# Smart Attendance System

This project uses a Teachable Machine face recognition model hosted via GitHub Pages to mark attendance in a mobile app built with MIT App Inventor.

## Files Included
- `index.html`: Loads the model and webcam
- `model.json`, `metadata.json`, `weights.bin`: Teachable Machine model files

## How to Use
- Host this repo with GitHub Pages
- Load the URL in MIT App Inventor's WebViewer
- Use `WebViewStringChanged` to capture recognized name
- Verify GPS location and store attendance in TinyDB

## Credits
- Built with Teachable Machine and MIT App Inventor
