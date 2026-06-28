CALL SHEET PWA — GitHub Pages Upload

1. Create a NEW public GitHub repo, for example: callsheet
2. Unzip this folder.
3. Upload every file inside the unzipped folder to the repo root:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - icon-180.png
   - icon-192.png
   - icon-512.png
4. Go to Settings → Pages.
5. Set Source to "Deploy from a branch".
6. Select branch: main and folder: /root.
7. Save.
8. Open the Pages URL in iPhone Safari.
9. Tap Share → Add to Home Screen.

Important:
The saved base playbook uses localStorage, which is device/browser-specific.
That means each coach's phone keeps its own saved playbook locally.
GitHub hosts the app files; it does not store users' playbooks.
If you change repo name or URL, Safari treats it as a different app/site and the saved data will not automatically transfer.
