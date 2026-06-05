# JobCoin Landing Page

A polished static landing page for the JobCoin memecoin bounty.

## Files

- `index.html` — page structure and content
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and contract copy button

## Required Placeholder

The contract placeholder is included exactly as:

```text
CA: CYRr9XoH8kjofJJcQx7hD8FLAE4WgMjeAePBJMZUeTX
```

Replace it after the official JobCoin contract is live.

## Deploy

This is a static site and can be deployed directly to Netlify, Vercel, GitHub Pages, or any static host.

### Netlify

1. Drag and drop this folder into Netlify, or connect it from a Git repository.
2. Build command: leave empty.
3. Publish directory: `/` or the repository root containing these files.

### Vercel

1. Import the folder or repository into Vercel.
2. Framework preset: Other.
3. Build command: leave empty.
4. Output directory: leave empty or set to `.`.

## Local Preview

From this directory:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
