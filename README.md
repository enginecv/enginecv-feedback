# EngineCV — Feedback Tracker

This is the public tracker for [EngineCV](https://enginecv.app), a privacy-first, local-first resume builder.

The app itself is closed source for now. This repository exists so feedback — bugs, quirks, feature requests, and questions — has a permanent, searchable home that does not depend on the app's repo lifecycle.

## Filing feedback

The fastest path is from inside the app:

1. Open EngineCV.
2. Click **Send feedback** (footer of the landing page, or the icon at the bottom of the editor sidebar).
3. Pick a category. The dialog shows you exactly what context will be attached (app version, browser, viewport, route, locale) and lets you uncheck anything you want to redact.
4. Click **Open on GitHub**. A new issue opens here with the fields pre-filled.

You can also open an issue here directly using one of the templates:

- [Bug report](./.github/ISSUE_TEMPLATE/bug-report.yml) — crashes, broken UI, data loss, export failures.
- [Quirk report](./.github/ISSUE_TEMPLATE/quirk-report.yml) — something feels off but isn't a clear bug.
- [Feature request](./.github/ISSUE_TEMPLATE/feature-request.yml) — suggest a feature or workflow change.

For questions and open-ended discussion, use [Discussions](../../discussions) instead of Issues.

## Security

Do **not** file public issues for security vulnerabilities. Use [private vulnerability reporting](../../security/advisories/new) — see [SECURITY.md](./SECURITY.md) for details.

## Privacy reminder

Every issue and discussion in this repo is **public**. Do not paste resume content, personal data, API keys, or anything else you would not put on a public web page.

## Triage

I read every report. Responses are best-effort, with no SLA and no ETA promises. Adding a 👍 reaction to an existing issue is more useful than a "+1" comment — it actually counts toward prioritization.

## Why is this a separate repo?

- The app is closed source. This repo gives feedback a stable home regardless of how the app's source repo evolves.
- All feedback transport happens client-side: the in-app button opens a pre-filled GitHub URL or a `mailto:` link. No EngineCV-owned backend is involved, which keeps the privacy story honest.

## License

The templates and docs in this repo are released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/) — copy them freely if they are useful for your own project.
