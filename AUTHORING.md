# Repository Authoring Instructions

These instructions apply whenever ChatGPT creates or updates study material in this repository.

## Markdown compatibility
- Write files for **GitHub-flavoured Markdown as rendered on GitHub**, not for ChatGPT's own renderer.
- Before committing Markdown, check headings, lists, tables, code spans, mathematical notation and spacing for GitHub rendering.
- Use `$...$` for inline mathematics and `$$...$$` on separate lines for display mathematics.
- Do **not** use ChatGPT/LaTeX inline delimiters such as `\\(...\\)`; they may appear as plain text on GitHub.
- Use valid LaTeX commands inside maths delimiters, for example `$n=1,2,3,\\ldots$`, `$ns^2np^5$`, and `$d^{10}$`.
- Prefer backticks for simple orbital-box diagrams such as `[↑↓] [↑] [↑]`.
- Prefer simple Markdown structures over elaborate formatting.
- Before committing, scan for stray pseudo-maths such as parenthesised `(n+l)`, missing backslashes, or notation that relies on ChatGPT-specific rendering.

## Study-material principles
- Preserve the concept-first approach: include enough reasoning to reconstruct ideas rather than only facts to memorise.
- Do not silently introduce material beyond the scope recorded in the roadmap/study record.
- Quick-reference files should be concise revision aids, not replacements for full lessons.
