# Marketing Skills for AI Agents

# Marketing Skills for AI Coding Agents

A curated collection of specialized marketing skills designed to extend the capabilities of AI coding agents. This framework provides structured workflows, domain-specific knowledge, and proven marketing methodologies that enable agents to perform marketing-related tasks with greater accuracy, consistency, and context awareness.

Built for founders, growth teams, product marketers, and technical professionals, these skills help AI agents support a wide range of marketing functions, including conversion rate optimization (CRO), SEO, copywriting, analytics, customer research, growth experimentation, and go-to-market strategy.

Rather than replacing marketing expertise, these skills act as a knowledge and workflow layer that guides AI agents through industry-standard processes, best practices, and decision-making frameworks.

## Key Features

* 40+ specialized marketing skill modules
* Structured workflows for repeatable execution
* Cross-skill knowledge sharing and dependency mapping
* Support for SEO, CRO, analytics, content strategy, and growth marketing
* Compatible with Claude Code, OpenAI Codex, Cursor, Windsurf, GitHub Copilot, and Agent Skills-compliant platforms
* Easily customizable for specific business, product, or marketing requirements

## Technical Highlights

* Modular skill-based architecture
* Context-aware workflow design
* Reusable prompt engineering patterns
* Agent interoperability through the Agent Skills specification
* Scalable framework for extending AI agent capabilities

This project demonstrates practical applications of prompt engineering, workflow design, AI-assisted marketing operations, and agent augmentation systems, showcasing how domain expertise can be embedded into AI-assisted development and business workflows.

## What are Skills?

Skills are markdown files that give AI agents specialized knowledge and workflows for specific tasks. When you add these to your project, your agent can recognize when you're working on a marketing task and apply the right frameworks and best practices.

## How Skills Work Together

Skills reference each other and build on shared context. The `product-marketing` skill is the foundation — every other skill checks it first to understand your product, audience, and positioning before doing anything.

┌──────────────────────────────────────────────────────────────┐
│                    PRODUCT MARKETING                         │
│                                                              │
│ Shared Context Layer                                         │
│ • Product Information                                        │
│ • Target Audience                                            │
│ • Positioning & Messaging                                    │
│ • Market & Competitor Context                                │
└───────────────────────┬──────────────────────────────────────┘
│
▼

┌────────────┬────────────┬────────────┬────────────┐
│    SEO     │    CRO     │  CONTENT   │ ANALYTICS  │
│ & DISCOVER │ & CONVERS. │ & COPY     │ & TESTING  │
└─────┬──────┴─────┬──────┴─────┬──────┴─────┬──────┘
│            │            │            │
▼            ▼            ▼            ▼

┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐
│seo-audit│   │   cro   │   │copywrite│   │analytics│
│ ai-seo  │   │ signup  │   │ emails  │   │ab-test  │
│ schema  │   │onboard  │   │ social  │   │ads data │
│ prog-seo│   │popups   │   │ video   │   │tracking │
└─────────┘   └─────────┘   └─────────┘   └─────────┘

┌────────────┬────────────┬────────────┐
│   GROWTH   │ SALES/GTM  │ STRATEGY   │
│ & RETENTION│ & REVOPS   │ & RESEARCH │
└─────┬──────┴─────┬──────┴─────┬──────┘
│            │            │
▼            ▼            ▼

┌─────────┐   ┌─────────┐   ┌─────────┐
│referrals│   │ revops  │   │mktgidea │
│community│   │launch   │   │psychol. │
│free-tool│   │pricing  │   │customer │
│churn    │   │prospect │   │research │
└─────────┘   └─────────┘   └─────────┘

Knowledge Dependencies

copywriting ───────► cro ───────► ab-testing

seo-audit ─────────► schema ────► ai-seo

customer-research ─► copywriting
└► cro
└► competitors

revops ────────────► sales-enablement
└► cold-email


See each skill's **Related Skills** section for the full dependency map.

## Available Skills

