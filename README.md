# To use LaTeX in Linux and compile

## Update
```/bash
sudo apt update
```

## Install VSCode and add LaTeX Workshop

## Install latexmk
```/bash
sudo apt install latexmk
```

## Install texlive recommended
```/bash
sudo apt install texlive-latex-recommended
```

## Install texlive extra
```/bash
sudo apt install texlive-latex-extra
```

## Install Biber
```/bash
sudo apt install texlive-bibtex-extra biber
```

# restart VSCode

## to build via terminal
latexmk -pdf -pvc relatorio.tex
