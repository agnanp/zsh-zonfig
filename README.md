# My zsh config
1. Install Neovim
   ``` bash
   curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
   sudo rm -rf /opt/nvim
   sudo tar -C /opt -xzf nvim-linux64.tar.gz
   ```
   
3. Install Nerd Font
   - Download a [Nerd Font](http://nerdfonts.com/)
   - sudo apt install fontconfig
   - Unzip and copy to `~/.fonts`
   - fc-cache -fv
  
4. Install fzf
   ``` bash
   git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
   ~/.fzf/install 
   ```
