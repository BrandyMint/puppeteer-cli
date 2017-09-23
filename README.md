# Puppeteer Webshot CLI [![npm version](http://img.shields.io/npm/v/puppeteer-webshot-cli.svg?style=flat-square)](https://www.npmjs.org/package/puppeteer-webshot-cli)

> Easy website screenshots in CLI with headless Chrome using Puppeteer.


```
Usage: puppeteer-webshot-cli --url=https://example.com

Options:
  --help      Show help                                                [boolean]
  --version   Show version number                                      [boolean]
  --width     Width of viewport
  --height    Height of viewport
  --fullPage  When true, takes a screenshot of the full scrollable page.
              Defaults to true.                                  [default: true]
  --out       File path to save. If `-` specified, outputs to console in
              base64-encoded                                      [default: "-"]
  --debug     Print dimensions information                      [default: false]
  --delay     Delay to save screenshot after loading CSS. Milliseconds
  --css       Additional CSS URL to load
  --style     Additional style to apply to body
  --url                                                               [required]
```
