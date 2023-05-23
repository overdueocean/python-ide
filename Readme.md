## Jedi-Vim :

#Install dependencies:
sudo apt install git curl python3-pip exuberant-ctags ack-grep
sudo pip3 install pynvim flake8 pylint isort jedi

https://github.com/davidhalter/jedi-vim

git clone --recursive https://github.com/davidhalter/jedi-vim.git ~/.vim/bundle/jedi-vim

# Run the following command to update the repo on macos:
git submodule update --init --recursive
