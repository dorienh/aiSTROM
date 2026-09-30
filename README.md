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

1. **[Visual toolkit](https://raw.githubusercontent.com/dorienh/aiSTROM/main/starter-kit/aiSTROM-visual-toolkit.pdf)** — an overview plus fourteen fillable detail pages covering seven dimensions.
2. **[Completed expense-claims strategy example](https://raw.githubusercontent.com/dorienh/aiSTROM/main/starter-kit/examples/expense-claims-visual-toolkit.pdf)** — all fifteen pages assess whether and how a fictional company could improve employee expense claims.
3. **[Instructor guide](https://raw.githubusercontent.com/dorienh/aiSTROM/main/instructor-kit/aiSTROM-instructor-guide.pdf)** — a workshop plan, exercises and facilitation prompts.

The PDF links bypass GitHub's preview. Save them and open the fillable sheets in a form-capable reader. For a one-page discussion, use page 1 of the visual toolkit.

## See how it works

### Bring the decisions together

![aiSTROM overview canvas with opportunity, seven strategy dimensions and the next decision.](https://raw.githubusercontent.com/dorienh/aiSTROM/main/assets/worksheet-overview.png)

*The overview gives the team a shared view of the opportunity and the decisions that need to fit together. [Open the fillable toolkit](https://raw.githubusercontent.com/dorienh/aiSTROM/main/starter-kit/aiSTROM-visual-toolkit.pdf).*

### Go beneath each headline

![Completed first Data page showing sources, acquisition and quality decisions for a fictional expense-claims opportunity.](https://raw.githubusercontent.com/dorienh/aiSTROM/main/assets/worksheet-data-example.png)

*The six Data cards span two pages. They compare options, assets, gaps and evidence. This completed example is a fictional strategic assessment, not a deployment or product comparison.*

### Compare risk responses

![Completed risk sheet showing safeguards and reversibility next to exposure and consequences.](https://raw.githubusercontent.com/dorienh/aiSTROM/main/assets/worksheet-risk-example.png)

*On risk cards, the positive field records safeguards or the benefit at stake; the negative field records exposure and consequences. The decision is whether the remaining risk is acceptable for the value sought.*

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

The original paper supplies the seven dimensions and many of their underlying topics. The six cards across each dimension's two pages are practical groupings, not a claim that the paper used these exact headings. Cards identify their source section or mark an added prompt. Conditional prompts at the bottom address particular system types without making every project an agent project.

## Fill in a card

Each dimension has six cards across two pages. The larger format gives three cards per page. For each question, record:

1. **Options or possible responses:** label them A, B, C so you can refer to them in the next fields.
2. **Strengths and constraints:** identify the assets and gaps for each option. The labels adapt to the dimension. On risk cards, examine *safeguards and reversibility* alongside *exposure and consequences*. The benefits and SWOT cards use their own labels.
3. **What is needed:** state prerequisites, missing evidence and links to other dimensions.
4. **Direction and reason:** record an emerging choice, or explain why it remains open.
5. **Next action:** name the evidence, owner and date. Set a decision state: `Open`, `Gathering evidence`, `Direction agreed`, `Deferred` or `N/A`.

For example, on **Data → Collect, acquire or label**, a company improving employee expense claims might compare A: labelling historical receipts, B: collecting corrections during normal review, and C: licensing external data. Finance reviewers know the relevant fields, but old labels may be sparse and external data may not match company policy. The company needs to estimate label volume, expert time, reuse rights and privacy requirements. It may choose to capture corrections now while leaving the training decision open.

The state describes the *decision process*, not whether a capability is ready or a project is approved. The signs are discussion aids, not a numerical score. Product reviews and trials come after a strategic direction and its criteria are set.

## Follow a complete example

The completed expense-claims example has the same fifteen-page layout as the blank toolkit. Its 42 cards examine whether and how a fictional 1,200-person company should invest in AI-assisted expense claims. It compares process improvement, current software, SaaS, internal adaptation and partnership. The overview gives a conditional direction: start with reversible receipt extraction and staff confirmation, subject to data, value and ownership evidence. No product, provider or trial is selected.

This is a **fictional teaching scenario**. It illustrates strategic reasoning; it does not claim measured performance or deployment. Many cards remain in `Gathering evidence` even though they are fully written, because the company still has work to do before implementation.

## Suggested working session

1. **Frame the opportunity.** Name the problem, affected people, desired outcome, scope and simpler alternatives in the overview's first box.
2. **Scan the seven dimensions.** Bring together business, domain and technical perspectives. Start with the sheets that could most change your decision.
3. **Compare upsides and downsides.** Ask what each route could enable, what it would cost or constrain, and which evidence is missing. Use short entries and link existing records rather than writing essays.
4. **Connect the dimensions.** A choice to fine-tune affects data, skills, hosting and costs. A new workflow affects roles, education and KPIs. Record dependencies at the bottom of each sheet.
5. **Return to the overview.** State whether to invest, prepare, defer or reject the opportunity. Name conditions, evidence, owner and review date for any later feasibility stage.

Use one set per opportunity. Compare multiple overview canvases when making portfolio decisions. Revisit affected sheets when goals, data, people, models, providers or operating conditions change.

## Using the files

All fifteen pages are interactive PDF forms, designed at **A3 landscape** for a workshop table or screen. Print at A3 for comfortable handwriting. A4 printing reduces both text and writing space.

Use a PDF reader that supports forms; save and reopen your copy to check that entries were retained. Keep entries concise and put longer evidence in linked project records. The overview is page 1 of the toolkit; print that page alone when you only need the summary.

## For instructors and facilitators

The [instructor guide](https://raw.githubusercontent.com/dorienh/aiSTROM/main/instructor-kit/aiSTROM-instructor-guide.pdf) includes a session plan, learning outcomes, discussion prompts, and predictive-AI and expense-claims exercises. Start with the visual sheets and use the guide to facilitate a class or workshop.

## Feedback

What did the sheets help you notice? Which decision changed? Where did you need more space or a clearer prompt? Share feedback through the [project website](https://dorienherremans.com/aiSTROM), removing confidential information.

## Reference

Herremans, D. (2021). **aiSTROM–A Roadmap for Developing a Successful AI Strategy.** *IEEE Access*, 9, 155826–155838. [Published paper](https://doi.org/10.1109/ACCESS.2021.3127548) · [Open author version](https://arxiv.org/abs/2107.06071).

**Dorien Herremans · Version 1.0 · Created September 2026**

## Reuse

Toolkit materials use the repository's [MIT licence](https://github.com/dorienh/aiSTROM/blob/main/LICENSE). Include the licence notice with redistributed copies. The original roadmap image is separately attributed under CC BY 4.0; see [asset credits](https://github.com/dorienh/aiSTROM/blob/main/assets/README.md).

The PDFs and instructor materials are ready to use. Download the toolkit, fill in the sheets and adapt the session to your project or class.

