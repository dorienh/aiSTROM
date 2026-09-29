# aiSTROM: turn AI ambition into an implementation strategy

**Choose worthwhile AI projects. Expose overlooked dependencies. Turn decisions into actions.**

**Version 1.0 · Created September 2026 · Dorien Herremans**

AI offers a substantial business opportunity, but adoption alone does not establish value:

| Opportunity | Implementation gap |
|---|---|
| **66% reported revenue increases** in business units using generative AI for marketing and sales in McKinsey's July 2024 survey. | **37% reported a positive enterprise-level profit impact** from AI in McKinsey's 2026 survey. |

The first figure concerns respondents whose organisations used generative AI in that function; the second concerns reported earnings before interest and tax (EBIT). They measure different outcomes in different surveys, not a causal comparison. [Revenue findings](https://www.mckinsey.com/featured-insights/charts/gen-ais-roi) · [2026 findings](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai).

The cost of poor implementation can be substantial. RAND's 2024 report cites estimates that **more than 80% of AI projects fail**. That is a cited estimate, not a failure rate measured by RAND. Its own interviews with 65 experienced practitioners identified recurring problems: misunderstood objectives, inadequate data, technology-first choices, insufficient infrastructure and tasks beyond the technology's capabilities. [RAND report](https://www.rand.org/pubs/research_reports/RRA2680-1.html).

**aiSTROM was developed to put strategic choices at the centre of AI implementation.** Published in [IEEE Access in 2021](https://doi.org/10.1109/ACCESS.2021.3127548), the framework connects the opportunity to seven dimensions: data, team, organisation, technology, value, risk and education. This visual toolkit translates those dimensions into decisions your business, domain and technical colleagues can work through together.

Use it to decide which opportunities deserve investment, what capabilities and information are missing, how success will be measured, and what must happen before the next commitment. It covers **predictive, generative and agentic AI**, from forecasting and computer vision to LLMs and agents. The research above motivates careful implementation; it does not measure the toolkit's effectiveness.

## Start here — three PDFs, no installation

**[Download the complete toolkit ZIP](https://raw.githubusercontent.com/dorienh/aiSTROM/main/aiSTROM-visual-toolkit-v1.0.zip)** — all three PDFs, the guide, previews and instructor materials.

1. **[Visual toolkit](https://raw.githubusercontent.com/dorienh/aiSTROM/main/starter-kit/aiSTROM-visual-toolkit.pdf)** — an overview plus seven fillable dimension sheets.
2. **[Completed purchasing strategy example](https://raw.githubusercontent.com/dorienh/aiSTROM/main/starter-kit/examples/procurement-visual-toolkit.pdf)** — all eight sheets assess whether and how AI could support a fictional manufacturer’s purchasing decisions.
3. **[Instructor guide](https://raw.githubusercontent.com/dorienh/aiSTROM/main/instructor-kit/aiSTROM-instructor-guide.pdf)** — a workshop plan, exercises and facilitation prompts.

The PDF links bypass GitHub's preview. Save them and open the fillable sheets in a form-capable reader. For a one-page discussion, use page 1 of the visual toolkit.

## See how it works

### Bring the decisions together

![aiSTROM overview canvas with opportunity, seven strategy dimensions and the next decision.](https://raw.githubusercontent.com/dorienh/aiSTROM/main/assets/worksheet-overview.png)

*The overview gives the team a shared view of the opportunity and the decisions that need to fit together. [Open the fillable toolkit](https://raw.githubusercontent.com/dorienh/aiSTROM/main/starter-kit/aiSTROM-visual-toolkit.pdf).*

### Go beneath each headline

![Completed Data sheet showing sources, acquisition, quality, privacy, storage and lifecycle decisions for a fictional procurement project.](https://raw.githubusercontent.com/dorienh/aiSTROM/main/assets/worksheet-data-example.png)

*Six subdimensions on the Data sheet turn “do we have the data?” into specific choices, strengths, gaps and actions. A completed card may still be marked unknown. This procurement example is a fictional strategic assessment, not a deployment or product comparison.*

## The framework behind the sheets

<img src="https://raw.githubusercontent.com/dorienh/aiSTROM/main/assets/aistrom-roadmap.png" alt="Original aiSTROM roadmap linking goals with data, the AI team, organisation, technologies, KPIs, risk and cultural change." width="480">

*Original aiSTROM roadmap, Herremans (2021), Figure 1, reproduced from the [open author version](https://arxiv.org/abs/2107.06071) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Cropped to the figure; diagram content unchanged. The visual worksheets are a practical adaptation, with contemporary prompts identified separately.*

## What your team should leave with

- **A clearer investment choice:** the problem, value, scope and alternatives.
- **Connected implementation decisions:** how data, people, technology and operating arrangements affect one another.
- **An evidence plan:** what to test or investigate, with owners and dates.
- **A strategic direction:** invest, prepare, defer or reject, with conditions for the next stage.

Work through the most consequential questions first. The aim is to improve the next decision, not to fill every box in one meeting.

## How the sheets fit together

| Sheet | Focus |
|---|---|
| **Overview** | Frame an opportunity, capture conclusions across seven dimensions, and record the next decision. |
| **1. Data** | Sources and future value; collection/acquisition; quality; privacy; storage; lifecycle and reuse. |
| **2. The AI team** | Domain expertise; technical skills; communication/design; obtaining expertise; retention; capacity. |
| **3. Organising AI development** | Team positioning; authority; portfolio; existing services; build/partner/acquire; agile delivery. |
| **4. Technologies** | Approach and baseline; models/adaptation; explainability; human involvement; hosting; integration. |
| **5. KPIs and value** | Strategic outcomes; customer value; processes; financial value; model performance; evidence and review. |
| **6. Risk level and benefits** | Performance uncertainty; bias/ethics/safety; security; dependencies; benefits/risk appetite; SWOT. |
| **7. Culture and education** | AI literacy; roles; participation; shared expertise; continuous education; adoption in practice. |

The original paper supplies the seven dimensions and many of their underlying topics. The six cards on each sheet are practical groupings, not a claim that the paper used these exact headings. Cards identify their source section or mark an added prompt. Conditional prompts at the bottom address particular system types without making every project an agent project.

## Fill in a card

Each dimension has six cards. Read the short prompt and record:

1. **Readiness:** `+ Supported`, `- Gap`, `? Unknown`, or `N/A` for the evidence needed to make the next decision.
2. **Strategic implication:** what AI would require, enable or change.
3. **+ Upside or strength:** a potential benefit or capability to build on.
4. **- Downside or gap:** a cost, dependency, limitation or missing capability.
5. **Next strategic action:** evidence to gather, with an owner and review date.

A card may have both strengths and gaps. Choose the status that best describes readiness for the next decision; keep both sides visible. Use `? Unknown` when evidence is missing, and explain `N/A`. The signs are discussion aids: do not add them into a score or let several strengths cancel an unresolved prerequisite.

For example, on **Data → Collect, acquire or label**:

- **Strategic implication:** training a custom purchasing model may require labelled decisions about acceptable substitutions; a service may need less training data but still receive proprietary documents.
- **+ Upside:** buyers and engineers can define the labels and critical constraints.
- **- Downside:** historical decisions and delivery outcomes are not linked, and supplier-document reuse rights are unclear.
- **Readiness:** `? Unknown`.
- **Next strategic action:** the data lead inventories usable records, labelling effort and rights before the company chooses a build or service route.

This is a fictional illustration, not a reported deployment. The card compares routes and prerequisites; product reviews and trials come after the strategic direction is set.

## Follow a complete example

The completed procurement example follows the same eight-sheet layout as the blank toolkit. Its 42 cards examine whether and how a fictional manufacturer should invest in AI for purchasing decisions. The overview connects requirements, upsides, downsides and unknowns into a conditional strategic direction. No product, provider or trial is selected.

It is a **fictional teaching scenario**. Roles, capabilities and organisational conditions are illustrative assumptions; no measured performance or deployment is claimed. `+ Supported` indicates a strength or known prerequisite within the scenario, not proof that AI will work. Many cards correctly remain `? Unknown` or `- Gap` after being filled in. A completed sheet is not the same as a resolved issue.

Use it to understand the level of strategic reasoning, not to copy its assumptions or choices into another organisation.

## Suggested working session

1. **Frame the opportunity.** Name the problem, affected people, desired outcome, scope and simpler alternatives in the overview's first box.
2. **Scan the seven dimensions.** Bring together business, domain and technical perspectives. Start with the sheets that could most change your decision.
3. **Compare upsides and downsides.** Ask what each route could enable, what it would cost or constrain, and which evidence is missing. Use short entries and link existing records rather than writing essays.
4. **Connect the dimensions.** A choice to fine-tune affects data, skills, hosting and costs. A new workflow affects roles, education and KPIs. Record dependencies at the bottom of each sheet.
5. **Return to the overview.** State whether to invest, prepare, defer or reject the opportunity. Name conditions, evidence, owner and review date for any later feasibility stage.

Use one set per opportunity. Compare multiple overview canvases when making portfolio decisions. Revisit affected sheets when goals, data, people, models, providers or operating conditions change.

## Using the files

All eight sheets are interactive PDF forms, designed at **A3 landscape** for a workshop table or screen. Print at A3 for comfortable handwriting. A4 printing reduces both text and writing space.

Use a PDF reader that supports forms; save and reopen your copy to check that entries were retained. Keep entries concise and put longer evidence in linked project records. The overview is page 1 of the toolkit; print that page alone when you only need the summary.

## For instructors and facilitators

The [instructor guide](https://raw.githubusercontent.com/dorienh/aiSTROM/main/instructor-kit/aiSTROM-instructor-guide.pdf) includes a session plan, learning outcomes, discussion prompts, and predictive-AI and procurement exercises. Start with the visual sheets and use the guide to facilitate a class or workshop.

## Feedback

What did the sheets help you notice? Which decision changed? Where did you need more space or a clearer prompt? Share feedback through the [project website](https://dorienherremans.com/aiSTROM), removing confidential information.

## Reference

Herremans, D. (2021). **aiSTROM–A Roadmap for Developing a Successful AI Strategy.** *IEEE Access*, 9, 155826–155838. [Published paper](https://doi.org/10.1109/ACCESS.2021.3127548) · [Open author version](https://arxiv.org/abs/2107.06071).

**Dorien Herremans · Version 1.0 · Created September 2026**

## Reuse

Toolkit materials use the repository's [MIT licence](https://github.com/dorienh/aiSTROM/blob/main/LICENSE). Include the licence notice with redistributed copies. The original roadmap image is separately attributed under CC BY 4.0; see [asset credits](https://github.com/dorienh/aiSTROM/blob/main/assets/README.md).

The PDFs and instructor materials are ready to use. Download the toolkit, fill in the sheets and adapt the session to your project or class.

