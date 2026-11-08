# AI Tools Portfolio — Maria Myers

**Live site: https://mariavmyers.github.io/ai-tools-portfolio/**

Click-to-try AI tools built with Claude Code by Maria Myers, a medical and legal interpreter (EN · PT · ES · IT, about 20 years) and founder of [QueryTrends.ai](https://querytrends.ai).

## Featured: LinguaCheck — Meta Global AI Developer Hackathon 2026
Asks Meta's Muse Spark Open the same medical, legal or finance question in English and Brazilian Portuguese, flags cross-lingual drift, and keeps a professional interpreter in the loop.
▶️ [Demo video](https://youtu.be/X9qs2wmBoCU) · 🚀 [Live app](https://huggingface.co/spaces/hugmarie/linguacheck) · 💻 [Repository](https://github.com/Mariavmyers/linguacheck) · 🎬 [Recording guide](https://mariavmyers.github.io/ai-tools-portfolio/linguacheck-recording-guide/)

## Tools in this repo

| Tool | What it does | Live demo |
|---|---|---|
| ⚖️ **Verdict Bench** | Blind "AI judge" brand audit comparing how global and Latin American AI models describe a brand. Weighted criteria, charts, exportable report. | [Try it](https://mariavmyers.github.io/ai-tools-portfolio/verdict-bench/) |
| 🏗️ **Data Center Impact Calculator** | ZIP code + role → distance from a proposed data center site (haversine, US Census centroids) and a tailored 3-step action plan. | [Try it](https://mariavmyers.github.io/ai-tools-portfolio/data-center-calculator/) |
| 📰 **QueryTrends Weekly Builder** | One-click newsletter writer for an AI-discoverability consultancy, with a fixed house style. | [Try it](https://mariavmyers.github.io/ai-tools-portfolio/newsletter-builder/) |
| 🎬 **LinguaCheck Recording Guide** | Shot list + scrolling teleprompter used to record the LinguaCheck hackathon demo. | [Open](https://mariavmyers.github.io/ai-tools-portfolio/linguacheck-recording-guide/) |

Also see **[QueryTrends X-Ray](https://github.com/Mariavmyers/querytrends-social)**, a website scanner + multilingual post scheduler built on the Blotato API. The same repo includes:
- 📣 **AdXR**: writes EN/ES/PT-BR ads from the *structure* of winning ads (never the words) and tests them free as organic posts through Blotato.
- 🏡 **AdSuperXR · Real Estate**: finds public "looking for a home" posts, matches each need to an investor's property list, and produces a client report that keeps buyers anonymous until they agree to an introduction.

## Honest labels
- **Verdict Bench** uses *demo scoring*: scores come from built-in text-signal rules, not live AI calls. The brand (Aurora Motors) and all responses are fictional.
- **Data Center Impact Calculator** is a portfolio demo with sample ZIP codes. The full version (all Missouri and Kansas ZIP codes) is part of the [Data Center Opportunity Group](https://community.mainentry.net).
- **QueryTrends Weekly Builder** shows pre-written sample issues here. The live version calls Claude with the same house-style prompt.
- No client, patient, or personal data is used anywhere.

## How it's built
Each tool is a single self-contained HTML page (no build step, no server), so it runs on free GitHub Pages hosting. Built with Claude Code.
