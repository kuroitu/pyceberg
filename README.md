Pyceberg is a few customized
[iceberg](https://github.com/cocopon/iceberg.vim)
for python.

![Screenshot](https://github.com/kuroitu/images/blob/master/screenshot1.png)
![Screenshot](https://github.com/kuroitu/images/blob/master/screenshot2.png)

See the [official site](https://cocopon.github.io/iceberg.vim/) or the
[vimonline page](https://www.vim.org/scripts/script.php?script_id=4820) for more information.

# Usage
If you have
[neobundle](https://github.com/Shougo/neobundle.vim)
, write your .vimrc as follow:

    NeoBundle('kuroitu/pyceberg')
    colorscheme pyceberg

also you have
[dein](https://github.com/Shougo/dein.vim)
, write your .vimrc as follow:

    call dein#add('kuroitu/pyceberg')
    colorscheme pyceberg

other way, if you use 'vim' then

    $ git clone 'https://github.com/kuroitu/pyceberg'
    $ mkdir ~/.vim/colors
    $ mv pyceberg/colors/pyceberg.vim ~/.vim/colors/

or use 'neovim' then

    $ git clone 'https://github.com/kuroitu/pyceberg'
    $ mkdir ~/.config/nvim/colors
    $ mv pyceberg/colors/pyceberg.vim ~/.config/nvim/colors

and write your .vimrc as mentioned above.

In any cases, if you get an error like 'pyceberg not found', rename the main file it may name 'iceberg.vim' in colors to 'pyceberg.vim'.

# License
MIT License. See `LICENSE.txt` for more information.
