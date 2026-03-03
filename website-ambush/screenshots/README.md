# Website Ambush - Screenshot Hosting

Static image hosting for email campaigns.

## Structure

```
screenshots/
└── pdfmerging-demo/
    ├── demo-screenshot-desktop-thumb.png
    └── demo-screenshot-mobile-thumb.png
```

## Usage

Images are served via GitHub raw URLs:

```
https://raw.githubusercontent.com/[USER]/website-ambush/master/screenshots/pdfmerging-demo/demo-screenshot-desktop-thumb.png
```

Used in HTML emails as:
```html
<img src="https://raw.githubusercontent.com/.../demo-screenshot-desktop-thumb.png">
```

## Auto-Upload Script

Run `upload-screenshots.sh` after generating new screenshots to push to GitHub.
