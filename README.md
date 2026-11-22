# 🌿 Space Journey Research Lab (`spacelabdevteam-hub`)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22756473.svg)](https://doi.org/10.5281/zenodo.22756473)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/spacelabdevteam-hub/sensory-impact-score-datasets/blob/main/explore_global_sensory_benchmark.ipynb)
[![WHO Acoustic Guideline](https://img.shields.io/badge/WHO_Guideline-53_dB_Lden-006699)](https://spacejourney.app/standards/sensory-impact-score/)
[![Hugging Face Hub](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-spacejourney-FFD21E)](https://huggingface.co/spacejourney)
[![Hugging Face Article](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Technical%20Article-yellow.svg)](https://huggingface.co/blog/spacejourney/measuring-urban-quiet-acoustic-telemetry-elevation)
[![Live MCP Server](https://img.shields.io/badge/MCP_Endpoint-Cloudflare_Workers_SSE-10B981)](https://space-journey-engine.spacelab-mcp.workers.dev/mcp)
[![Canonical Portal](https://img.shields.io/badge/Web-spacejourney.app-E8C57D)](https://spacejourney.app/)
[![GitHub Discussions](https://img.shields.io/badge/Discussions-Join%20Debate%20%235-059669?style=flat&logo=github)](https://github.com/spacelabdevteam-hub/space-journey-mcp-engine/discussions/5)

> **The 21st-Century Open Standard for Contemplative Travel, Urban Acoustic Health, and Sensory AI Routing.**  
> *Aligned with the World Health Organization (WHO) 53 dB Lden environmental noise guidelines and cited via CERN Zenodo ([`10.5281/zenodo.22756473`](https://doi.org/10.5281/zenodo.22756473)).*

<div align="center">
  <br />
  <a href="https://huggingface.co/blog/spacejourney/measuring-urban-quiet-acoustic-telemetry-elevation">
    <img src="https://huggingface.co/spaces/spacejourney/sensory-impact-explorer/resolve/main/assets/og-sensory-earth.png" width="100%" alt="Space Journey — Sensory Earth & Acoustic Telemetry (SIS Index v3.0)" style="border-radius: 14px; box-shadow: 0 8px 32px rgba(232, 197, 125, 0.3); border: 1px solid rgba(232, 197, 125, 0.45);" />
  </a>
  <p>
    <b>📖 Official Technical Publication (Hugging Face Blog · DR 88):</b> <br />
    <a href="https://huggingface.co/blog/spacejourney/measuring-urban-quiet-acoustic-telemetry-elevation">
      <em>Measuring Urban Quiet: Acoustic Telemetry, Elevation Profiles, and the Open Sensory Impact Score (SIS v3.0)</em>
    </a>
    <br />
    <sub>Authored by Daniel Adolfo Duque Romero & Space Lab Research Team · Permanent CERN Zenodo Archive: <a href="https://doi.org/10.5281/zenodo.22756473"><code>10.5281/zenodo.22756473</code></a></sub>
  </p>
  <br />
</div>


> [!NOTE]
> 💬 **Scientific Peer Review & Community Debate:** We invite urban planners, soundscape ecologists, and AI developers to join [**GitHub Discussion #5: Urban Acoustic Telemetry & SIS Index v3.0**](https://github.com/spacelabdevteam-hub/space-journey-mcp-engine/discussions/5) alongside our [Hugging Face Technical Publication](https://huggingface.co/blog/spacejourney/measuring-urban-quiet-acoustic-telemetry-elevation).

---

## Open tool · Sensory Earth Music Bridge — Open Source Kit

**[Try Sensory Earth Music Bridge](https://github.com/spacelabdevteam-hub/music-library-kit)** — A dependency-free CSV/JSON music metadata preparer with a local-worker browser demo, tests, synthetic examples and a documented file handoff to [Sensory Earth](https://spacejourney.app/earth/). [Try the live demo on Hugging Face](https://huggingface.co/spaces/spacejourney/music-library-kit), or run it locally with `npm start`.

**ES:** Prepara tu biblioteca en el navegador y descarga lotes compatibles con Earth.  
**PT:** Prepare sua biblioteca no navegador e baixe lotes compatíveis com o Earth.

MIT-licensed utility; no private resolver or catalog included. Developed with substantial OpenAI Codex / GPT-6 assistance. This product release makes no grant-funding or eligibility claim.

---

## Development update · 22 November 2026

**[Sensory Earth: music-library imports and geographic discovery](updates/2026-11-22-sensory-earth-music-import.md)** — A status report on public-link, library-file and authorized account-import work, with verification limits and platform dependencies. [Open the official experience](https://spacejourney.app/earth/).

**ES:** Avances en importación musical y exploración geográfica, con estado comprobado y límites documentados.  
**PT:** Avanços na importação musical e exploração geográfica, com estado verificado e limites documentados.

This is a product-development report, separate from the spatial-routing research. It does not release importer code or change existing software licenses. Prepared with OpenAI Codex assistance; see the note for editorial provenance.

---

## 🏛️ Open Digital Commons Architecture (The Triad of Repositories)

| Repository | Layer | Purpose & Live Endpoint |
| :--- | :---: | :--- |
| 🧠 **[`space-journey-mcp-engine`](https://github.com/spacelabdevteam-hub/space-journey-mcp-engine)** | **AI Protocol (MCP v3.0)** | Zero-Auth **Model Context Protocol (MCP)** server & **Kairós IATA Routing Protocol** for Claude, Cursor, OpenWebUI, Llama, Mistral & Gemini. Live endpoint: `https://space-journey-engine.spacelab-mcp.workers.dev/mcp` |
| 📊 **[`sensory-impact-score-datasets`](https://github.com/spacelabdevteam-hub/sensory-impact-score-datasets)** | **Open Data (CC-BY-4.0)** | Verified acoustic (dB), photic (lx), and crowd-density (pax/m²) urban benchmarks across **Rome, Paris, and Mexico City (CDMX)** + 1-Click Google Colab notebooks. |
| 🎮 **[`the-sensory-atlas-prototype`](https://github.com/spacelabdevteam-hub/the-sensory-atlas-prototype)** | **Spatial WebGL (`<1MB`)** | Isometric Three.js WebGL playable experience translating urban acoustic harmony into interactive art. [Live Demo](https://spacejourney.app/play/roma-atlas/) |

---

## ⚡ Connect Your AI Agent in 15 Seconds (Zero-Auth MCP)

```json
{
  "mcpServers": {
    "space-journey-engine": {
      "url": "https://space-journey-engine.spacelab-mcp.workers.dev/mcp"
    }
  }
}
```

---

## 🌍 Live Ecosystem & Public Tools

- **Sensory Impact Score (SIS) Technical Standard:** [https://spacejourney.app/standards/sensory-impact-score/](https://spacejourney.app/standards/sensory-impact-score/)
- **Interactive 1-Click Contemplative Planner:** [https://spacejourney.app/planificador-de-viajes/](https://spacejourney.app/planificador-de-viajes/)
- **Sensory Earth (3D WebGL Globe — 227 Countries):** [https://spacejourney.app/earth/](https://spacejourney.app/earth/)
- **Trip Saver Browser Extension (Chrome Web Store):** [https://spacejourney.app/extension-viajes-chrome-safari/](https://spacejourney.app/extension-viajes-chrome-safari/)
- **Hugging Face Datasets & Interactive Space:** [https://huggingface.co/spacejourney](https://huggingface.co/spacejourney)
