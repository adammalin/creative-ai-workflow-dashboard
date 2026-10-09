CREATIVE AI OPERATIONS HUB

1. Open index.html in a current browser.
2. Enter the dashboard password supplied separately.
3. Optionally select Remember this browser to unlock automatically next time.
4. Use the lock button when you finish.

The dashboard and its browser-saved edits are encrypted. The password is not
stored in this file. The vault also locks after 15 minutes without activity.
Remembered access stores a non-exportable key in that browser. From the lock
screen, use Forget remembered access to remove it. Anyone with access to the
remembered browser profile can open the dashboard.

IMPORTANT: Export data creates a plaintext JSON backup. Store exported backups
securely.

If the browser restricts Web Crypto for local files, serve this folder only on
the loopback interface:

  python3 -m http.server --bind 127.0.0.1 4173

Then open http://127.0.0.1:4173/
