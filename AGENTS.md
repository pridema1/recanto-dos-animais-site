# Project Agent Instructions

## Default Skills

- Use `build-web-apps` by default for frontend work in this project: UI changes, visual QA, responsive checks, layout, styling, and local web app verification.
- Use `caveman:caveman` by default for communication in this project.

## Communication

- Default `caveman` intensity: `full`.
- Keep technical accuracy. Be terse. Remove filler.
- Use normal, explicit wording for security warnings, irreversible actions, approvals, commits, PR text, and any step where terse fragments could cause confusion.

## Project Context

- Site: Recanto dos Animais.
- Brand colors:
  - Pink: `#E6007E`
  - Blue: `#00509D`
  - White: `#FFFFFF`
  - Dark text: `#25272B`
- Instagram reference: `https://www.instagram.com/rec_dos_animais_/`

## Frontend Defaults

- Preserve current static multi-page structure unless user asks for framework migration.
- Keep pages responsive and usable without a build step.
- Use the local logo asset at `assets/recanto-logo.jpeg`.
- After frontend edits, verify at least the affected page over local HTTP when practical.
