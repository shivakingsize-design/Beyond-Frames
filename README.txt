# MotionXStudio portfolio

## Files
- `index.html` — page content
- `style.css` — layout, colours and responsive styling
- `script.js` — mobile menu, reveal effects and current year

## Preview on Android
1. Extract the ZIP using your phone's Files app.
2. Open `index.html` in a code editor with an HTML preview feature, or upload the files to GitHub and enable GitHub Pages.

## Add your own videos
1. Create an `assets` folder beside `index.html`.
2. Put your MP4 files inside it, for example `project-01.mp4` and `project-02.mp4`.
3. In `index.html`, find each `video-placeholder` block and replace it with:

```html
<video controls playsinline preload="metadata" poster="assets/project-01.jpg">
  <source src="assets/project-01.mp4" type="video/mp4">
</video>
```

For the second video, change both filenames to `project-02`.

Use compressed MP4 files so the website loads faster on mobile. Only upload work you created or have permission to show.

## Personalise contact links
In `index.html`:
- Replace `https://www.instagram.com/` with your Instagram profile URL.
- Replace `yourname@example.com` with your professional contact email.

## Free hosting with GitHub Pages (Android)
1. Sign in to GitHub or create an account.
2. Create a new **public** repository named `motionxstudio`.
3. Upload `index.html`, `style.css`, and `script.js` to the repository's root (top-level).
4. Open the repository's **Settings** → **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Wait a few minutes. GitHub will show your published website address in the Pages section. It will usually look like `https://YOUR-USERNAME.github.io/motionxstudio/`.

Keep the repository public for the free GitHub Pages option. Do not put private client footage, passwords, private data or unpublished client work in a public repository.
