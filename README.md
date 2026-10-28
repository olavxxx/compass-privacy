# Compass privacy site

Public GitHub Pages source for the Compass privacy policy.

Live URL (once Pages is enabled):

```
https://olavxxx.github.io/compass-privacy/
```

## One-time setup

1. Create a **public** repository `olavxxx/compass-privacy` on GitHub.
2. Push this folder to it:

   ```powershell
   git remote add origin git@github.com:olavxxx/compass-privacy.git
   git branch -M main
   git push -u origin main
   ```

3. In the repository: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main`, folder `/ (root)`
4. Wait for the green Pages deployment, then open the URL and confirm it loads.
5. Put the same URL in `android-compass/store/listing.md` (already pre-filled).

`index.html` is the same file as `android-compass/store/privacy-policy.html`; update both when the
policy changes.
