# Contributing to Dust Whisperers

Thank you for your interest in contributing. Please read these guidelines before submitting any changes.

## Getting Started
1. Clone the repository
2. Install dependencies: `npm install`
3. Copy `.env.example` to `.env` and fill in your values
4. Run locally: `npm run dev`

## Branching Strategy
- `main` — production-ready code only
- `develop` — integration branch for features
- `feature/your-feature-name` — individual feature branches
- `fix/your-fix-name` — bug fix branches

Always branch from `develop`, never from `main`.

## Submitting Changes
1. Create a feature or fix branch from `develop`
2. Make your changes with clear, focused commits
3. Ensure all tests pass: `npm test`
4. Open a Pull Request against `develop`
5. Fill out the Pull Request template completely

## Commit Message Format
Use clear, present-tense messages:
- `add booking confirmation email`
- `fix null check in pricing calculator`
- `update README with new env variables`

## Code Standards
- Follow the existing code style
- All new code must have tests
- No commented-out code in PRs
- No `.env` files — use `.env.example` for new variables

## Reporting Bugs
Open a GitHub Issue using the Bug Report template. Include as much detail as possible.

## Questions
Open a GitHub Issue using the Feature Request template or reach out to the maintainer.
