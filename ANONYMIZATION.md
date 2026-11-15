# What was changed for anonymous review

Only identity was removed; no data value, record or result was changed.

- Removed: `CITATION.cff`, `.zenodo.json`, `paper/paper.pdf`, `paper/paper.html` (author metadata only).
- Renamed: the human labeller's files in `results/ccrab-final/` to `labels-human.csv` and `labels-human-raw.csv`.
- Replaced in text files and inside `.gz` files: author name, user names and e-mails -> `Anonymous Author`,
  `anonymous`, `anonymous@example.com`; home-directory paths in stack traces -> `/Users/anon`, `/tmp/scratch`;
  location words in timestamps' comments -> `local time` ;
  the original repository URL and project name -> this anonymous URL and `forge27-review`; a collaborator's
  third-party repository URL and commit, used only by the withdrawn condition E -> withheld (that code
  path cannot fetch it during review).
- Fresh git history with an anonymous author; see `PROVENANCE.md`.
