# Lucky Draw Spinner — GitHub Pages

## Publish it with GitHub Pages

1. Sign in to https://github.com/
2. Create a new repository (for example: `lucky-draw`).
3. If you want the site to be publicly accessible, set the repository to **Public**.
4. Upload `index.html` from this folder to the repository's root (top level).
5. Open the repository's **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then click **Save**.
8. Wait for GitHub Pages to publish. The site URL will look like:
   `https://YOUR-USERNAME.github.io/lucky-draw/`

## Important security note

This is a static demo. The username and password are stored in the page's JavaScript, so anyone who can view the public page's source can discover them. GitHub Pages does not provide server-side password authentication. Do not use this demo login to protect a real or confidential draw. For genuine access control, use a backend or an authentication service (for example, Firebase Authentication) and keep credentials off the client.

## Default demo login

- Username: `Admin`
- Password: `Lucky@2026`
