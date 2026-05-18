---
name: open-design
description: |
  Open-source design skill catalog — 31 composable skills for UI/UX, creative direction, animation, color science, marketing copy, and cross-platform design. Acts as a discovery hub: when the user asks for design work, use this catalog to identify the right upstream skill and invoke it by name or trigger phrase. Source: nexu-io/open-design.
triggers:
  - "open design"
  - "design catalog"
  - "which design skill"
  - "what design skills are available"
od:
  repo: "https://github.com/nexu-io/open-design"
  license: Apache-2.0
---

# Open Design

Open-source alternative to Claude Design. A curated catalog of 31 composable design skills covering UI prototypes, presentations, creative direction, color science, animation, and marketing — running on any local coding agent.

## How to use

When the user asks for design work, consult the catalog below to identify the right skill, then invoke it by name or trigger phrase. Each skill entry lists its upstream source for full reference files and scripts.

Two modes across all skills:
- **Prototype mode** (27 skills) — web prototypes, SaaS landings, dashboards, mobile apps, social carousels, decks, document templates
- **Deck mode** (4 skills) — presentation frameworks

---

## Skill Catalog

### Design Systems

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `frontend-design` | Distinctive production-grade interfaces; avoid generic AI aesthetics | "frontend design", "ui design", "web design" | anthropics/skills |
| `frontend-skill` | Visually strong landing pages and app UIs with restrained composition. OpenAI's production frontend playbook | "landing page", "frontend playbook", "ui composition" | openai/skills |
| `platform-design` | 300+ design rules from Apple HIG, Material Design 3, and WCAG 2.2 for cross-platform apps | "platform design", "cross platform design", "material design", "hig rules", "wcag rules" | ehmo/platform-design-skills |
| `apple-hig` | Apple Human Interface Guidelines as 14 agent skills for iOS, macOS, visionOS, watchOS, tvOS | "apple hig", "human interface", "ios design", "macos design", "visionos design" | raintree-technology/apple-hig-skills |
| `color-expert` | Color science with 286K words covering OKLCH/OKLAB, palette generation, accessibility/contrast, pigment mixing, historical color theory | "color theory", "palette generator", "color science", "oklch palette", "contrast check" | meodai/skill.color-expert |
| `design-md` | Create and manage DESIGN.md files — design tokens and visual rules in a single source of truth | "design.md", "design doc", "design tokens doc", "visual rules doc" | google-labs-code/skills |

### Creative Direction

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `creative-director` | AI creative director with recursive self-assessment: 20+ methodologies (SIT, TRIZ, Bisociation, SCAMPER, Synectics), 3-axis evaluation calibrated against Cannes/D&AD/HumanKind, 5-phase process from brief to presentation | "creative director", "campaign concept", "creative critique", "cannes review", "scamper" | smixs/creative-director-skill |
| `design-brief` | Parse design briefs into concrete specifications resolving 8 dimensions: color palette, accent color, typography, layout model, mood, density, and constraints. Outputs DESIGN.md + brief-preview.html | "design brief", "parse brief", "design spec" | nexu-io/open-design |
| `design-consultation` | Interactive design consultation to define project direction | "design consultation", "design direction" | nexu-io/open-design |
| `design-review` | Review and critique existing designs against established principles | "design review", "critique design" | nexu-io/open-design |

### Animation & Motion

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `gsap-core` | Core GSAP API: gsap.to(), from(), fromTo(), easing, duration, stagger, and defaults | "gsap", "gsap core", "web animation", "tween", "easing" | greensock/skills |
| `gsap-react` | GSAP integration with React: useGSAP hook, context management, and timeline cleanup | "gsap react", "react animation", "useGSAP" | greensock/skills |
| `gsap-scrolltrigger` | Scroll-driven animations with ScrollTrigger: pinning, scrubbing, and snap | "scrolltrigger", "scroll animation", "scroll-driven" | greensock/skills |
| `gsap-timeline` | Complex sequenced animations with GSAP Timeline: labels, callbacks, and nested timelines | "gsap timeline", "animation sequence", "timeline" | greensock/skills |

