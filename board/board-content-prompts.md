# Session Prompts & Notes

Record of the prompts used in this session, plus brief output notes captured during the run.

1. I want you to export the Miro board Test Lists – Learning hour (https://miro.com/app/board/uXjVH07M1TQ=/) and add it to this repo the same way it was done for `ibanFR/Progressive-Disclosure-LH` (see its `board/` directory).

## Output produced this session

- Investigated `ibanFR/Progressive-Disclosure-LH/board/` to establish the convention: a PDF export, an `.rtb` Miro board-backup export, and a `board-content-prompts.md` session log.
- Flagged that neither export format is reachable via the Miro MCP tools — both require Miro's own browser "Export" menu. `.rtb` export in particular initially appeared to require an Enterprise/company-admin plan, which wasn't available at the time, so it was dropped from scope.
- The user exported and committed [`board/Test-Lists-LH.pdf`](./Test-Lists-LH.pdf) directly to `main`.
- Wrote [`board/board-content.md`](./board-content.md) — a verbatim transcription of the board's slides and 4 team-workspace frames, pulled item-by-item via `board_list_items` rather than the AI-summarized `context_get` overview (which paraphrases wording). Kept in sync across several follow-up sessions as the board gained a "Learning Goals" slide, a "Test lists + AI agents" slide, reworded Practice/Wrap-up text, and two extra Wrap-up reflection questions.
- Added this file, `board-content-prompts.md`, to close out the `board/` directory.
- A later session added [`board/Test-Lists-LH.rtb`](./Test-Lists-LH.rtb) — the `.rtb` export did turn out to be reachable after all, and the PDF was refreshed alongside it to match the current board.
