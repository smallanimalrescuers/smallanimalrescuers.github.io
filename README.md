# Small Animal Rescuers website

Static site served by GitHub Pages. `index.html` loads `app.js`, which is **generated** from `src/app.jsx`.

## Editing

- Edit text, puppies, colours and translations in **`src/app.jsx`** (never edit `app.js` by hand).
- Then rebuild:

```bash
npx esbuild@0.25.10 src/app.jsx --minify --target=es2018 --outfile=app.js
```

- Commit both `src/app.jsx` and `app.js`. Requires Node.js; nothing else to install.

## Analytics

Visitor stats use GoatCounter (no cookies). Replace `GOATCOUNTER_CODE` in `index.html` with the site code.
