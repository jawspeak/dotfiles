dotfiles
========

Installation:

```
git clone git@github.com:jawspeak/dotfiles.git
ln -s dotfiles/.gitconfig ~/.gitconfig
ln -s dotfiles/.bash_aliases ~/.bash_aliases

echo "" >> ~/.bashrc
echo "# sourcing my aliases (jaw)" >> ~/.bashrc
echo "source ~./bash_aliases" >> ~/.bashrc
```
