# lawfirmMultiwebsites

Static multi-page website for J.M. KATHILI & COMPANY ADVOCATES (Machakos, Nairobi & Maturu, Kenya).

## Deploy to Vercel

The project is a static site and needs no build step.

### Option 1 — Dashboard

1. Push this repo to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import the repository.
4. Framework Preset: **Other** (auto-detected).
5. Build Command: *(none)*, Output Directory: `.` (default).
6. Click **Deploy**.

### Option 2 — CLI

```bash
npm i -g vercel
vercel
```

### Local preview

```bash
vercel dev
```

## Configuration

`vercel.json` enables clean URLs, so `/about`, `/services#civil-litigation`, etc. are served without the `.html` extension (the existing `.html` links still work via redirect).