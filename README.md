# GitHub Copilot archives

Download packaged archives from [GitHub Releases](https://github.com/sudwind/github-copilot-blob/releases).

Binary distributions are stored as release assets rather than committed to this repository. Choose the asset for your operating system and architecture; GitHub's automatically generated source archives do not contain the release assets.

## Publishing a release

Place the distribution archive in this folder, then upload it using the GitHub Releases interface or the GitHub CLI:

```sh
gh release create <tag> ./<archive>.zip --title "<release title>" --notes "<version and platform details>"
```

Local ZIP archives and split ZIP parts are ignored by Git.
