# Contributing to StrixMCS Labs

`StrixMCS Labs · Dr. Matt Booth`

These guidelines apply to every StrixMCS Labs repository that does not carry its own `CONTRIBUTING.md`.

## Issues and pull requests

- Describe what happened, what you expected, and how to reproduce it. Include versions and the operating system.
- Keep one change per pull request, and say how you checked it.
- Never post API keys, passwords, cookies, private configuration or personal data in an issue or pull request. Report security problems through the repository's private vulnerability reporting, or email [labs@strixmcs.org](mailto:labs@strixmcs.org).
- Contributions are licensed under the repository's license.

## New repository checklist

Each StrixMCS Labs repository is set up the same way. The [design system](https://github.com/strixmcs-labs/StrixMCS-Design) is the authority; this is the short form.

- **Name.** Plain, descriptive, lowercase and hyphenated. No `Strix` prefix; that belongs to the home. Forks keep the upstream name and casing exactly, and credit upstream beneath the byline. A fork that becomes a separate product under its own name follows the plain rule and still credits upstream.
- **README header.** The project's name as the title, then the byline on one mono line: `StrixMCS Labs · Dr. Matt Booth`.
- **Credit.** If the project is built on another one, credit it directly beneath the byline, before anything else: the project, the author's public name with their GitHub handle in parentheses, and its contributors. Say plainly that the work is independent and not an official release.
- **Footer.** The motto, the gloss, the site and the byline:

  ```
  *Scientia · Societas · Ascensus*
  Knowledge · Society · Ascent
  [mattbooth.me](https://mattbooth.me) · `StrixMCS Labs · Dr. Matt Booth`
  ```
- **Social preview.** 1280×640 on absolute black: the StrixMCS logo (whole) on the left, the project's name in proper case in IBM Plex Mono 600 white, the byline beneath, and a credit line when the project builds on another. Commit it as `.github/social-preview.png` and upload it under Settings → General → Social preview.
- **License and notice.** A `LICENSE`, and a `NOTICE` whose copyright line reads `StrixMCS Labs, Dr. Matt Booth, and other contributors`. Upstream licenses and notices stay with the upstream project.
- **Images.** List every documentation image in `docs/IMAGES.md` with where it is used, alt text, a one-line caption, its capture date and its status.
- **Voice.** Third person or imperative, precise, no emoji, normal case.

## Keeping images current

When a release changes the interface, re-capture the screenshots it affects at the same framing, update their dates in `docs/IMAGES.md`, and redraw any diagram that no longer matches. Mark an unverified image as such rather than guessing.

---

*Scientia · Societas · Ascensus*
Knowledge · Society · Ascent
[mattbooth.me](https://mattbooth.me) · `StrixMCS Labs · Dr. Matt Booth`
