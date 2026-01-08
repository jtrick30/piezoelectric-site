# Favicon Installation for piezoelectric.ai

## Files Included

| File | Purpose |
|------|---------|
| `favicon.svg` | Animated favicon (Safari/Firefox) |
| `favicon-static.svg` | Static fallback |
| `favicon-16x16.png` | Browser tab icon |
| `favicon-32x32.png` | Browser tab icon (high-DPI) |
| `apple-touch-icon.png` | iOS home screen (180x180) |
| `android-chrome-192x192.png` | Android home screen |
| `android-chrome-512x512.png` | Android splash screen |
| `site.webmanifest` | PWA configuration |

---

## Installation Steps

### Step 1: Upload Files to GitHub

1. Go to your repo: `github.com/jtrick30/piezoelectric-effect`
2. Click **Add file** → **Upload files**
3. Drag and drop ALL the favicon files (except this instructions file)
4. Commit the changes

### Step 2: Update Your `index.html`

Find the `<head>` section of your `index.html` and **replace** any existing favicon lines with:

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Piezoelectric | Jason Trickovic, MD</title>
    
    <!-- Favicons -->
    <link rel="icon" type="image/svg+xml" href="/favicon.svg">
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
    <link rel="manifest" href="/site.webmanifest">
    <meta name="theme-color" content="#1B4D3E">
    
    <!-- ... rest of your head content ... -->
</head>
```

### Step 3: Clear Browser Cache

After uploading, you may need to hard-refresh your browser:
- **Mac**: `Cmd + Shift + R`
- **Windows**: `Ctrl + Shift + R`

Or clear your browser cache to see the new favicon.

---

## How It Works

- **Safari & Firefox**: Display the animated `favicon.svg` with the pulsing crystal and energy particles
- **Chrome & Edge**: Display the static `favicon-32x32.png` (they don't support animated SVG favicons)
- **iOS**: Uses `apple-touch-icon.png` when added to home screen
- **Android**: Uses the `site.webmanifest` icons

---

## The Design

Your favicon shows a 3D piezoelectric crystal on a deep green background (#1B4D3E) with golden energy particles radiating outward. This visualizes your brand concept: **pressure transformed into power**.

The animation (where supported) shows:
- Crystal facets gently pulsing
- Pressure arrows pushing in from top/bottom
- Golden energy bolts and particles discharging outward
- Subtle outer ring pulse

