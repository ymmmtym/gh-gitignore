# gh-gitignore

Download `.gitignore` from [github/gitignore](https://github.com/github/gitignore) to current dir.

## Requirements

- [GitHub CLI](https://cli.github.com/) (`gh`), logged in via `gh auth login`
- [fzf](https://github.com/junegunn/fzf)
- [curl](https://curl.se/)

## Usage

```bash
gh extension install ymmmtym/gh-gitignore
gh gitignore
```

The authentication token is retrieved with `gh auth token`, so it works with
tokens stored in the system keyring.

