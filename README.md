# Ball Python Complete Pro

Self-contained web app for ball python care, breeding, genetics, clutches, and food stock.

## Deploy on GitHub Pages

1. Create a GitHub repository.
2. Upload **all files in this folder** to the **repository root** (or put them in a `docs/` folder).
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Branch: `main` (or `master`), folder: `/ (root)` — or `/docs` if you used that.
6. Save, wait a minute, open the URL GitHub shows (e.g. `https://YOURUSER.github.io/REPO/`).

### Files that must be together
| File | Role |
|------|------|
| `index.html` | App (GitHub Pages looks for this name) |
| `manifest.webmanifest` | PWA / home-screen install |
| `icon-192.png` | Icon |
| `icon-512.png` | Icon |
| `apple-touch-icon.png` | iOS home-screen icon |

No build tools. Works offline after first load (data stays in the browser).

## Food stock + feeding
1. **More → Food** — add stock (e.g. Rat **XL / Jumbo** = 10).
2. **Care → Feed** — pick the snake, select **Rat XL / Jumbo** from the prey list, choose **Ate**, save.
3. That prey quantity is **removed from stock** automatically.
4. **Refused** does **not** deduct stock.
5. Bulk feed: type `XL rat` / `X-Large rat` and check Ate — matches catalog and deducts when stock allows.

## Dashboard shortcuts
Tap **Males**, **Females**, or **For sale** to open the animal list with that filter applied.
