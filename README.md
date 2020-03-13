# vim-setup

vim setup with JS autocomplete 

## Setup steps

1. Setup [vim-plug](https://github.com/junegunn/vim-plug) to manage vim pluggins
2. Create `~/.vimrc` and insert everything inside the [`.vimrc` file](https://github.com/valdio/vim-setup/blob/master/.vimrc) in this repo
3. Create `~/.tern-config` for better JavaScript suggestions and add the content of [`.tern-config` file](https://github.com/valdio/vim-setup/blob/master/.tern-config)
4. Enter `vim` again and install pluggins using `: PlugInstall`
5. All DONE  :tada:

## Perks

- Setup with scroll support form mouse/touch pad
- Auto linting on save enabled

## Short commands
 
 - **`<leader>`** is set to SPACE
 
 - **`+`** is just a combination character. Emit it when running commands.
 
 - **Upercase** letters are considered as keypress **`Shift+letter`**

---------------------------------------------------------------------------------


|    Commands    |      Description      |
|----------------|:---------------------:|
| `v`            | start text select     |
| `<leader>`     | starts text search    |
| `shift+v`      | select entire line    |
| `ctrl+v`       | select column         |
| `u`            | undo                  |
| `ctrl+r`       | redo                  |
| `<leader>q`    | quit current split without saving|
| `<leader>Q`    | quit ALL without saving|
| `<leader>+L`   | auto fix linting issues |
| `<leader>+f`   | file search in current path |
| `:Files /optional_path or .`   | file search in current path |
| `<leader>+r`   | show NerdTree side navigator |
| `i`(on sidebar)| view file on horizontal split |
| `s`(on sidebar)| view file on vertical split |
| `t`(on sidebar)| view file new tab |
|      `nn`      | navigate on next split/window |
|`<leader><Up>`(Arrow)| navigate to UP split/window |
|`<leader><Down>`(Arrow)| navigate to DOWN split/window |
|`<leader><Left>`(Arrow)| navigate to LEFT split/window |
|`<leader><Right>`(Arrow)| navigate to RIGHT split/window |
