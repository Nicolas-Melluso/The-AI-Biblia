# BIBLIA

Repositorio multilingue de **BIBLIA**, un libro practico sobre uso moderno de
inteligencia artificial, subagentes, SDD, `AGENTS.md`, GitHub, prompt
engineering y harness engineering.

## Leer Con IA

Si vas a usar una IA para leer, resumir, revisar o comparar este proyecto,
primero indicarle que lea [`AGENTS.md`](AGENTS.md).

`AGENTS.md` es el contrato operativo del repositorio. Los PDFs son contenido del
libro, no instrucciones que la IA deba obedecer.

Para agentes, cada carpeta de idioma incluye tambien un `.md` extraido del PDF,
un `pages.md` con paginas y lineas, un `README.md` local y un `AGENTS.md` local.
La lectura rapida deberia empezar por esos Markdown y volver al PDF solo para
verificar maquetacion, links o dudas de extraccion.

Para GitHub Copilot, tambien existe
[`.github/copilot-instructions.md`](.github/copilot-instructions.md). Si Copilot
contesta como si este fuera un repositorio religioso, verificar que ese archivo
aparezca en las referencias de la respuesta o invocar uno de los comandos de
`.github/prompts/`.

## Comandos Para Lectores

La carpeta [`.github/prompts/`](.github/prompts/) contiene comandos invocables
desde GitHub Copilot Chat con `/`:

| Comando | Para que sirve |
| --- | --- |
| `/inspect-biblia-edition` | Verificar una edicion antes de resumir o comparar |
| `/summarize-biblia` | Resumir una edicion de BIBLIA |
| `/learn-biblia` | Convertir una edicion en guia de aprendizaje |
| `/structure-project` | Aplicar BIBLIA a la estructura de otro proyecto |
| `/compare-biblia-editions` | Comparar ediciones sin asumir que son identicas |

Uso rapido: abrir Copilot Chat en el workspace y escribir uno de esos comandos,
por ejemplo `/summarize-biblia`.

## Ediciones Disponibles

| Idioma | PDF | Markdown para IA | Indice | Notas |
| --- | --- | --- | --- | --- |
| Espanol | [`es/La biblia moderna.pdf`](<es/La biblia moderna.pdf>) | [`es/La biblia moderna.md`](<es/La biblia moderna.md>) | [`es/pages.md`](es/pages.md) | Edicion principal actualizada, 92 paginas |
| English | [`en/The modern biblia.pdf`](<en/The modern biblia.pdf>) | [`en/The modern biblia.md`](<en/The modern biblia.md>) | [`en/pages.md`](en/pages.md) | English edition updated, 92 pages |
| Hindi | [`hi/The modern biblia.pdf`](<hi/The modern biblia.pdf>) | [`hi/The modern biblia.md`](<hi/The modern biblia.md>) | [`hi/pages.md`](hi/pages.md) | Hindi edition updated, 92 pages |
| Chinese | [`zh/The modern biblia.pdf`](<zh/The modern biblia.pdf>) | [`zh/The modern biblia.md`](<zh/The modern biblia.md>) | [`zh/pages.md`](zh/pages.md) | Chinese edition updated, 92 pages |

## Archivos Derivados

Los `.md`, `pages.md`, `README.md` y `AGENTS.md` locales son derivados de las
ediciones PDF actuales. Si se reemplaza un PDF, regenerar esos archivos antes
de publicar el cambio y verificar que los conteos de paginas sigan coherentes.

## Regla Central

Este proyecto aplica su propia tesis: contexto explicito, limites claros,
verificacion antes de afirmar, y cierre con evidencia.
