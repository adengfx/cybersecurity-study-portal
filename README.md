# 🛡️ Aden's Cybersecurity Study Portal

A personal study portal for tracking progress through cybersecurity courses, certifications and hands-on labs — built as part of an active learning journey into the field.

🌐 **Live site:** https://adengfx.github.io/cybersecurity-study-portal/

## Study Guides

| Course | Guide | Score | Cert |
|---|---|---|---|
| Cybersecurity Foundations | [View notes](https://adengfx.github.io/cybersecurity-study-portal/cybersecurity_foundations_study_guide.html) | 77% | NASBA |
| Networking Basics | [View notes](https://adengfx.github.io/cybersecurity-study-portal/networking_basics_study_guide.html) | N/A | — |
| IT Security Foundations: Core Concepts | [View notes](https://adengfx.github.io/cybersecurity-study-portal/it_security_foundations_study_guide.html) | 100% | NASBA |

## Lab Pathways

| Platform | Pathway | Status | Rooms |
|---|---|---|---|
| TryHackMe | [Pre-Security](https://adengfx.github.io/cybersecurity-study-portal/labs/presecurity/) | In Progress | 31 rooms · 7 modules |
| TryHackMe | [Cyber Security 101](https://adengfx.github.io/cybersecurity-study-portal/labs/cybersecurity101/) | Not started | 47 rooms · 14 sections |
| TryHackMe | [SOC Level 1](https://adengfx.github.io/cybersecurity-study-portal/labs/soc1/) | Not started | 55 rooms · 14 sections |

## Tools

- [Revision Quiz](https://adengfx.github.io/cybersecurity-study-portal/quiz.html) — randomised questions from all courses
- [Glossary](https://adengfx.github.io/cybersecurity-study-portal/glossary.html) — all key terms with flashcard mode

## What it is

A lightweight, static HTML study hub with a dark-themed interface. Each course gets its own study guide with structured notes, key terms, tables, and concept breakdowns. Lab pathways have a dedicated landing page listing all rooms with progress tracking, linking to individual room guides as they are completed. An index page tracks completed courses, exam scores, and certifications earned.

## Structure

```
index.html                  ← portal home
glossary.html               ← all terms, flashcard mode
quiz.html                   ← randomised multi-choice quiz
favicon.svg
courses/
├── cybersecurity_foundations_study_guide.html
├── networking_basics_study_guide.html
└── it_security_foundations_study_guide.html
labs/
└── presecurity/
    ├── index.html          ← pathway landing page
    └── [room guides]       ← one file per room
```

## How it was built

Vibecoded with Claude from my course notes.

## Stack

Pure HTML + CSS + vanilla JS — no frameworks, no build tools. Hosted on GitHub Pages.
