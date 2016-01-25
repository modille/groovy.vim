groovy.vim
==========

Custom vim indenting and syntax highlighting for Groovy

Indent
------

Copied from http://www.vim.org/scripts/script.php?script_id=2961 and then `s/^M$//`

Syntax
------

A fork of `groovy.vim` (taken from the neovim project), with the following changes:

- Annotations are matched and highlighted as `PreProc` (similar to `java.vim`)
- Match `/* comment blocks */` as `Comment` instead of `groovyString`
- Don't treat division operator (`/`) as start of regex
