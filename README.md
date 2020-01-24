vs-snippets
===========

This repository contains VSCode's snippets files for various programming languages.

Install:
--------

### If you use vim/neovim

```vim
dein#add('hrsh7th/vim-vsnip')
dein#add('kitagry/vs-snippets')

let g:vsnip_snippet_dirs = split(globpath(&runtimepath, 'snippets'), '\n')
```

License:
--------

MIT

This plugin complies with following plugins lisense(MIT)

- [microsoft/vscode](https://github.com/microsoft/vscode)
- [microsoft/vscode-go](https://github.com/microsoft/vscode-go)
- [microsoft/vscode-python](https://github.com/microsoft/vscode-python)
- [editor-rs/vscode-rust](https://github.com/editor-rs/vscode-rust)
- [rubyide/vscode-ruby](https://github.com/rubyide/vscode-ruby)

Author:
-------

Ryo Kitagawa
