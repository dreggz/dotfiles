dotfiles.git
============
See [http://github.com/dreggz/ubuntu-setup](http://github.com/dreggz/ubuntu-setup) for headless install of this script and prerequisite
programs.

Or, clone and manually configure your `bash` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/dreggz/dotfiles.git
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
ln -sb dotfiles/.inputrc .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```

Tested and working on:
- [x] Ubuntu 12.04.2 LTS (EC2 instance)
- [x] Mint 15 (VirtualBox 4.2.12 r84980)  

More info at: [dotfiles.github.io](http://dotfiles.github.io/)  & [Stanford Startup Engineering video lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
