# AI Batch: LLM Fundamentals

This repository contains learning materials for software testers, including a self-paced, browser-based introduction to large language model (LLM) fundamentals and practical QA prompt exercises.

## Open the course

Open [LLM_Fundamentals.html](./01_LLM_Fundamentals_Folder/LLM_Fundamentals.html) in a modern web browser. No installation, build step, or server is required.

## What you'll learn

The 13 lessons build from foundational ideas to practical evaluation:

1. AI, machine learning, and LLMs
2. How an LLM works
3. Tokens
4. Foundation, base, and chat models
5. Prompts
6. Temperature
7. Context windows
8. Memory and its limits
9. Retrieval-augmented generation (RAG)
10. Tools and the Model Context Protocol (MCP)
11. AI agents
12. Why LLMs get things wrong
13. Testing LLM output

Along the way, you can work through nine hands-on labs, answer lesson quick checks, and refer to a plain-language glossary and course reference sheet.

## QA prompt exercises

The [02_STAR_METHOD](./01_LLM_Fundamentals_Folder/02_STAR_METHOD/) folder contains example prompts for applying structured prompting to software testing:

- [CLEAR.MD](./01_LLM_Fundamentals_Folder/02_STAR_METHOD/CLEAR.MD) requests functional login test cases based on explicitly supplied requirements.
- [CRISP.MD](./01_LLM_Fundamentals_Folder/02_STAR_METHOD/CRISP.MD) requests a concise, reproducible hypothetical login bug report.
- [star.md](./01_LLM_Fundamentals_Folder/02_STAR_METHOD/star.md) outlines a broader login test-suite exercise.

These are exercise prompts, not verified test results or confirmed product defects. Review each prompt's stated assumptions and scope before using it.

## How to use it

1. Clone or download this repository.
2. Open `01_LLM_Fundamentals_Folder/LLM_Fundamentals.html` in your browser.
3. Follow the course navigation at your own pace. Try the practice activities and quick checks as you go.
4. Open the Markdown files in `01_LLM_Fundamentals_Folder/02_STAR_METHOD/` to explore the QA prompt exercises.

The course keeps lesson-completion progress and the selected theme in your browser's local storage. This information is specific to that browser; clearing its stored site data will reset it.

## Repository structure

```text
.
├── README.md
└── 01_LLM_Fundamentals_Folder/
    ├── LLM_Fundamentals.html
    └── 02_STAR_METHOD/
        ├── CLEAR.MD
        ├── CRISP.MD
        └── star.md
```
