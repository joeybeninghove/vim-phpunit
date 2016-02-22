vim-phpunit
===========

Run phpunit tests using vim :D

## Setup (manually)

```
git clone https://github.com/joeybeninghove/vim-phpunit.git ~/.vim/bundle/vim-phpunit
```

## Setup (using Vundle)

Add this to your Vundle file:

`Plugin 'joeybeninghove/vim-phpunit'`

## Leader Mappings

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
