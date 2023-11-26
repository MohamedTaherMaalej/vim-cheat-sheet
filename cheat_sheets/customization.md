# Vim Customization Cheat Sheet

## Configuration Files

- **~/.vimrc**: User-specific Vim configuration file.
- **/etc/vim/vimrc**: System-wide Vim configuration file (Linux).

## Basic Customization

### Changing Colorschemes

- **:colorscheme {name}**: Change the colorscheme.

### Setting Line Numbers

- **:set number**: Display line numbers.
- **:set nonumber**: Hide line numbers.

### Changing Tab Width

- **:set tabstop=4**: Set the tab width to 4 spaces.
- **:set expandtab**: Use spaces instead of tabs.

## Key Mapping

### Remapping Keys

- **:map {original} {new}**: Remap a key.
- **:imap {original} {new}**: Remap a key in insert mode.

### Custom Commands

- **:command MyCommand :echo "Hello, Vim!"**: Define a custom command.

## Plugins and Package Management

### Installing Plugins

1. **Pathogen**
   - Install Pathogen: `mkdir -p ~/.vim/autoload ~/.vim/bundle && curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim`
   - Add to ~/.vimrc: `execute pathogen#infect()`

2. **Vundle**
   - Install Vundle: `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
   - Add to ~/.vimrc: `call vundle#begin()`, `Plugin 'user/plugin'`, `call vundle#end()`

### Managing Plugins

- **:PluginInstall**: Install plugins with Vundle.
- **:PluginUpdate**: Update installed plugins.
- **:PluginSearch {name}**: Search for plugins.
- **:PluginClean**: Remove plugins not in the list.

## Advanced Customization

### Autocommands

- **augroup MyGroup | autocmd! | autocmd BufRead,BufNewFile *.txt set tabstop=8 | augroup END**: Set specific options for files with a certain extension.

### Creating Functionality

- **function MyFunction() | ... | endfunction**: Define a custom function.
- **:call MyFunction()**: Call the custom function.

### Using Variables

- **:let g:my_variable = "value"**: Set a global variable.
- **:echo g:my_variable**: Display the value of the global variable.

Customizing Vim allows you to tailor the editor to your specific needs. Experiment with these customization options to create a comfortable and efficient editing environment.
