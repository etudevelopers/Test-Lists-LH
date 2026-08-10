# Session Prompts & Notes

Record of the prompts used in this session, plus brief output notes captured during the run.

1. I want you to export the Miro board Test Lists – Learning hour (https://miro.com/app/board/uXjVH07M1TQ=/) and add it to this repo the same way it was done for `ibanFR/Progressive-Disclosure-LH` (see its `board/` directory).
2. PDF file added. What format is that RTB?
3. I don't see the option to export the board as a Miro board (RTB format).
4. Yes, go with that (content markdown instead of RTB). This is the location of the PDF file: `board/Test-Lists-LH.pdf`.
5. Forget it, already added to the repo.

## Output produced this session

- Investigated `ibanFR/Progressive-Disclosure-LH/board/` to establish the convention: a PDF export, an `.rtb` Miro board-backup export, and a `board-content-prompts.md` session log.
- Flagged that neither export format is reachable via the Miro MCP tools — both require Miro's own browser "Export" menu. `.rtb` export in particular turned out to require an Enterprise/company-admin plan, which wasn't available here, so it was dropped from scope.
- The user exported and committed [`board/Test-Lists-LH.pdf`](./Test-Lists-LH.pdf) directly to `main`.
- Wrote [`board/board-content.md`](./board-content.md) — a verbatim transcription of the board's 9 slides and 4 team-workspace frames, pulled item-by-item via `board_list_items` rather than the AI-summarized `context_get` overview (which paraphrases wording).
- Added this file, `board-content-prompts.md`, to close out the `board/` directory.
