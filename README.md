Word lists from my readings
Migrate from markdown to LaTex
```sh
sed -r -e 's/^\* /\\hline\n/' -e 's/^  [0-9]\. (.*)/\&\n\1\n\\\\\n/' -e 's/^### (.*)/\\hline\n\\multicolumn{2}{|l|}{\\textbf{\1}}\\\\/'
```
