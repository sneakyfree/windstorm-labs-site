# windstormlabs.com

The public website for **Windstorm Labs** — the engineering and AI-infrastructure arm of the Windstorm Institute. Builds and ships the Windy-* product family, runs the autonomous research fleet, mirrors the Institute's reproducibility code.

Live site: [windstormlabs.com](https://windstormlabs.com)

Sister site: [windstorminstitute.org](https://windstorminstitute.org) — the research arm.

## Structure

```
index.html      — Homepage: products, research code mirror, infrastructure, team
assets/
  images/       — Logos, screenshots, infrastructure photos
.github/
  workflows/
    deploy.yml  — Auto-deploy to Cloudflare Pages on push to main
```

## Engineering products (10 in the family as of May 2026)

| Product | URL | What it does |
|---------|-----|--------------|
| **Eternitas** | [eternitas.ai](https://eternitas.ai) | Identity / passport system for AI agents |
| **Windy Word** | [windyword.ai](https://windyword.ai) | Voice-to-text Electron app, 3,500+ specialized models |
| **Windy Chat** | [windychat.ai](https://windychat.ai) | Encrypted messaging + real-time translation |
| **Windy Clone** | [windyclone.ai](https://windyclone.ai) | Voice cloning + digital twin from your recordings |
| **Windy Cloud** | [windycloud.com](https://windycloud.com) | AI-creator cloud storage; soul files, voice models |
| **Windy Code** | [windycode.org](https://windycode.org) | AI-native IDE with chat/mail/voice built in |
| **Windy Fly** | [windyfly.ai](https://windyfly.ai) | Personal AI agent runtime |
| **Windy Mail** | [windymail.ai](https://windymail.ai) | Email built for humans and AI agents |
| **Windy Translate** | [windytranslate.com](https://windytranslate.com) | Translation engine (3,500+ models) powering the family |
| **Windy Traveler** | [windytraveler.com](https://windytraveler.com) | AI travel companion — translation, guides, planning |

## Research code mirror (12 reproducibility repos)

Reproducibility code for the Windstorm Institute's papers lives at [github.com/Windstorm-Labs](https://github.com/Windstorm-Labs). 12 repos, mirrored 1:1 with the Institute's paper publication repos. See the [research page](https://windstorminstitute.org) on the Institute site for the corresponding papers.

## Infrastructure

- **Primary compute:** Current-generation Nvidia GPU (32 GB VRAM, CUDA), Intel Core Ultra 9 285K, 256 GB RAM
- **Location:** Mount Pleasant, SC
- **Agent fleet:** Anthropic Claude, xAI Grok, Google Gemini, Perplexity Deep Research, and OpenAI in coordinated agentic configurations — large-scale empirical experiments, adversarial review, and multi-LLM verification workflows
- **Available for use** by the Institute and select collaborators

## License

Website content: CC BY 4.0. Engineering code in the Windy-* product repos: per-product (typically MIT or Apache). Research code mirror: MIT.

---

Auto-deploys to Cloudflare Pages on push to `main` via GitHub Actions.
