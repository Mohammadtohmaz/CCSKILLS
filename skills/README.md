# Claude Code Skills

This folder contains installed Claude Code skills that extend Claude's capabilities with specialized knowledge and workflows.

## Installed Skills

| Skill | Description | Source |
|-------|-------------|--------|
| [frontend-design](#frontend-design) | Create distinctive, production-grade frontend interfaces | [Anthropic](https://github.com/anthropics/claude-code) |
| [content-research-writer](#content-research-writer) | Research and write high-quality content with citations | [ComposioHQ](https://github.com/ComposioHQ/awesome-claude-skills) |
| [lead-research-assistant](#lead-research-assistant) | Find and qualify potential leads for your business | [ComposioHQ](https://github.com/ComposioHQ/awesome-claude-skills) |
| [skill-creator](#skill-creator) | Create new Claude Code skills | [ComposioHQ](https://github.com/ComposioHQ/awesome-claude-skills) |
| [domain-name-brainstormer](#domain-name-brainstormer) | Generate creative domain names and check availability | [ComposioHQ](https://github.com/ComposioHQ/awesome-claude-skills) |
| [stripe-integration](#stripe-integration) | Implement PCI-compliant Stripe payment processing | [wshobson](https://github.com/wshobson/agents) |
| [product-scout](#product-scout) | Scout and analyze successful products for cloning opportunities | Custom |
| [brand-namer](#brand-namer) | Generate creative brand names using proven naming techniques | Custom |

---

## Skill Details

### frontend-design

Create distinctive, production-grade frontend interfaces with high design quality. Avoids generic "AI slop" aesthetics by focusing on bold typography, cohesive color themes, and meaningful animations.

**Use when:** Building web components, pages, or applications that need to stand out visually.

**Example:**
```
Use the frontend design skill. Create a music player app with a retro-futuristic aesthetic.
```

---

### content-research-writer

Your writing partner for creating well-researched content with proper citations. Helps with outlining, research, improving hooks, and section-by-section feedback while preserving your unique voice.

**Use when:** Writing blog posts, articles, newsletters, case studies, or technical documentation.

**Example:**
```
Help me create an outline for an article about continuous discovery. I want to target product managers.
```

---

### lead-research-assistant

Identifies high-quality leads by analyzing your business, understanding your ideal customer profile, and providing actionable outreach strategies with personalized messaging.

**Use when:** Finding potential customers, building prospect lists, or preparing for sales outreach.

**Example:**
```
I'm building a tool that masks sensitive data in AI coding queries. Find me 10 companies in fintech that would be good leads.
```

---

### skill-creator

Guide for creating effective Claude Code skills. Helps you design, structure, and package skills with proper SKILL.md files and bundled resources.

**Use when:** Creating a new skill or updating an existing skill to extend Claude's capabilities.

**Example:**
```
Help me create a skill for generating database migrations based on schema changes.
```

---

### domain-name-brainstormer

Generates creative domain name ideas for your project and checks availability across multiple TLDs (.com, .io, .dev, .ai, etc.).

**Use when:** Starting a new project, launching a product, or rebranding and need an available domain.

**Example:**
```
I'm building a project management tool for remote teams. Suggest domain names with .com and .io options.
```

---

### stripe-integration

Implement Stripe payment processing for robust, PCI-compliant payment flows including checkout sessions, subscriptions, webhooks, and refunds.

**Use when:** Integrating Stripe payments, building subscription systems, or implementing secure checkout flows.

**Example:**
```
Help me set up a Stripe checkout session for a monthly subscription at $20/month.
```

---

### product-scout

Systematically find and analyze successful products in any industry to identify opportunities for cloning or rebranding. Produces comprehensive reports with business model breakdowns, feature analysis, competitive landscape, and clone viability scores.

**Use when:** Researching competitors, evaluating market opportunities, or analyzing products to potentially clone for different markets.

**Example:**
```
Scout successful fintech products in the "buy now pay later" space. I'm looking for products to clone for the Middle East market.
```

---

### brand-namer

Generate creative, brandable names using 6 proven naming techniques: portmanteaus, phonetic respelling, tech prefixes/suffixes, industry terms + twist, and gaming/casual slang. Provides 15-20 options with pronunciation guides, domain patterns, and rationale.

**Use when:** Naming a new startup, product, app, or rebranding venture.

**Example:**
```
Generate brand names for a forex trading education platform targeting beginners. Tone should be friendly but credible.
```

---

## Installation

Skills are automatically loaded when Claude Code detects a matching use case based on the skill's description.

To manually reference a skill, you can say:
```
Use the [skill-name] skill to [task description]
```

## Adding More Skills

Browse available skills at:
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- [SkillsMP Marketplace](https://skillsmp.com)
- [Anthropic Claude Code Plugins](https://github.com/anthropics/claude-code/tree/main/plugins)
