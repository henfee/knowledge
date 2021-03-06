# [Sublime text](https://www.sublimetext.com)
Use this editor in addition to VS Code and Neovim for its blazing fast speed of opening files.

I use it primarily to edit markdown files like [this wiki](../other/wiki-workflow.md). I also edit config files and open large and small files for quick edits.

I use [Ayu theme](https://github.com/dempfi/ayu).

## Packages I use
- [Six](https://github.com/guillermooo/Six) - Vim plugin that is genuinely amazing.
- [SendCode](https://Sgithub.com/randy3k/SendCode)
- [Text Git](https://github.com/kemayo/sublime-text-git)

## Interesting
- [Linter flake8](https://github.com/SublimeLinter/SublimeLinter-flake8)

## Notes
- Entering into sublime console (View -> Show Console):
	- `sublime.log_commands(True)`
	- `sublime.log_input(True)` - Allows you to then see what commands you type as well as actions you make map to as sublime bindings.
	- You can then turn all logging by running commands above with `False` or restart Sublime.
- `New view into file` will split current file into two tabs.