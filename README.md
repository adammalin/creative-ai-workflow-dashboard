# Creative AI Operations Hub

Password-encrypted, local-first dashboard for Creative Services AI workflow planning, research, pilots, tool evaluation, and governance.

## Live dashboard

<https://adammalin.github.io/creative-ai-workflow-dashboard/>

The published `index.html` contains an AES-256-GCM encrypted application payload. A dashboard password is required before protected content is rendered. The password is distributed separately and is not stored in this repository.

Selecting **Remember this browser** stores a non-exportable decryption key in that browser's IndexedDB so subsequent visits can unlock automatically. Use **Forget remembered access** from the lock screen to remove it. Anyone with access to that browser profile can open the remembered dashboard.

The dashboard uses the Team App Library visual language with ORNL digital design tokens and square interface geometry.

> Exported JSON backups are plaintext and should be stored securely.
