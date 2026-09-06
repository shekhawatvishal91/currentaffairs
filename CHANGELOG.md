# 📝 CHANGELOG & VERSION HISTORY

All notable changes to the Current Affairs Dossier repository and Rajputana Gazette Broadsheet System are documented here.

---

## 🔄 [Unreleased / Staged for Next Push]

---

## 🚀 [v1.1] — 2026-09-06

### 🎯 35+ Strike File Exam Angle Streamlining
- **Removed Redundant Trap Labels**: Cleaned `IBPS_MAINS_35PLUS_MASTER_JAN_SEPT.md` (and modular source generators `ibps_full_sec*.mjs`) by stripping `[THE EXAMINER'S TRAP MATRIX]` and repetitive `Trap A / Trap B / Trap C` bullet prefixes across all 121 case items.
- **Unified Clean Syntax**: All exam angle blocks now begin cleanly with `🎯 Exam Angle →` followed directly by specific topic takeaway bullets (e.g., `• Corridor Math: ...`, `• Stance Confusion: ...`, `• Target MCQ Form: ...`).
- **Preserved 100% Core Fact Discipline**: All distractor logic, numerical thresholds, committee origins, and model MCQ questions remain intact without loss of information.

### 🎨 Broadsheet Hub & Typography
- **Disabled Autolinking (`linkify: false`)**: Set `linkify: false` across both build-time and client-side parsers to prevent proper nouns containing periods (such as `MuleHunter.AI`, `Vyoma.AI`, and `maandhan.in`) from converting into unintentional blue underlined external hyperlinks.
- **Eliminated Heading Anchor Permalinks**: Removed the unsightly `#` symbols appearing after section headings across all documents by removing the `linkInsideHeader` permalink option in `converter.js` and adding defensive CSS rules (`.header-anchor, .anchor-symbol { display: none !important; }`).
- **Preserved TOC & Navigation**: All slug IDs (`id="1-rbi-policy..."`) remain intact so table of contents, sidebar index, and search jump links function smoothly.
- **Web App Mirror Sync**: Synchronized `current_affairs_hub.html` and `index.html` with all v1.1 refinements.

---

## 🚀 [v1.0] — 2026-09-06

### Initial Master Release
- **👑 35+ Strike File**: Standalone master dossier (`IBPS_MAINS_35PLUS_MASTER_JAN_SEPT.md`) with 121 verified news stories + 5 comprehensive reference strike grids (Sports, Days, UNESCO/Ramsar, Defence, Static Banking).
- **April 2026 Dossier**: Unified Parts 1 & 2 into `current_affairs_2026_april.md` with 55 news items organized across all 10 canonical sections.
- **Q1 2026 Consolidated Dossier**: `current_affairs_2026_q1_jan_mar.md` with 91 news items across 10 sections.
- **August 2026 Dossier**: `aug_ca_cgb1-31aug_pib1-18aug.md` with 110 news items.
- **Rajputana Gazette Broadsheet Hub**: Interactive command center (`current_affairs_hub.html` / `index.html`) featuring:
  - Lexend font applied across body, headings, cards, and UI.
  - Non-sticky header with full-width broadsheet dateline strip.
  - Fullscreen Reading Mode (Shortcut: `F`).
  - Terracotta single-line exam boxes (`🎯 EXAM ANGLE`) with inline study mastery checkboxes.
  - Instant multi-month switcher (`👑 35+ Strike File`, `August 2026`, `April 2026`, `Q1 (Jan–Mar)`).
  - Collapsible sidebar with real-time topic filtering.
- **Repository Infrastructure**: Clean `.gitignore` ignoring backup/cache files and `README.md` establishing the strict approval-first push protocol.
