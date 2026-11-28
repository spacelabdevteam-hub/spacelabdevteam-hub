# London SIS v1.1 & The Sensory Atlas v2.0: open benchmark and modular WebGL update

Published: 28 November 2026  
Repositories: [`sensory-impact-score-datasets`](https://github.com/spacelabdevteam-hub/sensory-impact-score-datasets) · [`the-sensory-atlas-prototype`](https://github.com/spacelabdevteam-hub/the-sensory-atlas-prototype)  
Languages: [English](#english) · [Español](#español) · [Português](#português)

## English

### What changed

This update documents two open-source and open-data milestones completed on 28 November 2026 across Space Journey's public repositories:

1. **London Sensory Impact Benchmark (`cities/03_london`, SIS v1.1):** Upgraded from a single flat CSV to full structural parity with Rome (`01_rome`) and Paris (`02_paris`). Added normalized CSV and JSON datasets (`29` fields across `15` curated London sanctuaries), corrected five raw duration anomalies (`Cutty Sark`, `Tower of London`, `Primrose Hill`, `Sky Garden`, `St Katharine Docks`), recalculated biomechanical exertion from **ESA Copernicus DEM GLO-90** (`11.0 m` Thames basin baseline), added a zero-dependency Python schema and geospatial validator (`validate_london_dataset.py`), published an interactive Google Colab notebook (`explore_london_sensory_impact.ipynb`), and synchronized the package to [`spacejourney/london-sensory-impact-dataset`](https://huggingface.co/datasets/spacejourney/london-sensory-impact-dataset) on Hugging Face.
2. **The Sensory Atlas Prototype (`v2.0.0`, modular WebGL):** Refactored from a single legacy Three.js `r128` file into a zero-bundler **Three.js `r170` ES Modules** architecture (`src/scene.js`, `src/data.js`, `src/audio.js`, `src/i18n.js`, `src/main.js`, `src/styles.css`). Implemented a true `35.264°` isometric `OrthographicCamera` with live Perspective toggle, connected the viewer directly to the open FAIR JSON benchmarks for Rome, Paris, and London (with verified offline fallback), scaled pedestal relief from ESA Copernicus DEM elevation, added an optional muted-by-default Web Audio API soundscape, enforced native `EN / ES / PT` parity and `prefers-reduced-motion` accessibility, and added a zero-dependency Node.js test suite running in GitHub Actions CI.

### Status and evidence

| Artifact | Verification performed on 28 November 2026 | Explicit limits |
| :--- | :--- | :--- |
| `cities/03_london` (SIS v1.1) | `validate_london_dataset.py` passed (`15/15` sanctuaries, CSV/JSON parity, Greater London WGS84 bounds, Copernicus DEM relief/exertion math, zero HTML entities); `15/15` English canonical URLs returned HTTP `200`; synced to Hugging Face Hub. | Observational and curated urban planning benchmark; not a certified ISO/IEC Class 1 acoustic laboratory measurement or clinical health claim. |
| `explore_london_sensory_impact.ipynb` | JSON schema and Python AST syntax verified across all code cells; raw CSV endpoints on GitHub and Hugging Face returned HTTP `200`. | Notebook charts were validated syntactically and against live CSV structure; visual rendering in Google Colab requires interactive runtime execution by the reader. |
| `the-sensory-atlas-prototype` v2.0 | `node --test tests/verify_prototype.mjs` passed `5/5` locally and in GitHub Actions CI (`Validate Sensory Atlas Prototype`, commit `a0b6e97`); jsDelivr Three.js `r170` modules and FAIR JSON URLs returned HTTP `200`. | Procedural architectural abstraction intended as a lightweight spatial data viewer (`<100 KB`), not photogrammetric or CAD monument reconstruction. |

### Licensing and provenance

- **Code (`the-sensory-atlas-prototype`):** MIT License.
- **Data (`sensory-impact-score-datasets`):** CC BY 4.0, archived via CERN Zenodo ([DOI `10.5281/zenodo.22756473`](https://doi.org/10.5281/zenodo.22756473)).
- **Editorial provenance:** Prepared with AI engineering assistance (Antigravity / Gemini) using direct source inspection, automated test execution, and live HTTP verification. This update documents public open-source progress and makes no grant-funding or eligibility claim.

---

## Español

Esta actualización documenta dos entregas abiertas publicadas el 28 de noviembre de 2026:

- **Dataset de Londres (`cities/03_london`, SIS v1.1):** normalización completa en CSV y JSON (15 santuarios, 29 campos, telemetría ESA Copernicus DEM GLO-90, corrección de 5 duraciones anómalas), validador Python sin dependencias (`validate_london_dataset.py`), notebook interactivo para Google Colab y sincronización en Hugging Face (`spacejourney/london-sensory-impact-dataset`).
- **The Sensory Atlas Prototype (`v2.0.0`):** refactorización modular con **Three.js `r170` ES Modules**, cámara ortográfica isométrica real a `35.264°` (con cambio a perspectiva), consumo en vivo de los datasets FAIR de Roma, París y Londres (con respaldo offline), audio procedimental Web Audio API opcional, soporte nativo **EN / ES / PT** y suite de tests en GitHub Actions CI en verde.

Límites explícitos: el benchmark urbano SIS es una referencia abierta curada (no un ensayo de laboratorio acústico certificado) y el visor 3D es una abstracción arquitectónica procedimental ligera (no reconstrucción fotogramétrica CAD). Nota técnica de progreso abierto; no constituye una afirmación de financiación ni de elegibilidad de subvención.

---

## Português

Esta atualização documenta duas entregas abertas publicadas em 28 de novembro de 2026:

- **Dataset de Londres (`cities/03_london`, SIS v1.1):** normalização completa em CSV e JSON (15 santuários, 29 campos, telemetria ESA Copernicus DEM GLO-90 e correção de 5 durações), validador Python sem dependências (`validate_london_dataset.py`), notebook interativo para Google Colab e sincronização no Hugging Face (`spacejourney/london-sensory-impact-dataset`).
- **The Sensory Atlas Prototype (`v2.0.0`):** arquitetura modular em **Three.js `r170` ES Modules**, câmera ortográfica isométrica real a `35.264°`, consumo ao vivo dos datasets FAIR de Roma, Paris e Londres (com fallback offline), áudio procedural Web Audio API opcional, suporte nativo **EN / ES / PT** e testes automatizados em verde no GitHub Actions CI.

Limites explícitos: o benchmark urbano SIS é uma referência aberta curada (não uma certificação acústica laboratorial) e o visualizador 3D é uma abstração procedural leve (não fotogrametria CAD). Registro técnico de desenvolvimento aberto; não representa reivindicação de financiamento ou elegibilidade.
