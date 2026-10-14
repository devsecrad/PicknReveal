# Pick & Reveal

A static, peer-to-peer party game. Create a room, share its six-digit code or invite link, approve the crew, and let the coin decide whether each answer gets exposed.

## Run locally

Open `index.html` in a modern browser, or serve this folder with any static server. Internet access is required for the PeerJS connection broker and fonts.

## Publish free on GitHub Pages

1. Create a GitHub repository and upload these files to its default branch.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
4. Share the GitHub Pages URL. Hosts will create a six-digit room code and an invite link from within the game.

## Notes

- This v1 uses [PeerJS](https://peerjs.com/) via its public cloud broker, so there is no application server or database to deploy.
- The host’s open browser is the game authority. The room ends if it closes or reloads.
- All room data is in memory only and disappears after the session.
