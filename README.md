# Sky Run – Dino Chase

A lightweight Temple Run–style browser game set in the sky. Run across floating cloud platforms, jump over gaps, and try to stay ahead of the chasing dinosaur.

## Play the game

1. Open the game file **[Run - Dino Chase](./Run%20-%20Dino%20Chase)** and download it.
2. Save it as `index.html` on your device.
3. Open `index.html` in a modern browser.
4. Press **Space** to jump.

> The game is currently a single-file HTML canvas project. The repository file has no `.html` extension, so save the downloaded copy as `index.html` before opening it in a browser.

## Features

- Endless-runner-inspired gameplay
- Floating cloud platforms
- Jumping with gravity
- A dinosaur that chases the player
- Score challenge and game-over condition

## Repository management

This repository includes collaboration and safety guidance to help contributors work together as the project grows.

- **[Contributing guide](CONTRIBUTING.md):** branches, focused changes, testing, and pull requests.
- **[Code of Conduct](CODE_OF_CONDUCT.md):** community expectations and reporting.
- **[Security policy](SECURITY.md):** responsible vulnerability reporting.
- **[CODEOWNERS](.github/CODEOWNERS):** default code owner for review routing.
- **Pull request template:** prompts contributors to describe and test changes.
- **Issue templates:** structured bug reports and feature requests.

### Repository ground rules

1. Keep changes focused and explain them clearly.
2. Test gameplay in a modern browser before opening a pull request.
3. Never commit credentials, tokens, private data, or secrets.
4. Use pull requests for review rather than making unreviewed changes directly to the default branch.
5. Treat other contributors respectfully and keep feedback constructive.
6. Report security vulnerabilities privately rather than posting exploit details publicly.

### Recommended GitHub settings for maintainers

For stronger enforcement, open **Settings → Rules → Rulesets** (or **Settings → Branches**, depending on the interface) and create a ruleset targeting `main`. Where available, require pull requests before merging, require at least one approval, dismiss stale approvals after new commits, require conversation resolution, block force pushes, and restrict deletion. Apply rules only after confirming they won't block necessary maintenance. These server-side settings must be enabled in GitHub repository settings; documentation files alone do not enforce them.

## Collaboration model

This is currently a personal repository. The owner controls repository settings and merges changes. If the project moves to a GitHub organization, use organization teams for ownership and review responsibilities rather than relying only on individual usernames.

## Project structure

- `Run - Dino Chase` — single-file HTML/CSS/JavaScript game.
- `CONTRIBUTING.md` — contributor workflow.
- `CODE_OF_CONDUCT.md` — community standards.
- `SECURITY.md` — vulnerability reporting.
- `.github/` — code ownership and issue/pull-request templates.

## Acknowledgment

Built as a small browser-game project and improved with repository-management practices for collaborative development.
