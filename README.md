This is a small repository to demonstrate the issue of failing to render a PDF document using the default pdf engine in quarto when setting up a custom font.

See discussion here for more details:
https://github.com/quarto-dev/quarto-cli/discussions/12071

The workaround is to change the engine to `lualatex` in the yaml of the quarto document.
