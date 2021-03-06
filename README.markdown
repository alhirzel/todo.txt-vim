### Quick install

    git clone git://github.com/freitass/todo.txt-vim.git
    cd todo.txt-vim
    cp -R * ~/.vim


This plugin gives syntax highlighting to [todo.txt](http://todotxt.com/) files. It also defines a few
mappings, to help with editing these files:

`<leader>-s` : Sort the file

`<leader>-s+` : Sort the file on +Projects

`<leader>-s@` : Sort the file on @Contexts

`<leader>-j` : Lower the priority (cursor must by on priority)

`<leader>-k` : Increase the priority (cursor must by on priority)

`<leader>-d` : Insert the current date

`date<tab>`  : (Insert mode) Insert the current date

`<leader>-x` : Mark task as done (inserts current date as completion date)

`<leader>-X` : Mark all tasks as completed

`<leader>-D` : Remove completed tasks

If you want the help installed, run ":helptags ~/.vim/doc" inside vim after having copied the files.
Then you will be able to get the commands help with: :h todo.txt
