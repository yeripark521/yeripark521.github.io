# Yeri Park portfolio

This directory is a plain static website, ready to publish with GitHub Pages. It does not depend on the Claude Design runtime (`support.js` or `image-slot.js`).

## Replace the uploaded assets

GitHub Pages is static hosting, so images and PDFs are updated by replacing local files and pushing the change to GitHub.

| Content | Destination | Notes |
| --- | --- | --- |
| Profile photo | `images/profile.jpg` | Square image recommended; it is cropped to a circle. |
| Project images | `images/projects/pruning.jpg`, `onnx.jpg`, `haskell.jpg`, `lidar.jpg`, `wearable.jpg` | Images or animated GIFs; change the matching extension in `projects.html` if using GIF/PNG. |
| CV | `assets/Yeri-Park-CV.pdf` | This exact filename is used by the home, CV, and download links. |

The site deliberately shows an empty labelled placeholder when a project/profile image has not yet been provided, so it can be published safely before photos are added.

## Publish to GitHub Pages

1. Commit and push this repository's `main` branch to `yeripark521/yeripark521.github.io`.
2. In GitHub: **Settings → Pages → Build and deployment**, select **Deploy from a branch**, then choose `main` and `/ (root)`.
3. The website will become available at `https://yeripark521.github.io/`.

Because this is a personal-site repository, its root URL is `https://yeripark521.github.io/`.
