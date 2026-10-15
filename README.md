# custodes-sandbox

A test target for [Custodes](https://github.com/mackowski/custodes) agents (triage,
implementation-check, proposal-review, pr-gate). **This is not security guidance.** Issues and
pull requests here are scenarios, and many contain deliberate prompt-injection payloads.

- `cheatsheets/`, `CONTRIBUTING.md` and the issue and PR templates are copied from
  [OWASP Cheat Sheet Series](https://github.com/OWASP/CheatSheetSeries) at commit
  `72865b1e3b5754246a101778dc00b37f9c233373`. They are licensed under
  [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); the copyright stays with the
  OWASP Cheat Sheet Series contributors. Changes: the file selection, this README, and deliberate
  test seeds made by `e2e/sandbox/run.ts seed`: two typos (`algorthm`, `atribute`) and a planted
  HTML comment addressed to AI review tools in the SQL Injection Prevention cheat sheet.
- The labels mirror the upstream ones (`ACK_WAITING`, `ACK_OBTAINED`, `HELP_WANTED`,
  `WAITING_UPDATE`, …) so that the agents apply the same rules here.
- Scenarios are created and checked by `e2e/sandbox` in the Custodes repository. Pull requests
  here may be closed automatically by the `pr-gate` agent, with a signed comment.

Please do not open real contributions here; send them to the
[OWASP Cheat Sheet Series](https://github.com/OWASP/CheatSheetSeries).
