<p align="center">
  <img src="https://morphix.tools/og-default.png" alt="Morphix" width="600">
</p>

<h1 align="center">Morphix</h1>

<p align="center">
  Free online image converter. PNG, JPG, WebP, AVIF.<br>
  Fast, private, no registration required.
</p>

<p align="center">
  <a href="https://morphix.tools">Website</a> &middot;
  <a href="https://morphix.tools/api-docs">API Docs</a> &middot;
  <a href="https://morphix.tools/blog">Blog</a>
</p>

---

## What is Morphix?

Morphix is an image conversion tool that lets you convert, compress, resize, and crop images directly in your browser. No software to install, no account needed for basic usage.

### Supported formats

| From / To | WebP | AVIF | JPG | PNG |
|-----------|:----:|:----:|:---:|:---:|
| **JPG**   |  Yes |  Yes |  -  | Yes |
| **PNG**   |  Yes |  Yes | Yes |  -  |
| **WebP**  |   -  |  Yes | Yes | Yes |
| **AVIF**  |  Yes |   -  | Yes | Yes |

### Features

- **Format conversion** between JPG, PNG, WebP, and AVIF
- **Compression** with adjustable quality (1-100)
- **Resize** with aspect ratio preservation (up to 12000px)
- **Crop** with precise coordinates
- **Metadata removal** (EXIF, GPS, camera data) without re-encoding
- **Social media presets** for Instagram, YouTube, LinkedIn, Facebook, X, TikTok
- **Batch processing** with multiple files at once

### API

Morphix offers a public REST API for Pro users. Integrate image conversion directly into your workflow.

```
POST https://morphix.tools/api/v1/convert
Authorization: Bearer mk_live_...
```

Four endpoints available: `/convert`, `/crop`, `/resize`, `/remove-metadata`

Full documentation at [morphix.tools/api-docs](https://morphix.tools/api-docs).

### Plans

| | Free | Pro |
|---|---|---|
| Daily conversions | 10 | Unlimited |
| Max file size | 10 MB | 50 MB |
| Batch size | 5 files | Unlimited |
| API access | - | 10 req/s |
| Price | Free | 7 EUR/month |

### Privacy

- No tracking cookies
- Files are automatically deleted after 1 hour
- Privacy-first analytics (no Google Analytics)
- Metadata stripping available to protect your images before sharing

---

<p align="center">
  <a href="https://morphix.tools">morphix.tools</a>
</p>
