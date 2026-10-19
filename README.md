
# AR Studio — WebAR prototype v0.1

This is a static, browser-based image-tracking
AR demo built with MindAR 1.2.5 and A-Frame 1.6.0.

## Run locally

1. Extract the ZIP.
2. In the extracted folder, run:
   python3 -m http.server 8000
3. Open http://localhost:8000 on the same
   computer. Camera support varies by device.

## Publish on GitHub Pages

1. Create a public GitHub repository,
   e.g. ar-studio.

2. Upload index.html and viewer.html to
   the repository root.

3. In Settings → Pages, choose:
   Deploy from a branch
   main
   / (root)
   Save

4. Wait for the published HTTPS URL.
   Open it on your phone.

5. Open the sample target on a second screen
   (or print it), tap Launch WebAR, allow
   camera permission, and point at the target.

## Notes

- Internet access is required for the external
  JavaScript libraries and sample target files.

- The sample target is hosted by the MindAR
  project's GitHub repository. If it is moved,
  replace both the image URL and .mind URL
  with a matching pair.

- This demo has no login, upload, publishing
  backend, or storage yet.

- Do not upload private client artwork to
  public repositories without permission.
