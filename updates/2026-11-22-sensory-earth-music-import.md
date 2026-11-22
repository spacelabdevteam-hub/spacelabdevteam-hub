# Sensory Earth: music-library import development update

Published: 22 November 2026  
Project: [Space Journey](https://spacejourney.app/) · [Open Sensory Earth](https://spacejourney.app/earth/)  
Languages: [English](#english) · [Español](#español) · [Português](#português)

## English

### What we are developing

Sensory Earth connects personal music references with geographic discovery. Recent work adds entry points for public music links, user-supplied library files, and account-based imports where a provider connection is configured and authorized.

This is library and metadata import, not audio transcription, downloading, or ownership transfer. Importing a reference does not guarantee an identical recording or an available playable match.

### Status and evidence

| Capability | Evidence reviewed for this update | Limit |
| --- | --- | --- |
| Public music links | Local implementation and entry interface for Spotify, YouTube, Apple Music, Deezer, SoundCloud and TIDAL | Coverage varies by provider, link type, permissions and availability; not every flow was tested end to end. |
| User-supplied files | Local CSV/JSON parsing paths; additional Apple library-file handling | Supported fields and import limits vary; this note does not certify lossless migration. |
| Account imports | Local Spotify and YouTube account-connection paths; public entry controls | Requires provider configuration and user authorization. Account authentication and private-library imports were not exercised in this review. |
| Geographic discovery | Local artist-to-country association and personal-library integration | Associations can be incomplete or inferred; they are not proof of nationality or cultural origin. |
| Public entry | The official Earth page returned HTTP 200 on 22 November 2026 and contained music-source, Spotify file-upload and YouTube account-entry controls | An available interface does not establish that every backend path is working. |

### Connection to Space Journey

The official destination for this experience is [Sensory Earth on spacejourney.app](https://spacejourney.app/earth/). It connects the library-import entry with the globe and geographic exploration in one hosted experience.

Developers and collaborators can reference this page and direct users to the official experience. No standalone importer package, public resolver API, third-party upload endpoint or new MCP tool is released by this update. Existing MCP tools retain their documented scope.

The integration implementation, matching rules, curated catalogs, account credentials and operational configuration are not included in this publication.

### User control and platform boundaries

- Music references can help a person explore beyond a single provider's interface. Playback still depends on the selected external provider and its availability.
- Public links and user-supplied files are distinct from account access. Account import requires the person's authorization.
- This update does not claim full offline operation, independence from proprietary platforms, anonymous processing, or complete local-only storage.
- Third-party recordings remain subject to their owners' rights. An embedded YouTube player does not guarantee artist royalties for every playback.
- Platform terms, attribution, player visibility, advertising and account-disconnection requirements continue to apply.

This music-discovery work is distinct from the spatial routing and Sensory Impact Score research. It does not establish acoustic measurements, health outcomes, or scientific validation of that research.

### Collaboration and reuse

We welcome user reports about import compatibility, accessibility, incorrect artist-country associations and unavailable playback through [the Space Journey website](https://spacejourney.app/). Please do not post passwords, access tokens, private playlists or listening-history exports in public GitHub reports.

Reference the project as **Space Journey — Sensory Earth** and link to the [official experience](https://spacejourney.app/earth/). A link identifies the origin and destination; it does not technically require forks or third-party applications to use our service. Any future software release will need explicit licensing and a documented integration contract.

This note does not change existing repository licenses or grant rights to private implementation, third-party music, catalogs or trademarks. It is a development report, not a software release.

### Editorial provenance

This update was prepared with OpenAI Codex assistance, using source inspection and a public-page availability check. It is product-development documentation, not a grant proposal, evaluation response or claim of funded work. The review did not include signed-in provider sessions, full production import tests, or a complete security or platform-policy audit.

## Español

Sensory Earth incorpora trabajo de importación de referencias musicales mediante enlaces, archivos y conexiones de cuenta cuando están configuradas y autorizadas. El destino oficial es [Space Journey — Sensory Earth](https://spacejourney.app/earth/).

La revisión confirmó código local y controles en la entrada pública; no verificó todos los flujos con cuentas reales. Se importan referencias y metadatos: no se transcribe audio, no se transfieren derechos musicales y no se garantizan regalías por reproducción. La reproducción sigue dependiendo de plataformas externas.

Esta publicación documenta desarrollo del producto. No publica el importador, una API nueva, catálogos privados ni credenciales, y no cambia las licencias existentes. El trabajo musical se distingue de la investigación espacial y del SIS. Nota preparada con asistencia de OpenAI Codex; no es una solicitud ni respuesta de evaluación de una subvención.

## Português

O Sensory Earth inclui trabalho de importação de referências musicais por links, arquivos e conexões de conta quando configuradas e autorizadas. O destino oficial é [Space Journey — Sensory Earth](https://spacejourney.app/earth/).

A revisão confirmou código local e controles na entrada pública; não verificou todos os fluxos com contas reais. A importação trata referências e metadados: não transcreve áudio, não transfere direitos musicais e não garante royalties por reprodução. A reprodução continua dependente de plataformas externas.

Esta publicação documenta o desenvolvimento do produto. Não disponibiliza o importador, uma nova API, catálogos privados ou credenciais, nem altera as licenças existentes. O trabalho musical é distinto da pesquisa espacial e do SIS. Nota preparada com assistência do OpenAI Codex; não é uma candidatura nem uma resposta de avaliação de financiamento.
