# Pandoc Plugin for Sublime Text

A [Sublime Text](http://www.sublimetext.com/) plugin that uses [Pandoc](http://johnmacfarlane.net/pandoc/) to convert text from one markup format into another. Pandoc can convert documents in markdown, reStructuredText, textile, HTML, DocBook, LaTeX, MediaWiki markup, TWiki markup, OPML, Emacs Org-Mode, Txt2Tags, Microsoft Word docx, LibreOffice ODT, EPUB, or Haddock markup to XHTML, HTML5, HTML slide shows using Slidy, reveal.js, Slideous, S5, or DZSlides, Microsoft Word docx, OpenOffice/LibreOffice ODT, OpenDocument XML, EPUB version 2 or 3, FictionBook2, DocBook, TEI Simple, GNU TexInfo, Groff man pages, Haddock markup, InDesign ICML, OPML, LaTeX, ConTeXt, LaTeX Beamer slides, PDF via LaTeX, Markdown (including CommonMark), reStructuredText, AsciiDoc, MediaWiki markup, DokuWiki markup, Emacs Org-Mode, Textile, or custom writers can be written in lua.

## Installation

You need to [install Pandoc](http://johnmacfarlane.net/pandoc/installing.html), and this module:

-	[Using the Package Control plugin](https://sublime.wbond.net/installation).
-	Manually, either download or checkout this repository and [install into your packages directory](http://docs.sublimetext.info/en/latest/extensibility/packages.html#package-installation)

For Sublime Text 2, use the 1.x branch.

## Usage

The input format is specified by setting the syntax of the document.

Run Pandoc on the current document via the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows) by selecting "Pandoc". You will be presented with output formats to choose from.

## Configure

You can fully configure the available formats, and configure the Pandoc options to customize transformation, via the [plugin settings file](http://docs.sublimetext.info/en/latest/customization/settings.html). Via the application menu, go to "Preferences" -> "Package Settings" -> "Pandoc".

There are 2 possible top level settings keys, "user" and "default". If you use "default" in your user settings file, the default settings will be overwritten, but if you use "user" your settings will be merged into the default settings.
