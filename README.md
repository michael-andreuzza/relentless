

# *Relentless theme for VS Code.
### Options
You have two themes, Midnight n' Sunset and here the screenshots
### Sunset

![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/cpp.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/cs.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/css.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/html.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/java.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/js.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/md.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/py.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/sunset-screenshots/sh.png?raw=true)

### Midnight
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/cpp.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/cs.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/css.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/html.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/java.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/js.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/md.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/py.png?raw=true)
![VS Code Marketplace](https://github.com/michael-andreuzza/relentless/blob/master/images/midnight-screenshots/sh.png?raw=true)

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for **`Relentless`**
3. Click **Install** to install it.
4. Code > Preferences > Color Theme >
 **Relentless**

## Personal Settings.

```js
{

  "editor.fontFamily": "'Dank Mono', monospace",
  "editor.fontSize": 18,
  "editor.lineHeight": 38,
  "editor.letterSpacing": 0.5,
  "files.trimTrailingWhitespace": true,
  "editor.fontWeight": "normal",
  "prettier.eslintIntegration": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "phase",
  "editor.renderWhitespace": "all",
}
```

The theme uses italics for certain language tokens by default.
To **disable** italics, add this snippet to your `settings.json`:
  - quotes and *italic* strings (like in markdown) will be unaffected and still be italic
  - if you want to exclude one of the themes from this change, simply remove its name (along with the brackets `[]`) at the top of the snippet

```jsonc
"editor.tokenColorCustomizations": {
  "[Relentless Sunset]": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "variable",
          "variable.other.object.js",
          "variable.other.object.property",
          "variable.language",
          "punctuation.accessor",
          "markup.changed",
          "markup.deleted.diff",
          "markup.inserted.diff",
          "keyword",
          "keyword.operator.relational",
          "keyword.operator.comparison",
          "keyword.control.flow.js",
          "keyword.control.flow.ts",
          "keyword.control.flow.tsx",
          "keyword.control.ruby",
          "keyword.control.module.ruby",
          "keyword.control.class.ruby",
          "keyword.control.def.ruby",
          "keyword.control.loop.js",
          "keyword.control.loop.ts",
          "keyword.control.import.js",
          "keyword.control.import.ts",
          "keyword.control.import.tsx",
          "keyword.control.from.js",
          "keyword.control.from.ts",
          "keyword.control.from.tsx",
          "keyword.operator.instanceof.js",
          "keyword.operator.expression.instanceof.ts",
          "keyword.operator.expression.instanceof.tsx",
          "support.constant",
          "support.function",
          "entity.other.attribute-name",
          "entity.other.inherited-class",
          "entity.name.function",
          "entity.name.tag.doctype",
          "entity.name.function",
          "meta.directive.vue",
          "meta.diff.header.git",
          "meta.diff.header.from-file",
          "meta.diff.header.to-file",
          "meta.var.expr",
          "meta.delimiter.period",
          "meta.selector",
          "meta.tag.sgml.doctype",
          "meta.tag.sgml.doctype.html",
          "meta.class meta.method.declaration meta.var.expr storage.type.js",
          "storage",
          "storage.type.property.js",
          "storage.type.property.ts",
          "storage.type.property.tsx",
          "source.elixir .punctuation.binary.elixir",
          "source.go keyword.package.go",
          "source.go keyword.import.go",
          "source.go keyword.function.go",
          "source.go keyword.type.go",
          "source.go keyword.struct.go",
          "source.go keyword.interface.go",
          "source.go keyword.const.go",
          "source.go keyword.var.go",
          "source.go keyword.map.go",
          "source.go keyword.channel.go",
          "source.go keyword.control.go",
          "string.quoted.docstring.multi.python",
        ],
        "settings": {
          "fontStyle": ""
        },
      },
    ],
  },
},
```


Relentless Theme created by [Micheal Andreuzza](https://github.com/michael-andreuzza).
[Twitter](https://twitter.com/Mike_Andreuzza)
