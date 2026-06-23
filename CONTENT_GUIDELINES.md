# ChatArt Pro public content guidelines

These guidelines define how to maintain the ChatArt Pro public repository and GitHub Pages content.

## Positioning

ChatArt Pro should be described as an AI asset production workspace for creators and marketers.

Preferred wording:

- AI asset production workspace
- campaign-ready assets
- creator and marketing workflows
- video assets, image assets, music directions, copy assets
- social content packs, ad variants, product launch materials, campaign materials

Avoid positioning ChatArt Pro as only a model directory or a generic AI tool list. Model pages should support the asset-production story.

## Public content structure

Keep these public entry points current:

- README.md - concise product overview for GitHub visitors.
- index.html - primary public landing page.
- capabilities.html - asset production capabilities and model directory.
- use-cases.html - creator and marketing workflows with a clear CTA.
- articles.html - article hub for creator and marketing asset production playbooks.
- articles/ - individual topic articles with Article JSON-LD, breadcrumbs, CTA, source note, and related internal links.
- faq.html - short, plain answers.
- models/ - model-specific asset production guidance.
- compare/ - practical model-selection comparisons.
- editorial-policy.html - review scope and freshness notes.
- llms.txt - plain-text URL directory and product facts.
- robots.txt and sitemap.xml - crawler and discovery support.

## Page requirements

Every HTML page should include:

- One clear title.
- One meta description aligned with the creator/marketer asset-production positioning.
- One canonical URL.
- A robots meta tag that allows indexing and rich snippets.
- A link to llms.txt.
- A link to sitemap.xml.
- The GA4 Google tag for G-VS171ECBSC.
- One H1.
- Valid JSON-LD where useful.
- A freshness/source note when claims can change.
- Internal links to related capability, model, comparison, FAQ, or policy pages.

## Model page requirements

Each model page should explain:

- What asset job the model is best for.
- When creators or marketers should use it.
- Practical capability notes.
- Prompt starters for asset production.
- Limits to check before final delivery.
- Source and freshness notes, including relevant external source links when available.

## Comparison page requirements

Each comparison page should answer:

- Which model to choose for which asset job.
- Speed vs. control tradeoffs.
- Exploration vs. polish tradeoffs.
- A practical test prompt.
- Where to go next in ChatArt Pro.

## Article page requirements

Each article should include:

- A practical creator or marketing asset-production problem.
- Who the workflow is for.
- What assets the reader can create.
- A recommended workflow.
- Prompt examples when useful.
- Model or capability recommendations.
- A natural ChatArt Pro CTA.
- Article JSON-LD, BreadcrumbList JSON-LD, and a freshness/source note.

When adding an article, also update articles.html, sitemap.xml, llms.txt, and at least one relevant internal link from index.html, capabilities.html, use-cases.html, or another article.

## Repository hygiene

Keep the tracked repository focused on public product content:

- Keep public HTML, CSS, README, sitemap, robots, policy, and model/comparison pages.
- Do not commit local caches, generated scratch files, backups, or private research notes.
- Use neutral commit messages such as "Update product pages", "Improve use case copy", or "Add content guidelines".
- Avoid commit messages that describe private promotional strategy.

## Update checklist

Before publishing:

- [ ] HTML starts with <!doctype html>.
- [ ] No mojibake or replacement characters.
- [ ] Local links resolve.
- [ ] JSON-LD parses.
- [ ] sitemap.xml includes every public page.
- [ ] llms.txt reflects the current public page set.
- [ ] GA4 tag G-VS171ECBSC is present on every public HTML page.
- [ ] Page copy consistently frames ChatArt Pro as asset production for creators and marketers.
- [ ] CTA links point to the official product or a relevant internal next step.
