# api documentation for  [gray-matter (v2.1.1)](https://github.com/jonschlinkert/gray-matter)  [![npm package](https://img.shields.io/npm/v/npmdoc-gray-matter.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gray-matter) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gray-matter.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gray-matter)
#### Parse front-matter from a string or file. Fast, reliable and easy to use. Parses YAML front matter by default, but also has support for YAML, JSON, TOML or Coffee Front-Matter, with options to set custom delimiters. Used by metalsmith, assemble, verb and

[![NPM](https://nodei.co/npm/gray-matter.png?downloads=true)](https://www.npmjs.com/package/gray-matter)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gray-matter/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gray-matter_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gray-matter/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gray-matter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gray-matter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/gray-matter/issues"
    },
    "contributors": [
        {
            "name": "Andrew Meyer",
            "url": "https://github.com/Ajedi32"
        },
        {
            "name": "Brian Woodward",
            "email": "brian.woodward@gmail.com",
            "url": "https://github.com/doowb"
        },
        {
            "name": "Ian Storm Taylor",
            "url": "http://ianstormtaylor.com"
        },
        {
            "name": "Jon Schlinkert",
            "email": "jon.schlinkert@sellside.com",
            "url": "http://twitter.com/jonschlinkert"
        },
        {
            "name": "Pawel Kadluczka",
            "url": "http://blog.3d-logic.com"
        },
        {
            "name": "Rob Loach",
            "email": "robloach@gmail.com",
            "url": "http://robloach.net"
        }
    ],
    "dependencies": {
        "ansi-red": "^0.1.1",
        "coffee-script": "^1.12.4",
        "extend-shallow": "^2.0.1",
        "js-yaml": "^3.8.1",
        "toml": "^2.3.2"
    },
    "description": "Parse front-matter from a string or file. Fast, reliable and easy to use. Parses YAML front matter by default, but also has support for YAML, JSON, TOML or Coffee Front-Matter, with options to set custom delimiters. Used by metalsmith, assemble, verb and ",
    "devDependencies": {
        "ansi-bold": "^0.1.1",
        "ansi-gray": "^0.1.1",
        "benchmarked": "^0.2.5",
        "delimiter-regex": "^2.0.0",
        "for-own": "^0.1.4",
        "front-matter": "^2.1.2",
        "glob": "^7.1.1",
        "gulp": "^3.9.1",
        "gulp-eslint": "^3.0.1",
        "gulp-format-md": "^0.1.11",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^4.0.1",
        "lodash": "^4.17.4",
        "minimist": "^1.2.0",
        "should": "^11.2.0",
        "sort-object": "^3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "3042d9adec2a1ded6a7707a9ed2380f8a17a430e",
        "tarball": "https://registry.npmjs.org/gray-matter/-/gray-matter-2.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "gray-matter.d.ts",
        "index.js",
        "lib"
    ],
    "gitHead": "995dd7d6e2e572e6a224a8f02417e558d76a076e",
    "homepage": "https://github.com/jonschlinkert/gray-matter",
    "keywords": [
        "assemble",
        "coffee",
        "coffee-script",
        "data",
        "docs",
        "documentation",
        "extract",
        "extracting",
        "front",
        "front-matter",
        "frontmatter",
        "generate",
        "generator",
        "gh-pages",
        "gray",
        "javascript",
        "jekyll",
        "js",
        "JSON",
        "markdown",
        "matter",
        "parse",
        "parser",
        "parsing",
        "site",
        "static",
        "template",
        "toml",
        "yaml",
        "yfm"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert",
            "email": "github@sellside.com"
        },
        {
            "name": "doowb",
            "email": "brian.woodward@gmail.com"
        }
    ],
    "name": "gray-matter",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/gray-matter.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "typings": "gray-matter.d.ts",
    "verb": {
        "related": {
            "list": [
                "assemble",
                "metalsmith",
                "verb"
            ]
        },
        "toc": false,
        "layout": "default",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "lint": {
            "reflinks": true
        },
        "reflinks": [
            "assemble",
            "front-matter",
            "verb",
            "verb-generate-readme"
        ]
    },
    "version": "2.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gray-matter](#apidoc.module.gray-matter)
