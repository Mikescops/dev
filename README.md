# Corentin Mors — Dev Portfolio

<img src="https://avatars.githubusercontent.com/u/4266283?v=4&s=200" alt="Portrait of Corentin Mors" width="100" align="right" />

Development portfolio hosted on [GitHub Pages](https://pages.github.com/), available at **[dev.pixelswap.fr](https://dev.pixelswap.fr/)**.

## About

**Corentin Mors** is Co-founder and CTO of [Subnoto](https://subnoto.com). This site collects open-source projects and dev creations — security tools, Terraform providers, TypeScript libraries, browser extensions, and web apps.

## Related sites

| Site | URL | Description |
|------|-----|-------------|
| Dev | [dev.pixelswap.fr](https://dev.pixelswap.fr/) | This site — projects and open-source work |
| Profile | [me.pixelswap.fr](https://me.pixelswap.fr/) | Experience, talks, publications |
| Blog | [pixelswap.fr](https://pixelswap.fr/) | Personal blog |
| Subnoto | [subnoto.com](https://subnoto.com/) | Confidential e-signature platform |

## Contact

- **Email:** medias@pixelswap.fr
- **LinkedIn:** [linkedin.com/in/corentinmors](https://www.linkedin.com/in/corentinmors/)
- **Bluesky:** [@corentin.mors.dev](https://bsky.app/profile/corentin.mors.dev)
- **GitHub:** [github.com/Mikescops](https://github.com/Mikescops)

## Repository structure

```
├── index.html       # Main portfolio page
├── css/style.css    # Styles
├── robots.txt       # Crawler directives
├── sitemap.xml      # Search engine sitemap
├── llms.txt         # LLM-readable site summary
└── llms-full.txt    # Full structured project list for AI systems
```

## SEO & discoverability

The site includes:

- Semantic HTML (`main`, `section`, `header`, `footer`)
- Meta tags and Open Graph metadata
- [JSON-LD](https://schema.org/) structured data (`WebSite`, `Person`, `ItemList`)
- `robots.txt` and `sitemap.xml` for search engines
- [`llms.txt`](https://llmstxt.org/) and `llms-full.txt` for AI/LLM discoverability

## Development

This is a static site — no build step required. Push to the default branch and GitHub Pages serves it via the `CNAME` file (`dev.pixelswap.fr`).

To preview locally:

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## License

All rights reserved. Code may be partially reproduced; content is property of its owner.
