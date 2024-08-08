# nvim-config
nvim config suited for FE development with React, TS, tailwind, etc.

List of plugins available in lua/napvlm/packer.lua

Preview:
iTerm2 with custom settings + Nerd Hack font + onedarkpro theme for vim
<img width="1194" alt="Screenshot 2023-11-19 at 12 39 05 PM" src="https://github.com/napvlm/nvim-config/assets/39429876/26ed6967-c29a-440b-b104-5a4985e67936">


Installation:
- Install nvim with HomeBrew: ```brew install nvim```
- Copy repo into: ```~/.config/``` folder under name "nvim"
- Install packer from here: https://github.com/wbthomason/packer.nvim?tab=readme-ov-file#quickstart
- **Install ripgrep so Telescope search can ignore stuff from ```.gitignore``` (e.g. ```node_modules```)**
- Go inside ```/nvim``` folder and open nvim: ```nvim .```
- Ignore bunch of errors pressing "Enter" (they are popping up since plguins aren't installed yet but required in other config files)
- Go to ```/Users/RBIRA027/.config/nvim/lua/napvlm/packer.lua```
- Type ```:so``` then ```:PackerSync```
- Restart nvim and enjoy your new lightweight code editor :)
