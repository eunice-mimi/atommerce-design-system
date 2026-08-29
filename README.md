# Atommerce Design System

Atommerce Core Design System documentation site.

Live site: https://atommerce-design-system.vercel.app

## AI integration

- AI index: `https://atommerce-design-system.vercel.app/llms.txt`
- Skill file: `https://atommerce-design-system.vercel.app/skill/SKILL.md`

The Skill contains global design policy.
Each component / pattern / template page contains page-specific implementation rules.

## Updating the deployed site

1. Replace the changed files in the GitHub repository.
2. Commit to `main`.
3. Vercel will redeploy automatically.


## Home

`index.html` is the Design System Guide homepage.
Clicking the `Atommerce Design System` title in the left sidebar always returns to this page.


## Claude Code onboarding

The homepage includes a one-click copy button for the global Skill URL.

Install source:
`https://atommerce-design-system.vercel.app/skill/SKILL.md`

Recommended usage:
1. Copy the global Skill URL from the homepage and register it in the Claude environment.
2. Open a relevant Component / Pattern / Template page.
3. Use `복사하기` to copy the documentation page URL.
4. Paste that context into Claude Code with the UI request.

## v28 visual direction
- Documentation chrome is intentionally minimal.
- Text-only Atommerce Design System logo.
- No breadcrumb/current-location top bar on detail pages.
- Update date appears only on each product introduction page.
- Overview pages use simple 3-column cards with code-rendered previews.
- Keep component/spec documentation complete; avoid additional editorial explanation.

## v29 service-first filesystem
The documentation filesystem now mirrors the product-first IA:
`/<service>/<category>/<detail>.html`.
Color documentation is separated per service, while values continue to come from the Figma Color Token service modes.
