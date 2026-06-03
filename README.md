# ParallelKernelBench

A benchmark for parallel kernel generation and optimization.

Project page (GitHub Pages): `https://<your-username>.github.io/parallel-kernel-bench/`

## Local preview

This is a static site — no build step required. From the repo root:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy with GitHub Pages

1. Push this repo to GitHub (make sure `index.html` is at the repo root).
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`.
4. Your site will be live at `https://<your-username>.github.io/parallel-kernel-bench/`.

## Editing

All content lives in `index.html`:

- Title, subtitle, authors, and affiliations are in the header.
- Paper and Code buttons currently point to `#` (dummy links) — update the `href`s.
- The abstract is placeholder text.
- The BibTeX entry is in the citation section.
