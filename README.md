# IL support for Visual Studio

Extension for Visual Studio Code 

Current features:
* Syntax Highlight


Inspired by [@Paweł Łukasik](https://twitter.com/pawel_lukasik) and his [IL syntax hightligter for Sublime Text](https://bitbucket.org/octalsolutions/cil-sublime).

## Build

Install yaml2json converter like:

```
npm install -g yamljs
```

and convert ```./syntaxes/il.yml``` to ```./syntaxes/il.json``` by doing something like this:

```
yaml2json -s il.yml
```
