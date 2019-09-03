# Diarama

A CLI tool written in OCaml used for simple *REPL-esque* style development of UML diagrams.

##### **Note:** This tool has not been compiled for a Windows or Linux environment. Linux compilation is pending, via docker build.  *Any assistance in building this command-line for a windows environment would be greatly appreciated*.


### Installation

```
npm install -g @amcorvi/diarama
```

### Usage

```bash

# The following command:
# for every .puml file found in the ./uml directory (-D)
# create png images in the ./images directory (-O)
# on every .puml file update (-W, watchmode).

$ diarama -D ./uml -O ./images -W

```
