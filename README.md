# Courtside

Fantasy basketball dashboard hosted on GitHub Pages at https://twostepp82.github.io/courtside/.

The site serves static HTML, CSS, and JavaScript. Imported rosters and standings remain in browser storage. This repository contains no saved league snapshots, Yahoo passwords, OAuth secrets, or cookies. GitHub Pages serves the interface publicly; it has no ChatGPT sign-in gate.

## Yahoo imports

Use **Paste from Yahoo** to import a readable roster or rotisserie standings table. Copy the table with its headers, preview the results, then apply the snapshot. Missing stats remain unknown. Only successfully imported tables appear.

## Optional 30-second browser sync

Download `yahoo-sync.zip` from the site and extract it into a permanent folder. In Chrome, open `chrome://extensions`, turn on Developer mode, choose Load unpacked, and select the extracted folder. Open your signed-in Yahoo league and this dashboard in the same Chrome profile, reload both tabs, and start sync using the extension popup. Chrome can delay refreshes while idle or asleep.

When moving from the previous hosted address, replace the helper files with this GitHub Pages version and reload the extension. It needs access to the new Pages host. Snapshots from the old site do not automatically carry across browser origins.

## Publishing

In Settings → Pages, publish from the `main` branch, `/ (root)` folder. `.nojekyll` enables plain static-file publishing. Changes to the root files deploy through GitHub Pages. No build step is needed.
