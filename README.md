# .dotfiles

1. Clone this repository
2. Run `install.sh`
3. Open up new window to initiate `zsh` shell
4. 
```sh
#Install node
nvm install 14

# install lsp
npm i -g \
		  vscode-langservers-extracted \
		  cssmodules-language-server \
		  dockerfile-language-server-nodejs \
		  stylelint-lsp \
		  @tailwindcss/language-server \
		  typescript \
		  typescript-language-server
```

## Current issues

- installing `nvim` plugins in `--headless` causes error output, but doesn't break installation
- Would like to improve the install script
- Handle installation on different OS (MacOS, Linux, WSL2)

### Future optimizations

- Improve install script by automating step 3 above, initializing the `zsh` environment
