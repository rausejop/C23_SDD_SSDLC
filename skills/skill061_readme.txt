# SKILL: skill061_readme
# ROLE: Documentation & Display Lead
# CONTEXT: Standardized README Generation
# STATUS: UPDATED
# DATE: 2026-03-30

## [0] METADATA (ADR)
- Problem: Inconsistent entry points for projects.
- Decision: Standard README skeleton.
- Mechanism: Enforced Markdown generation via checklist.
- Consequence: Professional project presentation.

---

## [1] README REQUIREMENTS (Standard Readme Specification)
The generated README MUST strictly follow the "Standard Readme" structure to ensure cross-language documentation clarity.

### 1.1 Structure & Sections (Ordered)
1.  **Title**: Required. Format: `# Project Name _(repo-name)_`.
2.  **Banner**: Optional. No title. Local image link directly after title.
3.  **Badges**: Optional. No title. Newline delimited. MUST include [![Standard Readme](https://img.shields.io/badge/standard--readme-OK-green?style=flat-square)](https://github.com/RichardLitt/standard-readme).
    - [X] Project Name
    - [X] Version: v2026.03
    - [X] Framework: C23_SDD_SSDLC
    - [X] Security: ISO27001:2022 | ISA 62443 | NIST CSF 2.0 | OWASP 2025
    - [X] License: Apache 2.0
    - [X] Platform: Windows 11
    - [X] Python: 3.14.3
    - [X] AI Ops. "Antigravity" | "Claude Code"
4.  **Short Description**: Required. No title. < 120 chars. On its own line. Match packager/repo description.
5.  **Long Description**: Optional. No title. Progressively detailed overview.
6.  **Table of Contents**: Required (> 100 lines). Links to all Level 2 (##) headings.
7.  **Security**: Optional. High-level security concerns and C23-SDD integrity mandates.
8.  **Background**: Optional. Motivation, intellectual provenance, and abstract dependencies.
9.  **Install**: Required. Code block for installation. Subsections: `### Dependencies`.
10. **Usage**: Required. Code block illustrating common usage or CLI interface.
11. **API**: Optional. Describe exported functions, return types, and caveats.
12. **Maintainers**: Optional. List maintainers with contact info (GitHub/Email).
13. **Thanks**: Optional. Acknowledgements and public contact links.
14. **Contributing**: Required. PR acceptance policy, where to ask questions, and links to CoC.
15. **License**: Required. MUST BE THE LAST SECTION. SPDX identifier and owner.

### 1.2 Esthetics & Formatting
- **Language**: Default English (Oxford). i18n filenames: `README.<bcp47>.md`.
- **Links**: Check for broken links before delivery.
- **Ethics**: Use separators (`---`) between major logical blocks if it improves readability without breaking the spec.
- **C23 SDD SSDLC compliance**: Integrate the C23 SDD SSDLC Metodology maturity matrix and build status into "Extra Sections" between Usage and API.

---

## [2] GENERATION CHECKLIST
Verivy compliance with Standard Readme Specification:
- [X] Be called README (with capitalization) and have a specific extension depending on its format (.md for Markdown, .org for Org Mode Markup syntax, .html for HTML, ...)
- [X] If the project supports i18n, the file must be named accordingly: README.de.md, where de is the BCP 47 Language tag. For naming, prioritize non-regional subtags for languages. If there is only one README and the language is not English, then a different language in the text is permissible without needing to specify the BCP tag: e.g., README.md can be in German if there is no README.md in another language. Where there are multiple languages, README.md is reserved for English.
- [X] Be a valid file in the selected format (Markdown, Org Mode, HTML, ...).
- [X] Sections must appear in order given below. Optional sections may be omitted.
- [X] Sections must have the titles listed below, unless otherwise specified. If the README is in another language, the titles must be translated into that language.
    - [X] Title
    - [X] Banner
    - [X] Badges
    - [X] Short Description
    - [X] Long Description
    - [X] Table of Contents
    - [X] Security
    - [X] Background
    - [X] Install
    - [X] Usage
    - [X] Extra Sections
    - [X] API
    - [X] Maintainers
    - [X] Thanks
    - [X] Contributing
    - [X] License
- [X] Must not contain broken links.
- [X] If there are code examples, they should be linted in the same way as the code is linted in the rest of the project.

---

## [3] REFERENCES
- [Standard Readme Specification](https://github.com/RichardLitt/standard-readme/blob/main/spec.md)