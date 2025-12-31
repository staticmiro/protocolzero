# Contributing to Protocol Zero

Thank you for your interest in improving Protocol Zero! 

**Protocol Zero is a living document** - a comprehensive guide that evolves with technology and community input. Think of it as a community-maintained book, not a software project.

This is a community resource, and contributions of all kinds are welcome.

## 🎯 What You Can Contribute

- **Fix errors** - typos, broken links, outdated information
- **Improve clarity** - better explanations, restructured sections
- **Add examples** - real-world scenarios, case studies
- **Update tools** - new software recommendations, deprecated tool warnings
- **Expand coverage** - new topics, emerging threats
- **Translate** - make Protocol Zero available in other languages

## 📝 How to Contribute

### Small Changes (typos, minor fixes)

1. Open the relevant `.md` file
2. Make your changes
3. Submit with a clear description of what you fixed

### Larger Changes (new sections, major rewrites)

1. **First, discuss** - open an issue to discuss your proposed changes
2. **Get feedback** - ensure alignment with project goals
3. **Make changes** - follow style guide below
4. **Submit** - with detailed description and rationale

### New Translations

Translations are highly encouraged! 

**Structure:**
- Each language has its own folder: `protocol/[language-code]/` (e.g., `protocol/es/` for Spanish)
- English edition is in `protocol/en/` - use as reference
- Each language folder contains complete set of 19 files (README + 12 parts + 6 appendices)

**Translation workflow:**
1. Check if language folder exists in `protocol/` - if not, create it
2. Copy structure from `protocol/en/` (19 files)
3. Translate `README.md` first (it contains table of contents)
4. Translate files in priority order (see below)
5. Update main `README.md` to add link to your language
6. Submit with language code, translator credits, and completion percentage

**Translation priorities:**
- **Critical:** `README.md` (navigation) + `02_identity_and_access.md` (passwords & 2FA)
- **High:** `04_archive_data_and_memories.md` (backups) + `b_crisis_scenarios_first_aid.md` (emergencies)
- **Medium:** Complete parts 01-12 in order
- **Low:** Appendices a, c, d, e, f

### Advanced Topics (Help Wanted)

Protocol Zero currently covers fundamentals for average users. We welcome contributions on advanced security topics:

**High Priority:**
- Tor Browser usage and configuration
- PGP/GPG email encryption
- Threat modeling frameworks
- State-level adversary protection
- High-risk journalism/activism security
- VPN legality and restrictions by country (ongoing updates)

**Welcome additions:**
- Advanced cryptography concepts
- Operational security (OPSEC) practices
- Digital forensics awareness
- Secure communication for whistleblowers
- Border crossing security

These topics would likely fit as new appendix or expansion of existing chapters. Open an issue to discuss scope and approach before starting significant work.

## ✍️ Style Guide

### General Principles

- **Clarity over cleverness** - simple language, accessible to non-technical readers
- **Actionable** - every recommendation should be implementable
- **Neutral** - avoid brand promotion, recommend multiple options
- **Evidence-based** - cite sources when making security claims

### Formatting Standards

**Headers:**
```markdown
# Main Header (H1) - Part/Appendix title only
## Section (H2)
### Subsection (H3)
#### Topic (H4)
```

**Priority Markers:**
```markdown
- **[CRITICAL]** - Do this immediately
- **[RECOMMENDED]** - Significant benefit
- **[ADVANCED]** - For tech-savvy users
- **[OPTIONAL]** - Specific situations only
```

**Code and Commands:**
```markdown
Use `backticks` for inline commands
Use ```code blocks``` for multi-line code
```

**Emojis:**
Use sparingly and functionally:
- 📖 (book) - Part headers (I-XII)
- 🚨 (siren) - Crisis/emergency sections
- 🗺️ (map) - Navigation sections
- 🚀 (rocket) - Quick start/action sections
- ⚠️ (warning) - Important warnings
- Country flags (🇬🇧🇵🇱 etc.) - Language selection only

Note: Appendices currently do not use emoji in headers. Avoid decorative emoji - use only where they add clear navigational or warning value.

### File-Specific Rules

**README in each language folder:**
- Combines table of contents + quick start guide
- Links to all 18 content files (12 parts + 6 appendices)
- Includes quick start paths and skill level guidance

**Tools in `a_tools_essential_list.md`:**
- List 2-3 options per category
- Include free/open-source when possible
- Note platform compatibility (Windows/Mac/Linux/mobile)
- Mark deprecated tools clearly

**Crisis scenarios in `b_crisis_scenarios_first_aid.md`:**
- Step-by-step numbered procedures
- Include time estimates ("within 5 minutes", "within 1 hour")
- Prioritize speed over perfection

**Glossary in `e_extended_glossary.md`:**
- Alphabetical order
- Plain language definitions
- Include common misconceptions where relevant

## ❌ What NOT to Contribute

- **Illegal activities** - hacking, piracy guides, illegal surveillance
- **Dangerous advice** - anything that could harm users
- **Promotional content** - advertising specific products/services
- **Unverified claims** - security advice without credible sources
- **Off-topic** - content unrelated to digital privacy/security

## 🔍 Review Process

All contributions are reviewed for:

1. **Accuracy** - is the information correct and current?
2. **Safety** - could this advice harm users?
3. **Clarity** - is it understandable to target audience?
4. **Consistency** - does it match existing style and structure?
5. **Completeness** - are there missing steps or edge cases?

## 📋 Checklist Before Submitting

- [ ] I've read the relevant section(s) completely
- [ ] My changes are accurate and up-to-date
- [ ] I've followed the style guide
- [ ] I've tested any procedures/commands I'm recommending
- [ ] I've checked for typos and broken links
- [ ] My contribution is within scope (see "What NOT to Contribute")
- [ ] I've provided a clear description of changes

## 🙏 Recognition

All contributors will be acknowledged in the versioning log (see `protocol/en/f_versioning_and_maintenance_plan.md` or equivalent in your language).

Significant contributions (entire sections, translations, major rewrites) will be credited in the main README and language-specific README files.

## 📜 License

By contributing, you agree that your contributions will be licensed under CC BY-SA 4.0, the same license as the main document.

This means your work:
- Will be freely shared and modified
- Requires attribution to you
- Must remain under the same license

## 🆘 Questions?

Not sure if your contribution fits? Have questions about the process?

Open an issue with tag `[question]` and we'll help guide you.

---

## 🔧 For Developers

If you want to run the documentation site locally or work on technical infrastructure:
- See [.github/README.md](.github/README.md) for setup instructions
- Requirements and build tools are in `.github/` directory

**Regular contributors don't need this** - you can edit `.md` files directly on GitHub!

**Every contribution makes Protocol Zero better for everyone. Thank you!**
