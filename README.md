# DataCamp Credentials — Florian Braun

A single-page credential showcase hosted on GitHub Pages, grouping four DataCamp certifications under one URL for use on LinkedIn.

## Live site

> `https://lumenworksco.github.io/DataCamp/`

## Credentials

| # | Course | Status |
|---|--------|--------|
| 01 | Multi-Modal Models with Hugging Face | 🔄 Under Construction |
| 02 | Transformer Models with PyTorch | ✅ Issued Mar 2026 |
| 03 | Developing LLM Applications with LangChain | ✅ Issued Mar 2026 |
| 04 | Intermediate Deep Learning with PyTorch | ✅ Issued Mar 2026 |

## Updating the 4th credential

When the Hugging Face certificate is issued on DataCamp:

1. Open `index.html`
2. Find the card with `class="card wip"` (card 01)
3. Replace the entire card with this structure:

```html
<div class="card">
  <p class="card-number">01 / 04</p>
  <h2 class="card-title">Multi-Modal Models with Hugging Face</h2>
  <p class="card-issuer">DATACAMP · ISSUED MARCH 2026</p>
  <div class="skills">
    <span class="skill-tag">Hugging Face</span>
    <span class="skill-tag">Multi-Modal AI</span>
    <span class="skill-tag">Vision-Language</span>
    <span class="skill-tag">Transformers</span>
  </div>
  <div class="credential-block">
    <p class="credential-label">Credential ID</p>
    <p class="credential-id">PASTE_CREDENTIAL_ID_HERE</p>
  </div>
  <a class="cta" href="PASTE_DATACAMP_URL_HERE" target="_blank" rel="noopener">
    <svg width="12" height="12" viewBox="0 0 12 12" fill="none">
      <path d="M2 10L10 2M10 2H4M10 2V8" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"/>
    </svg>
    View on DataCamp
  </a>
</div>
```

## Repo structure

```
├── index.html       # Main page
├── og-image.png     # Open Graph preview image (1200×630)
├── favicon.ico      # Browser tab icon
├── .nojekyll        # Prevents GitHub Pages Jekyll processing
└── README.md
```

## Setup

1. Push this repo to GitHub
2. Go to **Settings → Pages → Source** and select `main` branch / root
3. GitHub Pages will publish at `https://<username>.github.io/<repo>/`
4. Paste that URL into the LinkedIn credential field

---

Built with vanilla HTML/CSS · Hosted on GitHub Pages
