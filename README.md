# Markdown

Markdown parser for Io. Based on [discount](https://github.com/Orc/discount).

## Installation

Using [eerie](https://github.com/AlesTsurko/eerie):

```
eerie install https://github.com/AlesTsurko/Markdown.git
```

## Usage

```Io
Markdown

"# Hello" markdownToHTML // will return <h1>Hello</h1>
```

## Tests

`OUTPUT.html` have been generated with the next command (using `markdown` from [discount](https://github.com/Orc/discount)):

```
markdown -oOUTPUT.html -fnopants,fencedcode,githubtags,urlencodedanchor TEST.md
```

The `TEST.md` is from this repository: [https://github.com/mxstbr/markdown-test-file](https://github.com/mxstbr/markdown-test-file)

To run tests `cd` in the `Markdown` and run:

```
jasmineio
```
