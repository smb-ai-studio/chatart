# ChatArt Pro Learn content guidelines

These guidelines define how to maintain the ChatArt Pro Learn repository and GitHub Pages content.

## Positioning

`learn.chatartpro.com` is the AI knowledge, tutorial, and practical skills content site for creators, marketers, and everyday AI users.

The Learn site should help users understand AI models, prompts, creative techniques, AI video/image workflows, content-production methods, and practical usage tips. It should not compete directly with the main `www.chatartpro.com` official website for the strongest product-brand positioning terms.

Primary Learn positioning:

- AI knowledge hub
- AI tutorials and practical guides
- AI prompt tips
- AI video and image creation tutorials
- model explanation articles
- creative AI techniques
- practical AI learning resources

Avoid making Learn pages primarily target or over-repeat:

- ChatArt Pro AI asset production workspace
- ChatArt Pro AI asset workflow
- ChatArt Pro model guide
- ChatArt Pro product workflow
- ChatArt Pro + AI asset / workflow / model guide brand phrases

Use ChatArt Pro as a light contextual CTA, not the dominant SEO topic of Learn pages.

When mentioning ChatArt Pro:

- Keep it as a helpful next step or optional tool mention.
- Prefer neutral CTA phrasing such as "Try the workflow in ChatArt Pro" or "Practice this prompt in ChatArt Pro."
- Avoid making the page title, H1, meta description, or opening paragraph primarily about ChatArt Pro unless the page is intentionally a product/support page.
- Do not position Learn as the official product homepage; that role belongs to `www.chatartpro.com`.

Header brand display:

- Use `ChatArt Learn` beside the logo in the site header so the Learn site is visually distinct from the main ChatArt Pro product site.
- Keep `ChatArt Pro` for the app CTA and product-specific mentions.

Legacy product-oriented wording may still appear where useful, but new and revised content should shift toward AI learning intent.

Preferred Learn wording:

- AI tutorial
- AI guide
- prompt examples
- practical AI workflow
- AI video tutorial
- AI image prompt guide
- model capability explanation
- creator tips
- marketing AI tips
- hands-on AI practice

Avoid positioning Learn as only a model directory, a generic AI tool list, or a product sales site. Model pages and comparison pages should help readers learn how to choose and use models, with ChatArt Pro appearing as the optional place to practice.

## Public content structure

Keep these public entry points current:

- README.md - concise product overview for GitHub visitors.
- index.html - primary Learn landing page for AI knowledge, tutorials, and practical guides.
- capabilities.html - AI capabilities and model learning directory.
- use-cases.html - AI usage scenarios and tutorial paths with a clear CTA.
- articles.html - article hub for AI tutorials, model explainers, prompt examples, and practical tips.
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
- One meta description aligned with AI knowledge, tutorial, model explanation, or prompt-tip intent.
- One canonical URL.
- A robots meta tag that allows indexing and rich snippets.
- A link to llms.txt.
- A link to sitemap.xml.
- The GA4 Google tag for G-VS171ECBSC.
- One H1.
- Valid JSON-LD where useful.
- A freshness/source note when claims can change.
- Internal links to related capability, model, comparison, FAQ, or policy pages.

## Google Search quality baseline

Follow Google's public Search documentation when creating, editing, or auditing pages. The default standard is helpful, reliable, people-first content.

Every public page should:

- Satisfy a real AI learning, creation, or practical usage task, not only target a keyword.
- Make the main topic and user benefit clear near the top of the page.
- Provide original value: practical workflow, decision help, prompt examples, tradeoffs, limitations, or hands-on usage guidance.
- Avoid thin summaries of external articles. When using external material, synthesize it into a ChatArt Pro workflow and cite the source.
- Avoid exaggerated claims, unsupported superlatives, fake certainty, or implying model/product access that is not confirmed.
- Identify freshness-sensitive claims with a review date and source note.
- Use clear headings that match the content below them.
- Link naturally to related internal pages when those pages help the reader continue learning or practicing the task.
- Keep the page usable on mobile and avoid layout issues such as horizontal overflow.
- Avoid keyword stuffing, doorway-style pages, mass-produced generic copy, or content written only for search ranking.
- If AI assistance is used to draft content, the final page still needs human-useful structure, source review, factual checks, and project-specific editing.

