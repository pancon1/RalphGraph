# RalphGraph - Expert Graphic & Digital Products Agent

**Version:** 1.0.0  
**Language:** Français / English  
**License:** Apache 2.0

---

## 🎨 About / À Propos

**RalphGraph** is a comprehensive AI agent prompt designed for graphic design professionals and digital product creators. This agent acts as a senior art director combined with a specialized freelance designer for sellable digital products on marketplaces like Etsy, Creative Market, Gumroad, and print-on-demand platforms.

**RalphGraph** est un prompt d'agent IA complet conçu pour les professionnels du design graphique et les créateurs de produits numériques. Cet agent agit comme un directeur artistique senior combiné à un designer freelance spécialisé dans les produits numériques vendables sur des marketplaces comme Etsy, Creative Market, Gumroad et les plateformes d'impression à la demande.

---

## ✨ Key Features / Fonctionnalités Clés

### Core Competencies / Compétences Principales

- **Visual Identity** - Logos, color palettes, typography systems, brand guidelines
- **Digital Templates** - Instagram, Facebook, Pinterest, YouTube, TikTok templates
- **Professional Documents** - eBooks, presentations, planners, Notion templates
- **Print & POD** - Posters, apparel, stationery, mockups with technical specs
- **Marketplace Optimization** - SEO strategies for Etsy, Creative Market, Gumroad
- **Legal & Compliance** - Copyright, licensing, terms of service

### Méthodologie Structurée / Structured Methodology

1. **Clarification** - Targeted questions to understand needs (6 core questions)
2. **Creative Directions** - 2-4 distinct creative concepts with specifications
3. **Detailed Specifications** - Complete technical requirements and file organization
4. **Sales Optimization** - Titles, descriptions, tags, mockups, pricing strategies
5. **Legal Framework** - Licensing, copyright protection, compliance checks
6. **Iterative Refinement** - Continuous improvement and variations

---

## 📋 Table of Contents / Table des Matières

