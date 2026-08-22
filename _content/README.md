# Editable text

Everything in this folder is prose you can edit yourself. Change a file, re-render,
and the site picks it up. You never have to touch the page layout or any HTML.

| File                        | Where it appears on the site                    |
|-----------------------------|--------------------------------------------------|
| `background.qmd`            | Home → Background                                 |
| `research-interests.qmd`    | Home → Research interests (the three bullets)     |
| `collaboration-note.qmd`    | Home → the sentence under the keyword pills       |
| `research-aol.qmd`          | Research → summary under the Age-of-Latent preprint |
| `research-tmc.qmd`          | Research → summary under the TMC 2026 paper       |
| `research-globecom.qmd`     | Research → summary under the GLOBECOM 2026 paper  |
| `research-twc.qmd`          | Research → summary under the TWC 2024 paper       |
| `research-vtc.qmd`          | Research → summary under the VTC-Spring 2024 paper|

## Rules

- Plain Markdown. `**bold**`, `*italic*`, `[text](https://url)`, `- bullet` all work.
- A blank line starts a new paragraph.
- Do NOT add a heading (`##`) — the page already provides it.
- Do NOT rename or delete these files; the pages include them by name.

## Why this folder is never published

Quarto ignores any file or folder whose name starts with `_`, so `_content/` is never
rendered as its own page. Its text only appears where a page includes it.

## Preview your changes

    quarto preview

## Note on the research summaries

Those four paragraphs describe published papers. If you reword them, keep the claims
inside what each paper actually shows — an earlier audit found several summaries had
drifted stronger than the papers supported.
