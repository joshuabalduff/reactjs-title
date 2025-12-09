## Tests

All commits that fix bugs or add features need a test.

`<blink>` Do not merge code without tests.`</blink>`

## Commit Messages

This repository uses [Conventional Commits](https://www.conventionalcommits.org/) to automate releases and changelog generation via [Release Please](https://github.com/googleapis/release-please).

Please format your commit messages as:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `chore:` for maintenance tasks
- `test:` for test-related changes

Example: `feat: add new title formatting option`

Breaking changes should include `BREAKING CHANGE:` in the commit body or add `!` after the type: `feat!: remove legacy API`

## Changelog

Changelogs are automatically generated from commit messages using Release Please. The changelog is updated when releases are created.

### Development

- `npm test` will fire up a karma test runner and watch for changes