1.  [function <span class="apidocSignatureSpan">gray-matter.</span>read (fp, options)](#apidoc.element.gray-matter.read)
1.  [function <span class="apidocSignatureSpan">gray-matter.</span>stringify (str, data, options)](#apidoc.element.gray-matter.stringify)
1.  [function <span class="apidocSignatureSpan">gray-matter.</span>test (str, options)](#apidoc.element.gray-matter.test)
1.  object <span class="apidocSignatureSpan">gray-matter.</span>parsers

#### [module gray-matter.parsers](#apidoc.module.gray-matter.parsers)
1.  [function <span class="apidocSignatureSpan">gray-matter.parsers.</span>coffee (str, options)](#apidoc.element.gray-matter.parsers.coffee)
1.  [function <span class="apidocSignatureSpan">gray-matter.parsers.</span>cson (str, options)](#apidoc.element.gray-matter.parsers.cson)
1.  [function <span class="apidocSignatureSpan">gray-matter.parsers.</span>javascript (str, options)](#apidoc.element.gray-matter.parsers.javascript)
1.  [function <span class="apidocSignatureSpan">gray-matter.parsers.</span>js (str, options)](#apidoc.element.gray-matter.parsers.js)
1.  [function <span class="apidocSignatureSpan">gray-matter.parsers.</span>json (str, options)](#apidoc.element.gray-matter.parsers.json)
1.  [function <span class="apidocSignatureSpan">gray-matter.parsers.</span>toml (str, opts)](#apidoc.element.gray-matter.parsers.toml)
1.  [function <span class="apidocSignatureSpan">gray-matter.parsers.</span>yaml (str, options)](#apidoc.element.gray-matter.parsers.yaml)
1.  object <span class="apidocSignatureSpan">gray-matter.parsers.</span>requires



# <a name="apidoc.module.gray-matter"></a>[module gray-matter](#apidoc.module.gray-matter)

#### <a name="apidoc.element.gray-matter.read"></a>[function <span class="apidocSignatureSpan">gray-matter.</span>read (fp, options)](#apidoc.element.gray-matter.read)
- description and source-code
```javascript
read = function (fp, options) {
  var str = fs.readFileSync(fp, 'utf8');
  var obj = matter(str, options);
  return extend(obj, {
    path: fp
  });
}
```
- example usage
```shell
...
### [.read](index.js#L136)

Read a file and parse front matter. Returns the same object as 'matter()'.

**Example**

'''js
matter.read('home.md');
'''

**Params**

* 'fp' **{String}**: file path of the file to read.
* 'options' **{Object}**: Options to pass to gray-matter.
* 'returns' **{Object}**
...
```

#### <a name="apidoc.element.gray-matter.stringify"></a>[function <span class="apidocSignatureSpan">gray-matter.</span>stringify (str, data, options)](#apidoc.element.gray-matter.stringify)
- description and source-code
```javascript
stringify = function (str, data, options) {
  var delims = arrayify(options && options.delims || '---');
  var res = '';
  res += delims[0] + '\n';
  res += YAML.safeDump(data, options);
  res += (delims[1] || delims[0]) + '\n';
  res += str + '\n';
  return res;
}
```
- example usage
```shell
...
Stringify an object to front-matter-formatted YAML, and concatenate it to the given string.

Results in:

**Examples**

'''js
matter.stringify('foo bar baz', {title: 'Home'});
'''

'''yaml
---
title: Home
---
foo bar baz
...
```

#### <a name="apidoc.element.gray-matter.test"></a>[function <span class="apidocSignatureSpan">gray-matter.</span>test (str, options)](#apidoc.element.gray-matter.test)
- description and source-code
```javascript
test = function (str, options) {
  var delims = arrayify(options && options.delims || '---');
  return isFirst(str, delims[0]);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gray-matter.parsers"></a>[module gray-matter.parsers](#apidoc.module.gray-matter.parsers)

#### <a name="apidoc.element.gray-matter.parsers.coffee"></a>[function <span class="apidocSignatureSpan">gray-matter.parsers.</span>coffee (str, options)](#apidoc.element.gray-matter.parsers.coffee)
- description and source-code
```javascript
coffee = function (str, options) {
  var opts = extend({eval: false, strict: false}, options);
  if (opts.eval) {
    try {
      var coffee = parser.requires.coffee || (parser.requires.coffee = require('coffee-script'));
      return coffee['eval'](str, options);
    } catch (err) {
      throw new SyntaxError(msg('coffee-script', err));
    }
  } else {

    // if 'eval' isn't set
    if (opts.strict) {
      throw new Error(evalError('coffee'));
    } else {
      console.error(evalError('coffee', true));
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gray-matter.parsers.cson"></a>[function <span class="apidocSignatureSpan">gray-matter.parsers.</span>cson (str, options)](#apidoc.element.gray-matter.parsers.cson)
- description and source-code
```javascript
cson = function (str, options) {
  var opts = extend({eval: false, strict: false}, options);
  if (opts.eval) {
    try {
      var coffee = parser.requires.coffee || (parser.requires.coffee = require('coffee-script'));
      return coffee['eval'](str, options);
    } catch (err) {
      throw new SyntaxError(msg('coffee-script', err));
    }
  } else {

    // if 'eval' isn't set
    if (opts.strict) {
      throw new Error(evalError('coffee'));
    } else {
      console.error(evalError('coffee', true));
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gray-matter.parsers.javascript"></a>[function <span class="apidocSignatureSpan">gray-matter.parsers.</span>javascript (str, options)](#apidoc.element.gray-matter.parsers.javascript)
- description and source-code
```javascript
javascript = function (str, options) {
  var opts = extend({wrapped: true, eval: false, strict: false}, options);
  if (opts.eval) {
    if (opts.wrapped) {
      str = 'function data() {return {' + str + '}; } data();';
    }
    try {
      return eval(str);
    } catch (err) {
      throw new SyntaxError(msg('javascript', err));
    }
    return {};
  } else {

    // if 'eval' isn't set
    if (opts.strict) {
      throw new Error(evalError('javascript'));
    } else {
      console.error(evalError('javascript', true));
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gray-matter.parsers.js"></a>[function <span class="apidocSignatureSpan">gray-matter.parsers.</span>js (str, options)](#apidoc.element.gray-matter.parsers.js)
- description and source-code
```javascript
js = function (str, options) {
  var opts = extend({wrapped: true, eval: false, strict: false}, options);
  if (opts.eval) {
    if (opts.wrapped) {
      str = 'function data() {return {' + str + '}; } data();';
    }
    try {
      return eval(str);
    } catch (err) {
      throw new SyntaxError(msg('javascript', err));
    }
    return {};
  } else {

    // if 'eval' isn't set
    if (opts.strict) {
      throw new Error(evalError('javascript'));
    } else {
      console.error(evalError('javascript', true));
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gray-matter.parsers.json"></a>[function <span class="apidocSignatureSpan">gray-matter.parsers.</span>json (str, options)](#apidoc.element.gray-matter.parsers.json)
- description and source-code
```javascript
json = function (str, options) {
  var opts = extend({strict: false}, options);
  try {
    return JSON.parse(str);
  } catch (err) {
    if (opts.strict) {
      throw new SyntaxError(msg('JSON', err));
    } else {
      return {};
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gray-matter.parsers.toml"></a>[function <span class="apidocSignatureSpan">gray-matter.parsers.</span>toml (str, opts)](#apidoc.element.gray-matter.parsers.toml)
- description and source-code
```javascript
toml = function (str, opts) {
  try {
    var toml = parser.requires.toml || (parser.requires.toml = require('toml'));
    return toml.parse(str);
  } catch (err) {
    if (opts.strict) {
      throw new SyntaxError(msg('TOML', err));
    } else {
      return {};
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gray-matter.parsers.yaml"></a>[function <span class="apidocSignatureSpan">gray-matter.parsers.</span>yaml (str, options)](#apidoc.element.gray-matter.parsers.yaml)
- description and source-code
```javascript
yaml = function (str, options) {
  var opts = extend({strict: false, safeLoad: false}, options);
  try {
    var YAML = parser.requires.yaml || (parser.requires.yaml = require('js-yaml'));
    return opts.safeLoad ? YAML.safeLoad(str, options) : YAML.load(str, options);
  } catch (err) {
    if (opts.strict) {
      throw new SyntaxError(msg('js-yaml', err));
    } else {
      return {};
    }
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
