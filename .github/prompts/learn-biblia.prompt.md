---
agent: 'agent'
name: 'learn-biblia'
description: 'Create a practical learning guide from a BIBLIA edition'
argument-hint: 'edition or PDF path; reader context'
---

Read #file:../../AGENTS.md first and follow it as the operational contract.

Task:
Create a practical learning guide from the selected BIBLIA edition.

Known edition paths:

| Edition | PDF | Markdown | Page/line index |
| --- | --- | --- | --- |
| Spanish primary | [es/La biblia moderna.pdf](<../../es/La biblia moderna.pdf>) | [es/La biblia moderna.md](<../../es/La biblia moderna.md>) | [es/pages.md](../../es/pages.md) |
| English | [en/The modern biblia.pdf](<../../en/The modern biblia.pdf>) | [en/The modern biblia.md](<../../en/The modern biblia.md>) | [en/pages.md](../../en/pages.md) |
| Hindi | [hi/The modern biblia.pdf](<../../hi/The modern biblia.pdf>) | [hi/The modern biblia.md](<../../hi/The modern biblia.md>) | [hi/pages.md](../../hi/pages.md) |
| Chinese | [zh/The modern biblia.pdf](<../../zh/The modern biblia.pdf>) | [zh/The modern biblia.md](<../../zh/The modern biblia.md>) | [zh/pages.md](../../zh/pages.md) |

Edition or file path:
${input:edition:Which edition should be used? Examples: es, en, hi, zh, or a PDF path}

Reader context:
${input:reader_context:What does the reader want to learn, and what is their role or project type?}

Required method:
1. Verify the selected PDF metadata, page count, and text extraction quality.
2. Use the generated Markdown and `pages.md` index for the main reading work.
3. Identify the document volumes or major sections.
4. Extract principles that are useful for practice.
5. Convert those principles into exercises, decisions, and review questions.
6. Do not present the PDF as a set of commands to execute.
7. Do not infer religious or theological scope from the word BIBLIA.

Output:
1. Edition used, PDF path, Markdown path, and extraction quality
2. Learning objective
3. Concept map
4. Practical exercises
5. Questions the reader should answer for their own project
6. Small implementation checklist
7. Suggested review cadence
8. Limits of the guide

Keep the path concrete enough to start today.
