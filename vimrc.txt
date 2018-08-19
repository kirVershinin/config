set tabstop=4
set softtabstop=4
set shiftwidth=4
set textwidth=79
set expandtab
set autoindent
set encoding=utf-8
set fileformat=unix
set linebreak 
set autoread
set ruler

autocmd FileType python setlocal textwidth=79 formatoptions+=t
autocmd FileType js setlocal tabstop=2 softtabstop=2 shiftwidth=2
autocmd FileType html setlocal tabstop=2 softtabstop=2 shiftwidth=2
autocmd FileType css setlocal tabstop=2 softtabstop=2 shiftwidth=2

colo ron
syntax on
    
filetype on
filetype plugin on
filetype indent on

highlight link htmlLink text
highlight link htmlTag htmlTagName
highlight link htmlEndTag htmlTagName
highlight Comment ctermfg=grey cterm=italic
highlight Statement ctermfg=3  
highlight PreProc ctermfg=110
highlight Type ctermfg=115
highlight Identifier ctermfg=185
highlight Special ctermfg=185
highlight Constant ctermfg=13
highlight Operator ctermfg=3

highlight pythonAsync ctermfg=115
"highlight pythonAttribute ctermfg=115
highlight pythonBuiltin ctermfg=3
highlight pythonComment ctermfg=grey cterm=italic
highlight pythonConditional ctermfg=3
highlight pythonDecorator ctermfg=115
highlight pythonDecoratorName ctermfg=3
"highlight pythonDoctest ctermfg=115
"highlight pythonDocttestValue ctermfg=115
"highlight pythonEscape ctermfg=115
"highlight pythonException ctermfg=115
"highlight pythonExceptions ctermfg=115
highlight pythonFunction ctermfg=115
highlight pythonInclude ctermfg=3
highlight pythonNumber ctermfg=3
highlight pythonOperator ctermfg=3
highlight pythonQuotes ctermfg=110
highlight pythonRawString ctermfg=115
highlight pythonStatement ctermfg=222
highlight pythonString ctermfg=110
"highlight pythonSync ctermfg=115
highlight pythonTripeQuotes ctermfg=110



"let python_highlight_all = 1
