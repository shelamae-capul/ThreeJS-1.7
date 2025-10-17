
## Setup
Download [Node.js](https://nodejs.org/en/download/).
Run this followed commands:

## Setup

Download Node.js: https://nodejs.org/en/download/

Commands (PowerShell / bash)

```powershell
# Install dependencies (run once)
npm install

# Run the local dev server (Vite default port is 5173)
npm run dev

# If you prefer to use port 8080, run Vite with the --port option:
npm run dev -- --port 8080

# Build for production (output goes into the `dist/` directory)
npm run build
```

Notes

- Vite's default dev port is 5173. If that port is already in use Vite will choose the next free port (for example 5174).
- Static assets placed in `static/` are served at the project root (for example `/textures/...`).
- To preview a production build you can add a `preview` script (optional):

```json
"scripts": {
	"dev": "vite",
	"build": "vite build",
	"preview": "vite preview --port 8080"
}
```

Then run:

```powershell
npm run preview
```
