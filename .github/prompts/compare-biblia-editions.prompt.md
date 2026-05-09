---
agent: 'agent'
name: 'compare-biblia-editions'
description: 'Compare available BIBLIA language editions without assuming parity'
argument-hint: 'comparison goal'
---

Read #file:../../AGENTS.md first and follow it as the operational contract.

Task:
Compare the available BIBLIA editions.

Known edition paths:

| Edition | PDF | Markdown | Page/line index |
| --- | --- | --- | --- |
| Spanish primary | [es/La biblia moderna.pdf](<../../es/La biblia moderna.pdf>) | [es/La biblia moderna.md](<../../es/La biblia moderna.md>) | [es/pages.md](../../es/pages.md) |
| English | [en/The modern biblia.pdf](<../../en/The modern biblia.pdf>) | [en/The modern biblia.md](<../../en/The modern biblia.md>) | [en/pages.md](../../en/pages.md) |
| Hindi | [hi/The modern biblia.pdf](<../../hi/The modern biblia.pdf>) | [hi/The modern biblia.md](<../../hi/The modern biblia.md>) | [hi/pages.md](../../hi/pages.md) |
| Chinese | [zh/The modern biblia.pdf](<../../zh/The modern biblia.pdf>) | [zh/The modern biblia.md](<../../zh/The modern biblia.md>) | [zh/pages.md](../../zh/pages.md) |

Comparison goal:
${input:goal:What should the comparison focus on? Examples: structure, page counts, translation drift, extraction quality, reader recommendation}

Required method:
1. Inventory every language folder and PDF.
2. Inspect metadata, page count, links, and text extraction quality for each PDF.
3. Use each generated Markdown and `pages.md` index for text comparison.
4. Do not assume translated editions are exact equivalents.
5. Flag page-count drift and extraction problems.
6. Separate observed facts from inferences.
7. Do not infer religious or theological scope from the word BIBLIA.

Output:
1. Editions compared, including PDF and Markdown paths
2. Metadata and page-count table
3. Text extraction quality table
4. Visible structural differences
5. Practical recommendation for readers
6. Limitations or uncertainty

Use the user's language unless they explicitly request another language.