<!-- SKILLS:START -->
| Skill | Description |
|-------|-------------|
| [ab-testing](skills/ab-testing/) | When the user wants to plan, design, or implement an A/B test or experiment, or build a growth experimentation program.... |
| [ad-creative](skills/ad-creative/) | When the user wants to generate, iterate, or scale ad creative — headlines, descriptions, primary text, or full ad... |
| [ads](skills/ads/) | When the user wants help with paid advertising campaigns on Google Ads, Meta (Facebook/Instagram), LinkedIn, Twitter/X,... |
| [ai-seo](skills/ai-seo/) | When the user wants to optimize content for AI search engines, get cited by LLMs, or appear in AI-generated answers.... |
| [analytics](skills/analytics/) | When the user wants to set up, improve, or audit analytics tracking and measurement. Also use when the user mentions... |
| [aso](skills/aso/) | When the user wants to audit or optimize an App Store or Google Play listing. Also use when the user mentions 'ASO... |
| [churn-prevention](skills/churn-prevention/) | When the user wants to reduce churn, build cancellation flows, set up save offers, recover failed payments, or... |
| [co-marketing](skills/co-marketing/) | When the user wants to find co-marketing partners, plan joint campaigns, or brainstorm partnership opportunities. Use... |
| [cold-email](skills/cold-email/) | Write B2B cold emails and follow-up sequences that get replies. Use when the user wants to write cold outreach emails,... |
| [community-marketing](skills/community-marketing/) | Build and leverage online communities to drive product growth and brand loyalty. Use when the user wants to create a... |
| [competitor-profiling](skills/competitor-profiling/) | When the user wants to research, profile, or analyze competitors from their URLs. Also use when the user mentions... |
| [competitors](skills/competitors/) | When the user wants to create competitor comparison or alternative pages for SEO and sales enablement. Also use when... |
| [content-strategy](skills/content-strategy/) | When the user wants to plan a content strategy, decide what content to create, or figure out what topics to cover. Also... |
| [copy-editing](skills/copy-editing/) | When the user wants to edit, review, or improve existing marketing copy, or refresh outdated content. Also use when the... |
| [copywriting](skills/copywriting/) | When the user wants to write, rewrite, or improve marketing copy for any page — including homepage, landing pages,... |
| [cro](skills/cro/) | When the user wants to optimize, improve, or increase conversions on any marketing page or form — including homepage,... |
| [customer-research](skills/customer-research/) | When the user wants to conduct, analyze, or synthesize customer research. Use when the user mentions "customer... |
| [directory-submissions](skills/directory-submissions/) | When the user wants to submit their product to startup, SaaS, AI, agent, MCP, no-code, or review directories for... |
| [emails](skills/emails/) | When the user wants to create or optimize an email sequence, drip campaign, automated email flow, or lifecycle email... |
| [free-tools](skills/free-tools/) | When the user wants to plan, evaluate, or build a free tool for marketing purposes — lead generation, SEO value, or... |
| [image](skills/image/) | When the user wants to create, generate, edit, or optimize images for marketing — blog heroes, social graphics, product... |
| [launch](skills/launch/) | When the user wants to plan a product launch, feature announcement, or release strategy. Also use when the user... |
| [lead-magnets](skills/lead-magnets/) | When the user wants to create, plan, or optimize a lead magnet for email capture or lead generation. Also use when the... |
| [marketing-ideas](skills/marketing-ideas/) | When the user needs marketing ideas, inspiration, or strategies for their SaaS or software product. Also use when the... |
| [marketing-plan](skills/marketing-plan/) | When the user needs a comprehensive marketing plan for a client, a company they advise, or their own product. Also use... |
| [marketing-psychology](skills/marketing-psychology/) | When the user wants to apply psychological principles, mental models, or behavioral science to marketing. Also use when... |
| [onboarding](skills/onboarding/) | When the user wants to optimize post-signup onboarding, user activation, first-run experience, or time-to-value. Also... |
| [paywalls](skills/paywalls/) | When the user wants to create or optimize in-app paywalls, upgrade screens, upsell modals, or feature gates. Also use... |
| [popups](skills/popups/) | When the user wants to create or optimize popups, modals, overlays, slide-ins, or banners for conversion purposes. Also... |
| [pricing](skills/pricing/) | When the user wants help with pricing decisions, packaging, or monetization strategy. Also use when the user mentions... |
| [product-marketing](skills/product-marketing/) | When the user wants to create or update their product marketing context document. Also use when the user mentions... |
| [programmatic-seo](skills/programmatic-seo/) | When the user wants to create SEO-driven pages at scale using templates and data. Also use when the user mentions... |
| [prospecting](skills/prospecting/) | When the user wants to find, qualify, and build a list of prospects to reach out to — across B2B SaaS, general B2B, or... |
| [referrals](skills/referrals/) | When the user wants to create, optimize, or analyze a referral program, affiliate program, or word-of-mouth strategy.... |
| [revops](skills/revops/) | When the user wants help with revenue operations, lead lifecycle management, or marketing-to-sales handoff processes.... |
| [sales-enablement](skills/sales-enablement/) | When the user wants to create sales collateral, pitch decks, one-pagers, objection handling docs, or demo scripts. Also... |
| [schema](skills/schema/) | When the user wants to add, fix, or optimize schema markup and structured data on their site. Also use when the user... |
| [seo-audit](skills/seo-audit/) | When the user wants to audit, review, or diagnose SEO issues on their site. Also use when the user mentions "SEO... |
| [signup](skills/signup/) | When the user wants to optimize signup, registration, account creation, or trial activation flows. Also use when the... |
| [site-architecture](skills/site-architecture/) | When the user wants to plan, map, or restructure their website's page hierarchy, navigation, URL structure, or internal... |
| [sms](skills/sms/) | When the user wants to plan, build, or optimize SMS or MMS marketing — including welcome flows, abandoned cart texts,... |
| [social](skills/social/) | When the user wants help creating, scheduling, or optimizing social media content for LinkedIn, Twitter/X, Instagram,... |
| [video](skills/video/) | When the user wants to create, generate, or produce video content using AI tools or programmatic frameworks. Also use... |
<!-- SKILLS:END -->
 Claude Code Plugin

Install via Claude Code's built-in plugin system:

```bash
# Add the marketplace
/plugin marketplace add coreyhaines31/marketingskills

# Install all marketing skills
/plugin install marketing-skills
```
