Fortify Highlighter
====

Syntax Highlighter for Fortify Rulepacks and NST files

INSTALL
====

1.  Install [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
1.  Open command palette `ctrl-shift-p` then `Install Package`
1.  Search for `Fortify Highlighter`
1.  Enjoy :)

FEATURES
====
*  Highlights:
** Fortify Rulepacks
** Structural Language
** Definition Blocks
** NST files

NOTES
====
*  The Syntax files are improved for [Cobalt2 Theme](https://github.com/wesbos/cobalt2)
*  If Sytax is not automatically enabled, use command palette `ctrl-shift-p` then `Set Syntax: Fortify xxxx`

CONTRIBUTE
====

Submit patches to the .JSON-tmLanguage files, not the xml files which are generated from them.

Build `tmLanguage`files with `AAAPackageDev`(install with package control, set Build System to `Convert To` in `Tools` and generate PList files). When submitting patches, please submit a sample code to exercise the syntax highlight.