For model and AI capability pages specifically:

- Explain what the model can help a reader understand, create, compare, or practice.
- Separate public model claims from ChatArt Pro product availability.
- Include practical prompts, use cases, limits to verify, and a light CTA to practice in ChatArt Pro when relevant.
- Prefer official model documentation and high-quality guide pages as sources; cite them in the source note.

## Google SEO starter guide baseline

Follow Google's SEO Starter Guide as an operational checklist for public pages. The priority is to help users and search engines understand the page, not to chase shortcuts.

Use these rules when creating, editing, or auditing pages:

- Keep pages crawlable as normal HTML with the same important content visible to users and Google. Do not hide essential content behind inaccessible scripts, images, or blocked resources.
- Use descriptive, stable URLs and keep related topics grouped in logical folders such as `articles/`, `models/`, and `compare/`.
- Avoid duplicate pages. Each page should have one clear purpose and a canonical URL; do not create near-identical pages for keyword variants.
- Write unique, specific `<title>` and meta description text for each page. The title should describe the page; the meta description should summarize why a creator or marketer should click.
- Use headings to organize content for scanning. H1 should match the main task; H2 sections should answer real reader questions.
- Write helpful link text. Avoid vague anchors like "click here"; use anchors that explain the destination, such as "Read the Seedance 2 model guide" or "Compare GPT Image 2 and Nano Banana".
- Link to related internal pages when the link helps the reader continue the task. Link to trusted external sources when they support factual or freshness-sensitive claims.
- Put images near relevant explanatory text, use clear images, and write descriptive `alt` text when the image adds meaning. Decorative images can use empty alt text.
- For video-focused pages, include a dedicated page context, descriptive title/description, nearby explanatory text, and structured data where useful.
- Think about both expert and beginner search language, but do not try to include every possible query. Use natural language and avoid keyword stuffing.
- Do not rely on meta keywords; Google does not use them for ranking.
- Avoid intrusive elements that block users from reading the main content.
- Promote new pages through relevant internal links, the article hub, sitemap.xml, llms.txt, and any appropriate public entry point.
- Use Search Console URL Inspection and performance data after publishing when diagnosing indexing, crawling, or search appearance issues.

## Model page requirements

Each model page should explain:

- What the model is, what it is good at, and what readers can learn or practice with it.
- When creators, marketers, or general AI users should consider it.
- Practical capability notes.
- Prompt starters and usage examples.
- Limits to check before final delivery.
- Source and freshness notes, including relevant external source links when available.

## Comparison page requirements

Each comparison page should answer:

- Which model to choose for which practical learning or creation task.
- Speed vs. control tradeoffs.
- Exploration vs. polish tradeoffs.
- A practical test prompt.
- Where to learn or practice next.

## Article page requirements

Each article should include:

- A practical AI learning, prompt, model, image, video, creator, or marketing problem.
- Who the workflow is for.
- What the reader can understand, create, compare, or improve.
- A recommended workflow.
- Prompt examples when useful.
- Model or capability recommendations.
- A natural, light ChatArt Pro CTA when useful, without making the article primarily a product page.
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
- [ ] Page passes the Google Search quality baseline: helpful task focus, original value, clear source/freshness note, no unsupported claims, no keyword stuffing.
- [ ] Page passes the Google SEO starter guide baseline: descriptive title/meta, logical URL, useful link text, visible crawlable content, image alt/context, no duplicate/near-duplicate page intent.
- [ ] Page copy follows the Learn positioning: AI knowledge, tutorials, prompt tips, and model explanations first; ChatArt Pro appears as a light practice CTA, not the dominant SEO topic.
- [ ] CTA links point to the official product or a relevant internal next step.
