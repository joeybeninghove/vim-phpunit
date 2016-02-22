vim-phpunit
===========

Run phpunit tests using vim :D

## Setup (using Vundle)

Add this to your Vundle file:

`Plugin 'joeybeninghove/vim-phpunit'`

Add this to your .vimrc:

```
" phpunit shortcuts
map <Leader>u :call RunCurrentTest()<CR>
map <Leader>uf :call RunCurrentTestFile()<CR>
map <Leader>ua :call RunAllTests()<CR>
```

## Use

Inside vim:

> Type Leader + u to run the current test.

> Type Leader + uf to run the current test file.

> Type Leader + ua to run all the tests in the entire project.

Enjoy :heart:
