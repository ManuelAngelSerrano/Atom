# Atom

My Atom.io Config

You can download Atom Editor from http://atom.io

You need to install these packages:

+ atom-monokai
+ file-icons
+ jump-to-line
+ jumpy
+ language-latex
+ latexer
+ markdown-writer
+ minimap
+ monokai
+ relative-numbers (Mark also: Show absolute numbers)
+ swackets (Mark All - Rainbow parens)
+ tidy-markdown
+ vim-mode-plus
+ vim-mode-plus-ex-mode
+ vim-mode-plus-keymaps-forsurround

And config keymap.cson with:
~~~
'atom-text-editor.vim-mode-plus.normal-mode':
  ', b': 'fuzzy-finder:toggle-buffer-finder'
  ', f': 'fuzzy-finder:toggle-file-finder'
  ', p': 'command-palette:toggle'
  ', t': 'command-palette:toggle'
  ', w': 'core:save'
  ', q': 'core:close'
  ', , q': 'application:quit'
  ', .': 'vim-mode-plus-ex-mode:open' #'ex-mode:open'
  ', e': 'application:open'
  ', s': 'vim-mode:search'
  ', S': 'vim-mode:reverse-search'
  ', , j': 'jump-to-line:start'
  ', , k': 'jump-to-line:start'
  ', , f': 'jumpy:toggle'
  ', , F': 'jumpy:toggle'
  ', , t': 'jumpy:toggle'
  ', , T': 'jumpy:toggle'
  ', , w': 'jumpy:toggle'
  ', c i': 'editor:toggle-line-comments'
  ', v': 'editor:toggle-soft-wrap'
  'U': 'vim-mode-plus:redo'  
~~~

Last you need to need to set
+ UI Theme: One Dark
+ Syntax Theme: Monokai