- [Installation & Setup](#installation--setup)
- [Usage / Utilisation](#usage--utilisation)
- [File Structure](#file-structure)
- [Examples](#examples)
- [Technical Specifications](#technical-specifications)
- [Marketplace Guidelines](#marketplace-guidelines)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

---

## 🚀 Installation & Setup

### Prerequisites / Prérequis

- Access to Claude, ChatGPT, or compatible AI platform with system prompts support
- Basic understanding of design tools (Canva, Photoshop, Illustrator, or Figma)
- Familiarity with marketplace platforms (Etsy, Creative Market, Gumroad)

### Quick Start / Démarrage Rapide

1. **Copy the main prompt** from `src/agent-prompt-en.txt` or `src/agent-prompt-fr.txt`
2. **Paste into your AI platform** (Claude Projects, ChatGPT Custom Instructions, etc.)
3. **Start by asking clarifying questions** about your product needs
4. **Follow the agent's methodology** through all 6 phases
5. **Export deliverables** (files, specifications, optimization copy)

### Alternative: Using JSON Configuration / Utilisation Configuration JSON

For API integrations, use `src/agent-config.json`:

```bash
# Python example
import json
with open('src/agent-config.json', 'r') as f:
    config = json.load(f)
# Pass config to your AI API
```

---

## 💡 Usage / Utilisation

### Scenario 1: Instagram Template Pack / Pack de Templates Instagram

**User Request:**
> "I want to create 15 Instagram templates for eco-friendly brands selling on Etsy."

**Agent Process:**
1. Asks 6 clarifying questions (platform, audience, style, tools, formats, constraints)
2. Proposes 3-4 creative directions (Minimalist, Organic, Vibrant, etc.)
3. Develops detailed specifications (colors, typography, layouts)
4. Provides complete technical specs (1080×1350px, PNG/JPG/Canva formats)
5. Generates SEO-optimized titles, descriptions, and tags for Etsy
6. Suggests 4-5 mockup variations for product presentation

### Scenario 2: Print-on-Demand Poster Series / Série d'Affiches POD

**Demande Utilisateur:**
> "Je veux créer une série de 5 affiches minimalistes pour Redbubble et ma boutique Shopify."

**Processus Agent:**
1. Pose 6 questions (format d'affiches, audience, style, DPI, fonds perdus)
2. Propose 3-4 directions créatives
3. Spécifie dimensions exactes (300 DPI, CMYK, 3mm bleed)
4. Génère fichiers imprimables et mockups lifestyle
5. Optimise descriptions + tags pour chaque plateforme
6. Fournit structure de fichiers professionnelle

### Scenario 3: Complete Brand Identity System / Système d'Identité Visuelle Complet

**User Request:**
> "Design a complete brand system for a sustainable cosmetics startup to sell templates on Creative Market."

**Agent Output:**
- Logo variations (main, icon, monochrome, with/without tagline)
- Color palette with psychology explanation (6 colors + hex codes)
- Typography hierarchy (headings, body text, emphasis)
- Component library (buttons, badges, dividers)
- 10+ template variations using the system
- Complete Creative Market application package
- Staff Picks optimization strategy

---

## 📁 File Structure

```
RalphGraph/
│
├── README.md (this file / ce fichier)
├── LICENSE (Apache 2.0)
├── CHANGELOG.md (version history / historique des versions)
├── CONTRIBUTING.md (contribution guidelines)
├── .gitignore
│
├── src/
│   ├── agent-prompt-en.txt (Complete English prompt - 15,000 words)
│   ├── agent-prompt-fr.txt (Complete French prompt - 15,000 words)
│   ├── agent-config.json (Structured config for API integration)
│   ├── agent-config.yaml (YAML version alternative)
│   ├── quick-start-guide-en.md
│   ├── quick-start-guide-fr.md
│   └── system-instructions-reference.md
│
├── examples/
│   ├── scenario-1-instagram-templates/
│   │   ├── example-user-request.txt
│   │   ├── agent-response-phase-1.md (Questions)
│   │   ├── agent-response-phase-2.md (Creative Directions)
│   │   ├── agent-response-phase-3.md (Detailed Specs)
│   │   ├── agent-response-phase-4.md (Technical Specs)
│   │   ├── agent-response-phase-5.md (Sales Copy)
│   │   └── deliverables-checklist.md
│   │
│   ├── scenario-2-pod-posters/
│   │   ├── example-user-request.txt
│   │   ├── agent-response-complete.md
│   │   ├── technical-specifications.pdf
│   │   └── file-structure-example.txt
│   │
│   ├── scenario-3-brand-identity/
│   │   ├── example-user-request.txt
│   │   ├── agent-response-complete.md
│   │   ├── brand-guidelines-template.md
│   │   └── creative-market-optimization.md
│   │
│   ├── scenario-4-canva-templates/
│   │   └── canva-briefing-document.md
│   │
│   └── scenario-5-ebook-templates/
│       └── ebook-design-specifications.md
│
├── templates/
│   ├── design-brief-template.md (for documenting requirements)
│   ├── technical-specs-template.md
│   ├── etsy-listing-template.md
│   ├── creative-market-template.md
│   ├── gumroad-description-template.md
│   ├── file-naming-convention.txt
│   ├── color-palette-template.md
│   ├── typography-system-template.md
│   └── mockup-checklist.md
│
├── resources/
│   ├── TECHNICAL-SPECS.md (Master reference for all dimensions)
│   ├── MARKETPLACE-GUIDE.md (Detailed marketplace optimization)
│   ├── LEGAL-COMPLIANCE.md (Licensing, copyright, terms)
│   ├── COLOR-THEORY.md (Color psychology & combinations)
│   ├── TYPOGRAPHY-GUIDE.md (Font pairings & hierarchies)
│   ├── SEO-KEYWORDS.md (10,000+ keywords organized by category)
│   ├── MOCKUP-RESOURCES.md (Best mockup tools & templates)
│   └── DESIGN-TOOLS-GUIDE.md (Tools comparison: Canva vs Photoshop vs Figma)
│
├── tools/
│   ├── prompt-formatter.py (Convert prompt format for different platforms)
│   ├── seo-keyword-generator.py (Generate tags for listings)
│   ├── file-organizer.py (Auto-organize exported files)
│   ├── specification-calculator.py (Calculate dimensions for different formats)
│   └── README-tools.md
│
└── docs/
    ├── API-INTEGRATION.md (How to integrate via API)
    ├── CUSTOM-MODIFICATIONS.md (How to customize the agent)
    ├── BEST-PRACTICES.md (Proven strategies for results)
    ├── TROUBLESHOOTING.md (Common issues & solutions)
    ├── GLOSSARY.md (Design & marketplace terminology)
    └── FAQ.md (Frequently asked questions)
```

---

## 📚 Examples / Exemples

### Example 1: Instagram Template Pack Request / Demande Pack Templates Instagram

**Project:** 15 Instagram templates for sustainable fashion brands
**Timeline:** 1 week
**Platform:** Etsy
**Budget:** $0-100 design investment expected

**Full example walkthrough:** See `examples/scenario-1-instagram-templates/`

### Example 2: Print-on-Demand Poster Series / Série d'Affiches Impression à la Demande

**Project:** 5-poster minimalist series for Redbubble
**Timeline:** 3 days
**Target Market:** Design enthusiasts, office decoration
**Files Needed:** 300 DPI CMYK, 3mm bleed, Mockups

**Full example walkthrough:** See `examples/scenario-2-pod-posters/`

### Example 3: Complete Brand System / Système de Marque Complet

**Project:** Brand identity system for creative agency
**Timeline:** 2 weeks
**Deliverables:** Logo suite, style guide, 20 templates, Creative Market package

**Full example walkthrough:** See `examples/scenario-3-brand-identity/`

---

## 🔧 Technical Specifications / Spécifications Techniques

### Social Media Dimensions / Dimensions Réseaux Sociaux

| Platform | Format | Dimensions | DPI | Ratio |
|----------|--------|------------|-----|-------|
| Instagram Post | Digital | 1080 × 1350px | 72 | 4:5 |
| Instagram Story | Digital | 1080 × 1920px | 72 | 9:16 |
| Instagram Reels | Digital | 1080 × 1920px | 72 | 9:16 |
| Facebook Post | Digital | 1200 × 627px | 72 | 1.91:1 |
| Pinterest Pin | Digital | 1000 × 1500px | 72 | 2:3 |
| YouTube Thumbnail | Digital | 1280 × 720px | 72 | 16:9 |
| TikTok Video | Digital | 1080 × 1920px | 72 | 9:16 |

### Print Specifications / Spécifications Impression

| Item | Resolution | Color Space | Bleed | Margins | Format |
|------|-----------|-------------|-------|---------|--------|
| Standard Print | 300 DPI | CMYK | 3mm (0.125") | 6mm (0.25") | PDF |
| Large Format | 150-300 DPI | CMYK | 3mm | 6mm | PDF |
| Print-on-Demand | 300 DPI | CMYK | Per provider | Per provider | PNG/JPG |
| Digital PDF | 72 DPI | RGB | None | 12mm | PDF |

### File Formats / Formats de Fichiers

- **Raster:** PNG (transparency), JPG (photos), PDF
- **Vector:** SVG, AI, EPS
- **Editable:** PSD, XD, Figma file links, Canva links
- **Archive:** ZIP (organized folder structure)

---

## 🛍️ Marketplace Guidelines / Directives Marketplace

### Etsy Optimization

- **Title Format:** [Primary Keyword] – [Benefit] – [Product Type] – [Style] – [Use Case]
- **Tags:** 13 maximum, 3+ words per tag when possible, long-tail keywords
- **Description:** Lead with problem/solution, include specs, end with benefits
- **Mockups:** 3-6 high-quality images showing product in context

### Creative Market Submission

- **Application:** 10-20 professional quality pieces required
- **Commission:** 60% to seller (40% platform fee)
- **Licensing:** Non-exclusive with personal + commercial options
- **Staff Picks:** High-quality + complete listing + 3-4 effective mockups

### Gumroad Strategy

- **Fee Structure:** 10% flat per sale
- **Setup:** Quick storefront creation
- **Flexibility:** Price-fixed, pay-what-you-want, subscriptions available

---

## 🤝 Contributing / Contribuer

We welcome contributions from the community! / Nous accueillons les contributions de la communauté !

### How to Contribute / Comment Contribuer

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/improvement-name`)
3. **Make your changes** with clear, descriptive commits
4. **Submit a Pull Request** with a detailed description
5. **Wait for review** and address feedback

### Contribution Ideas / Idées de Contribution

- New design examples and scenarios
- Marketplace optimization strategies
- Updated technical specifications
- Tool improvements (Python scripts)
- Translations to other languages
- Additional template examples
- Design system improvements
- Documentation enhancements

See `CONTRIBUTING.md` for detailed guidelines / Voir `CONTRIBUTING.md` pour les directives détaillées

---

## ⚖️ License / Licence

**RalphGraph** is released under the **Apache License 2.0**, which provides:

✅ Commercial use permitted  
✅ Modification allowed  
✅ Distribution allowed  
✅ Patent rights provided  
⚠️ Must include copyright notice  
⚠️ Must state significant changes  
⚠️ Same license applies to derivatives  

**Why Apache 2.0?** Because it balances openness with patent protection, making it ideal for professional design tools that may be modified and commercialized.

For full license text, see `LICENSE` file.

---

## 📞 Support / Support

### Getting Help / Obtenir de l'Aide

- **Issues:** Report bugs or suggest improvements via GitHub Issues
- **Discussions:** Join community discussions for questions and ideas
- **Documentation:** Check `docs/` folder for comprehensive guides
- **FAQ:** See `docs/FAQ.md` for common questions

### Community / Communauté

- **Discussions Forum:** GitHub Discussions (coming soon)
- **Email:** Contact through repository owner
- **Twitter:** Follow for updates and tips

### Feedback / Retours

Your feedback is valuable! Share your experience:
- ⭐ Star the repository if you find it useful
- 💬 Leave comments on issues you're interested in
- 🔧 Contribute improvements and examples
- 📣 Share how you're using RalphGraph

---

## 🗺️ Roadmap / Feuille de Route

### Version 1.0.0 (Current / Actuelle)
- ✅ Complete prompt documentation
- ✅ Marketplace optimization guides
- ✅ Technical specifications reference
- ✅ Example scenarios
- ✅ Template files

### Version 1.1.0 (Planned / Planifié)
- 🔄 Web interface for prompt formatting
- 🔄 Video tutorials for each scenario
- 🔄 Integration examples (Python, Node.js)
- 🔄 Community examples gallery

### Version 1.2.0 (Future / Futur)
- 🔄 AI-powered template generator
- 🔄 Automated SEO keyword suggestions
- 🔄 Design system validator
- 🔄 Marketplace pricing calculator

---

## 📖 Additional Resources / Ressources Supplémentaires

- **GitHub:** [github.com/username/RalphGraph](https://github.com/username/RalphGraph)
- **Documentation:** See `docs/` folder
- **Templates:** Download from `templates/` folder
- **Examples:** Full walkthroughs in `examples/` folder
- **Tools:** Python utilities in `tools/` folder

---

## 👤 About the Creator / À Propos du Créateur

**RalphGraph** was created by **Ralph Randy Lekane Tsague**, a music industry manager and AI-assisted workflow specialist passionate about empowering creators with professional design tools and marketplace knowledge.

**RalphGraph** a été créé par **Ralph Randy Lekane Tsague**, gestionnaire de l'industrie musicale et spécialiste des flux de travail assistés par l'IA, passionné par l'autonomisation des créateurs avec des outils de conception professionnels et des connaissances en matière de marketplace.

---

## ❤️ Support This Project

If RalphGraph helps your creative business, please:
- ⭐ Star the repository
- 📤 Share with other creators
- 🐛 Report issues you find
- 💡 Suggest improvements
- 🤝 Contribute examples or documentation

---

**Last Updated:** November 2025  
**Version:** 1.0.0  
**Status:** Active Development

---

*RalphGraph - Empowering creators with AI-driven design excellence.*

*RalphGraph - Autonomiser les créateurs avec l'excellence du design piloté par l'IA.*
