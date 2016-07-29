Installation
============
mkdir -p $HOME/.local/share/xfce4/terminal/colorschemes
cd $HOME/.local/share/xfce4/terminal/
if [ -d colorschemes/ ]; then mv colorschemes colorschemes.old; fi
git clone git@github.com:netzverweigerer/xfce4-terminal-additional-colorschemes.git
mv xfce4-terminal-additional-colorschemes colorschemes 


