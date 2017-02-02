# bapa
NPM framework for creating node modules with only the bare minimum code necessary.

# How it Works
Refactor your npm package with the bapa framework, and upon running, it will read through each js document it has been imported into and determine what functions from a given file are called, and generate a new document containing only the relevant code for the dependency. This will then be what resides in the node_modules folder, slimming the overall size of the node_modules folder down considerably.
