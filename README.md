# marketing.me

Base de conocimiento y skills de marketing para usar con Claude Code (y otros agentes compatibles con el estándar [Agent Skills](https://agentskills.io)).

Este repositorio incorpora las skills, plantillas y guías del proyecto open-source [marketingskills](https://github.com/coreyhaines31/marketingskills) de [Corey Haines](https://corey.co), como punto de partida para automatizar y mejorar procesos de marketing, ventas y crecimiento.

## Estructura

- **`.claude/skills/`** — 50 skills de marketing en formato `SKILL.md`, listas para que Claude Code las use automáticamente en este proyecto (copywriting, SEO, CRO, email, ads, analítica, retención, GTM, estrategia, etc.). Cada carpeta incluye `SKILL.md`, `references/` y (cuando aplica) `evals/` y `assets/`.
- **`resources/marketing-toolkit/`** — Integraciones y CLIs de referencia para herramientas de marketing (GA4, Meta Ads, Google Ads, Klaviyo, HubSpot, Segment, etc.) tomadas del proyecto original.
- **`docs/marketing-skills-source/`** — Documentación original del proyecto fuente (README, changelog, guías para agentes, licencia) conservada para atribución y referencia.

## Cómo se usan las skills

Cuando trabajes con Claude Code en este repositorio, las skills en `.claude/skills/` se activan automáticamente según lo que pidas. Por ejemplo:

- "Ayúdame a escribir un email de bienvenida" → activa `emails` / `copywriting`.
- "Quiero un plan de marketing para mi cadena de farmacias" → activa `marketing-plan`.
- "Compara mis precios con la competencia" → activa `competitors` / `pricing`.
- "Dame ideas para crecer con presupuesto bajo" → activa `marketing-ideas` / `marketing-loops`.

La skill `product-marketing` es la base: conviene definirla primero (producto, audiencia, posicionamiento) porque el resto de skills la usan como contexto.

## Créditos

Las skills y herramientas en `.claude/skills/` y `resources/marketing-toolkit/` provienen de [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills), publicado bajo licencia MIT (ver `docs/marketing-skills-source/UPSTREAM-LICENSE.txt`). Todo el crédito de ese contenido es para Corey Haines y los contribuidores del proyecto original.

## Próximos pasos

Este repositorio es la base. A partir de aquí se pueden agregar:

- Contexto propio del negocio (farmacias, trading/inversiones) para personalizar las skills.
- Plantillas y automatizaciones específicas.
- Notas y sistemas de seguimiento para procesos de marketing, ventas e inversión.
