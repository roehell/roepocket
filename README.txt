Pocket Ledger iPhone PWA (based on v2.8)

Upload ALL files in this folder to a dedicated GitHub Pages repository or other HTTPS static host, keeping them together at the same folder level.
Visit the hosted URL in iPhone Safari while online. Wait for first load to complete, then Share > Add to Home Screen. Open from the Home Screen. Test in Airplane Mode after initial installation.

This is a local-first offline app: expense data is saved in the browser/home-screen app storage, not in GitHub. Back up JSON often; Safari and installed home-screen app may not share data. Never assume data from a file:// copy transfers automatically.

Offline support is limited to the app shell and built-in functionality. External resources, if later added, need separate offline handling. PNG and print workflows require testing on iPhone.
