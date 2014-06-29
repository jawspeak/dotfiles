dotfiles
========

Installation:

```
git clone git@github.com:jawspeak/dotfiles.git
ln -s `pwd`/dotfiles/.gitconfig ~/.gitconfig
ln -s `pwd`/dotfiles/.bash_aliases ~/.bash_aliases

echo "" >> ~/.bashrc
echo "# sourcing my aliases (jaw)" >> ~/.bashrc
echo "source ~/.bash_aliases" >> ~/.bashrc
```


Also, for mac, use https://github.com/square/maximum-awesome.
