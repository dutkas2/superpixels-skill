# Superpixels — Claude Code Skill

A Claude Code skill for designing and building remarkable, memorable micro-interactions and design elements. Based on Glen Allsopp's [Superpixels framework](https://detailed.com/superpixels/).

## What are Superpixels?

Small, intentional design choices that are so specific and thoughtful that visitors feel the craft behind them. A Superpixel makes someone pause and think "that's clever" — the kind of detail someone would screenshot and send to a friend.

**The test:** Would someone screenshot this? Would a designer bookmark it? Would a competitor copy it?

## Install

```bash
claude install dutkas2/superpixels-skill
```

Or manually:

```bash
git clone https://github.com/dutkas2/superpixels-skill.git ~/.claude/skills/superpixels
```

## Usage

In Claude Code, use `/superpixels` or ask to "add a superpixel" to any section.

The skill will:
1. Audit the page for common missed opportunities (unclickable headlines, missing hover states, generic copy)
2. Propose 3-5 targeted Superpixel ideas drawn from 9 categories with 100+ real-world examples
3. Build the ones you pick with accessibility, performance, and progressive enhancement
4. Verify at mobile and desktop viewports

## 9 Categories

| # | Category | What it means |
|---|----------|--------------|
| 1 | **Adaptive Content** | Elements that change based on context, location, scroll position, or time |
| 2 | **Trust Amplifiers** | Social proof in unexpected places — review process transparency, research effort, brutal honesty |
| 3 | **Interactive Reveals** | Hover/click states that surprise — photo-to-video crossfade, escalating animations, progress-bar cycling |
| 4 | **Personal Touches** | Details showing humans behind the brand — founder messages, live counters, recognizable avatar embeds |
| 5 | **Smart Navigation** | Navigation that adapts per page type, embeds conversion elements, or uses niche-themed scroll-to-top |
| 6 | **SuperHooks** | Copy that reads the visitor's mind — asterisk amplification, pain-point flips, skip-the-ad reversals |
| 7 | **Micro-Copy Personality** | Words in unexpected places — personality opt-ins, humorous footer links, theme name Easter eggs |
| 8 | **Visual Craft** | Pixel-level details — brand-matched gradients, internal vs external link styling, rating overlays on product images |
| 9 | **Branded Content Areas** | Give your blog/content section its own name, logo, and visual identity |

Plus: a **Missed Opportunities audit** (12 common design/usability mistakes) and **site-type-specific guidance** with prioritized patterns for:

- **Local Service Businesses** — plumbers, dentists, lawyers, HVAC (urgency + trust)
- **eCommerce** — DTC brands, Shopify stores (comparison shopping + purchase confidence)
- **SaaS & Software** — web apps, B2B platforms (evaluation + onboarding)
- **Affiliate & Review Sites** — product reviews, comparison sites (skepticism + methodology)
- **News & Media** — publications, content-first sites (credibility + reading experience)
- **Portfolio & Personal Brand** — freelancers, agencies, creators (personality + proof)

## Framework-Agnostic

Works with any frontend stack — React, Next.js, Astro, Vue, Svelte, or plain HTML/CSS. Adapts to whatever framework and design system your project uses.

## Credits

Based on the Superpixels framework by [Glen Allsopp](https://detailed.com) from [SEO Blueprint](https://seoblueprint.com). All examples and patterns are sourced from the Superpixels course material.

## License

MIT
