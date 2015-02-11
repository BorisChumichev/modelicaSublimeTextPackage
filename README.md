##Sublime Text Package for the Modelica Language

[view on “GitHub pages”](http://borischumichev.github.io/modelicaSublimeTextPackage/)

Sublime Text editor comes without syntax definitions for [Modelica language](http://www.modelica.org) by default, so the purpose of this package is to bring Modelica language support to Sublime Text. In addition, it provides some handy snippets for commonly used language patterns.

Also, this package is used by [github/linguist](https://github.com/github/linguist) library in order to perform syntax highlighting of Moldelica sources at github. You can [play with it using Lightshow](https://github-lightshow.herokuapp.com/?utf8=%E2%9C%93&scope=source.modelica&grammar_url=https%3A%2F%2Fgithub.com%2FBorisChumichev%2FmodelicaSublimeTextPackage%2Fblob%2Fmaster%2FModelica.tmLanguage&grammar_text=&code_source=from-url&code_url=https%3A%2F%2Fgithub.com%2Fmodelica%2FModelica%2Fblob%2Frelease%2FModelica%25203.2.1%2FElectrical%2FAnalog%2FLines.mo&code=).

###Installation

First [Install Package Controll for Sublime Text](https://packagecontrol.io/installation) (if you still have not done so) and restart Sublime Text.

Then follow these steps:

1. Open Sublime's command palette (`Ctrl(Cmd)+Shift+P`)
1. Enter: Package Control: Install Package
1. Enter: Modelica

Syntax definitions will be applyed for all sources with 'mo' extention. Or you could manually enable syntax through command palette: 'Set Syntax: Modelica'.

### Contributing

Everyone can contribute to the package development. You are welcome to submit a pull request or create an issue. Package is not well tested yet so feedback from first users is really appreciated. Please create an issue if you find any bugs.
