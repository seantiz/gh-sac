# gh-sac

A `gh` extension to **s**earch **a**nd **c**lone repositories.

If you're familiar with the [zoxide](https://github.com/ajeetdsouza/zoxide) workflow - this is a gh search wrapper to mimic that ease of jumping to your target without ever leaving your terminal.

## Requirements

Please make sure you have [fzf](https://github.com/junegunn/fzf) installed

## Installation
```bash
gh extension install seantiz/gh-sac
```

## Usage

Search for a repository and clone it interactively:
```bash
gh sac svelte
```

This will search Github for repos matching "svelte" and show the results for you to scroll though. Hit Enter on your selection to clone the repo.

## License

MIT
