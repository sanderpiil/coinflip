# coinflip

This is a single-file yes/no coinflip page. To use it, open `index.html` in any web browser (double-click it from your file explorer, or use your editor's “Open in Browser/Preview” feature). If you have Python installed, you can also serve it locally with:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/index.html`. 

## Windows .exe (optional)

If you want a double-clickable `.exe`, the easiest path is to wrap the HTML file with Electron via `nativefier`:

1. Install [Node.js](https://nodejs.org/).
2. In this folder, run:
   ```bash
   npx --yes nativefier index.html --name "Coinflip" --platform windows --arch x64
   ```
3. Open the generated `Coinflip-win32-x64` folder and run `Coinflip.exe`.
