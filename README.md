# Joseph's Dotfoles
*dotfiles repo compatible with gnu stow*
- Consider the prerequisites section to ensure Non breaking changes
- Dotfiles included are indexed below
- Usage is detailed below

## Usage

### first run
1. install git stow and git
2. set up git credentials
3. git clone the repo into local folder in home directory
	```
	$ git clone git@github.com:jabby123321/dotfiles.git
	```
4. run
	```
	$ stow --ignore * .
	```

### sync from remote repo
1. pull the remote repo
	```
	$ git pull origin master
	```
2. nothing!!! git stow uses symbolic links the changes should already be in effect

### Sync to the remote repo
1. git push to the remote repo
	```
	$ git push -u -f origin Master 
	```

## Prerequisites
the following prerequisites are highly recomended
- A nerdfont set as terminal default font or use jetbrains mono nerdfort and use alacritty
- If using ZSH then ensure that starship, bat and Exa are installed

## Dotfiles Included
*dotfiles are included to configure the following services, programmes and tools*

### Alacritty
Alacritty terminal behaviours and themes

### Bacon
Bacon prefs.toml

### Cargo
Rust cargo config

### Starship
Starship prompt settings and configuration 

### VSCodium
VSCodium use settings

### ZSH
Z shell aliases aliases configurations and behaviours
