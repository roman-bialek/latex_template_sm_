# latex_template_sm_
latex template files to be used with git submodules.

To use simply go to your LaTeX directory (folder), and in a terminal enter
```sh
git submodule add https://github.com/roman-bialek/latex_template_sm_.git
```
(To pull, just enter the submodule's directory and use git as usual.)

In your main LaTeX file, use `\input{latex_template_sm_/SETUP.tex}` after the `\documentclass` statement. See the [example main.tex file](./example/main.tex) for more information.



## Context
This is my personal latex setup file for note taking. Feel free to use it yourself.

Hopefully in the near future I will create a Beamer branch or file?
