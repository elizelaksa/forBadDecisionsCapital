# DPI-HT-01 · Divorce Party International Ltd.

Static English case-review application. It requires no login, database, build step, or API key.

## Publish

1. Replace the two student placeholders in `submission.json` with the student's real ID and name.
2. Push this directory to a new GitHub repository.
3. Import that repository into Vercel as an **Other / static** project. No build command is required.

Routes: `/`, `/review`, and `/submission.json`.

`submission.json` contains the 100 official decision IDs (`D001`–`D100`) and is kept together with `submission-rules.json` for validation/reference.
