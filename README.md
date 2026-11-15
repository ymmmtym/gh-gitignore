# gh-gitignore

Download `.gitignore` from [github/gitignore](https://github.com/github/gitignore) to current dir.

## Usage

```bash
gh extension install ymmmtym/gh-gitignore
gh gitignore
```

By default the selected template overwrites `.gitignore`. To keep the existing
file and append the template instead, set `APPEND=1`:

```bash
APPEND=1 gh gitignore
```

## Authentication

This extension reads the authentication token with `gh auth token` and calls the
API through the `gh api` client. Both support tokens stored in the system keyring
(macOS Keychain, GNOME Keyring, or Wincred) as well as the `GH_TOKEN` /
`GITHUB_TOKEN` environment variables, so secure token storage is supported.

If you are not authenticated, run `gh auth login` first.

