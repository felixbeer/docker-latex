# docker-latex ✍️

LaTeX docker container with TexLive 2025.
It also installs a handful of useful packages to get started quickly.

This image is based on the [jumchovej/devcontainers template](https://github.com/jmuchovej/devcontainers/tree/main)

## Quickstart

To use this image as a devcontainer, copy the `.devcontainer/devcontainer.json` file to your project.

### Add custom packages

You can specify additional LaTeX packages in the `.devcontainer/devcontainer.json` via a `postCreateCommand`:

```json
{
  "postCreateCommand": "tlmgr install <package(s)>"
}
```

## Installed packages

- latexmk
- latexindent
- upquote
- babel-german
- german
- breakurl
- times
- courier
- relsize
- biblatex
- xkeyval
- bigfoot
- xstring
- frankenstein
- csquotes
- acronym
- biblatex-chicago
- lineno
- biber
- appendix
- makecell
- subfig
- caption
- float
- minted
- texcount
- adjustbox
- multirow
- rsfs
