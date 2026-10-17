# Profile README implementation notes

## Main profile
- `README.md`

## Contribution snake
- `.github/workflows/contribution-snake.yml`

## Generated branch
- `output`

## Generated SVG files
- `github-contribution-grid-snake.svg`
- `github-contribution-grid-snake-dark.svg`

## Setup
1. Push this repository to GitHub.
2. In Settings → Actions → General, enable read/write workflow permissions if allowed.
3. Open Actions → Generate Contribution Snake.
4. Run the workflow manually.
5. Confirm both SVG files exist in the `output` branch.
6. Test the raw SVG URLs and review the profile README.

No access tokens should be stored in this file.
