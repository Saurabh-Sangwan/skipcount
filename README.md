# SkipCount Pro

Camera-based jump-rope counter designed for phones.

## Deploy with GitHub Pages

1. Create a new GitHub repository, for example `skipcount`.
2. Upload **all files and folders** in this directory.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Open the HTTPS Pages URL on your phone.
7. Allow camera permission.
8. Optionally choose **Add to Home Screen** / **Install App**.

### Important
Do not open `index.html` directly as a `file://` URL. Camera access requires a secure context such as HTTPS (GitHub Pages) or localhost.

The app uses MediaPipe Pose from jsDelivr, so an internet connection is required for the first load/model download.
