linter-processing
===========

This linter plugin for [Linter](https://github.com/AtomLinter/Linter) provides an interface to [processing-java](http://processing.org). It will be used on files which have a '.pde' extension.
Linter-processing is a fork of [linter-clojure](https://github.com/AtomLinter/linter-clojure/).

Linting takes as long as it takes for processing-java to compile, usually around 2 seconds. So after saving, errors will be marked with a slight delay. 
## Installation
On first activation the plugin will install all dependencies automatically. processing-java has to be installed manually.

In order to make sure $PATH is set correctly, you should run Atom from the command line!!! (This is important, elsewise it won't find processing-java).

## Settings
You can configure linter-processing by editing ~/.atom/config.cson (choose Open Your Config in Atom menu):

## Installation of processing-java
Make sure to link the processing-java command correctly. Installation process of processing-java can be seen here: https://atom.io/packages/processing
