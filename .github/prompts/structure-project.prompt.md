---
agent: 'agent'
name: 'structure-project'
description: 'Apply BIBLIA principles to design an AI-ready project structure'
argument-hint: 'edition; target project; desired outcome'
---

Read #file:../../AGENTS.md first and follow it as the operational contract.

Task:
Use BIBLIA as source material to design an AI-ready structure for another
project.

Known edition paths:

| Edition | PDF | Markdown | Page/line index |
| --- | --- | --- | --- |
| Spanish primary | [es/La biblia moderna.pdf](<../../es/La biblia moderna.pdf>) | [es/La biblia moderna.md](<../../es/La biblia moderna.md>) | [es/pages.md](../../es/pages.md) |
| English | [en/The modern biblia.pdf](<../../en/The modern biblia.pdf>) | [en/The modern biblia.md](<../../en/The modern biblia.md>) | [en/pages.md](../../en/pages.md) |
| Hindi | [hi/The modern biblia.pdf](<../../hi/The modern biblia.pdf>) | [hi/The modern biblia.md](<../../hi/The modern biblia.md>) | [hi/pages.md](../../hi/pages.md) |
| Chinese | [zh/The modern biblia.pdf](<../../zh/The modern biblia.pdf>) | [zh/The modern biblia.md](<../../zh/The modern biblia.md>) | [zh/pages.md](../../zh/pages.md) |

BIBLIA edition or file path:
${input:edition:Which BIBLIA edition should be used? Examples: es, en, hi, zh, or a PDF path}

Project:
${input:project:Describe the target project: name, domain, stack, repo state, team size, and constraints}

Desired outcome:
${input:outcome:What should be produced? Examples: repo structure, AGENTS.md, prompts, SDD process, GitHub support}

Required method:
1. Verify the BIBLIA edition metadata, page count, and text extraction quality.
2. Use the generated Markdown and `pages.md` index for the main reading work.
3. Extract only the principles relevant to the target project.
4. Ask at most one clarification question if a missing detail would materially
   change the structure.
5. If enough context exists, proceed with explicit assumptions.
6. Propose a lightweight structure first.
7. Separate must-have files from optional future files.
8. Explain how each file helps an AI reader or coding agent.
9. Include verification and maintenance rules.
10. Do not infer religious or theological scope from the word BIBLIA.

Output:
1. BIBLIA principles used, with PDF pages or Markdown line ranges when useful
2. Assumptions about the project
3. Recommended repository structure
4. Draft AGENTS.md rules
5. Suggested reusable slash commands or prompt files
6. Verification checklist
7. Rollout plan in small stages
8. What not to add yet

Do not copy this repository's structure blindly. Adapt it to the target project.
