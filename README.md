###  xdvipdfmx:fatal: Invalid font: -1 (0)

This is a small repository to demonstrate the issue of failing to render a PDF document using the default xelatex pdf engine in quarto when setting up a custom font.

Currently this fails when trying to set up the font Ubuntu. But I tried with Times New Roman (after installing the appropirate package) and it failed too.

See discussion here for more details:
https://github.com/quarto-dev/quarto-cli/discussions/12071

The workaround is to change the engine to `lualatex` in the yaml of the quarto document.

See the log at https://github.com/novica/quarto-render-to-pdf-custom-font-issue/actions/runs/13291012938 for mode details.

See similar issuses discussed here: https://duckduckgo.com/?q=xdvipdfmx%3Afatal%3A+Invalid+font%3A+-1+(0)