### Marketing & Copy

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `copywriting` | Write and rewrite marketing copy for landing pages, homepages, and ads | "copywriting", "landing copy", "ad copy", "homepage copy", "rewrite copy" | coreyhaines31/marketingskills |
| `marketing-psychology` | Apply psychological principles and behavioral science to marketing copy and design | "marketing psychology", "behavioral copy", "persuasion", "framing", "cognitive bias" | coreyhaines31/marketingskills |
| `paywall-upgrade-cro` | Conversion rate optimization for paywalls and upgrade flows | "paywall", "upgrade flow", "cro", "conversion" | nexu-io/open-design |

### UI Components & Layouts

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `login-flow` | Design and implement authentication flows: login, signup, forgot password | "login flow", "auth flow", "signup page" | nexu-io/open-design |
| `faq-page` | Design and build FAQ page layouts | "faq page", "faq design" | nexu-io/open-design |
| `resume-modern` | Generate modern, typographically strong resume layouts | "resume", "cv design", "modern resume" | nexu-io/open-design |

### Decks & Presentations

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `deck-swiss-international` | Swiss International Typographic Style presentation decks | "swiss design deck", "international typographic", "helvetica deck" | nexu-io/open-design |
| `deck-open-slide-canvas` | Open slide canvas for free-form presentation design | "open slide", "canvas deck", "freeform presentation" | nexu-io/open-design |
| `deck-guizang-editorial` | Magazine-style editorial presentation framework | "guizang", "editorial deck", "magazine presentation" | nexu-io/open-design |
| `pptx-generator` | Generate PowerPoint-compatible .pptx files | "pptx", "powerpoint", "generate slides" | nexu-io/open-design |

### Documents & Reports

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `doc` | Generate clean document layouts in HTML | "document", "doc layout", "text document" | nexu-io/open-design |
| `data-report` | Design data-driven reports with charts and tables | "data report", "analytics report", "report design" | nexu-io/open-design |
| `release-notes-one-pager` | Design polished one-page release notes | "release notes", "one pager", "changelog design" | nexu-io/open-design |

### Posters & Visual Content

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `poster-hero` | Create large-format hero poster designs | "poster", "hero poster", "large format" | nexu-io/open-design |
| `ad-creative` | Design ad creatives for digital marketing | "ad creative", "banner ad", "display ad" | nexu-io/open-design |
| `card-twitter` | Design Twitter/X card visuals | "twitter card", "x card", "social card" | nexu-io/open-design |
| `card-xiaohongshu` | Design Xiaohongshu (Little Red Book) card visuals | "xiaohongshu", "red book card", "小红书" | nexu-io/open-design |

### Data Visualization

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `d3-visualization` | Build interactive data visualizations with D3.js | "d3", "d3 chart", "data visualization", "interactive chart" | nexu-io/open-design |
| `frame-data-chart-nyt` | NYT-style editorial data chart frames | "nyt chart", "editorial chart", "news chart" | nexu-io/open-design |

### Utilities

| Skill | Description | Triggers | Upstream |
|-------|-------------|----------|----------|
| `enhance-prompt` | Enhance and refine design prompts for better AI output | "enhance prompt", "improve prompt", "refine brief" | nexu-io/open-design |
| `brainstorming` | Structured creative brainstorming for design problems | "brainstorm", "creative brainstorm", "ideate" | nexu-io/open-design |
| `full-page-screenshot` | Capture full-page screenshots of web designs | "screenshot", "full page capture" | nexu-io/open-design |

---

## design-brief Workflow (Built-in)

The `design-brief` skill parses briefs into concrete specifications across 8 dimensions:

1. **Color palette** — background/text hex values (e.g. `navy_and_white` → `#0F172A` / `#F8FAFC`)
2. **Accent color** — primary action color
3. **Body typography** — font + weight + size
4. **Display typography** — heading font + weight
5. **Layout model** — grid system and container widths
6. **Mood** — aesthetic direction (editorial, minimal, playful, etc.)
7. **Density** — spacing scale (compact, balanced, spacious)
8. **Constraints** — technical or brand restrictions

**Accepts:** I-Lang structured notation or natural language.

**Outputs:**
- `DESIGN.md` — 9-section design system (visual theme, colors, typography, components, layout, elevation, do's/don'ts, breakpoints, agent prompt guide)
- `brief-preview.html` — Visual preview with color swatches, type specimens, spacing rulers, and component examples

**Transparency:** Reports which dimensions defaulted and which rules applied.

---

## Upstream Repository

Full source, design systems (72 definitions), and all skill reference files:
`https://github.com/nexu-io/open-design`
