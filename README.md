# Project Scaffolding

The dotfiles contain some common scaffolding such as indentation and whitespace settings, ignored files, and so on. The only thing worth mentioning here is that we have to set line endings to LF for all bash scripts, otherwise, if you save a script on Windows, it would have CRLF line breaks, which doesn’t work on Linux. This is achieved by a combination of ‘.editorconfig’ defining how the code is displayed in a text editor, and ‘.gitatttributes’, which controls how the file is saved in source control.
