dotfiles.git
============
Clone and run to configure your `bash` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/dreggz/dotfiles.git
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```
If all goes well, in addition to a more useful prompt, now you can
do `emacs -nw hello.js` and hitting `C-c!` to launch an interactive SSJS
REPL, among many other features.  

Tested and working on:
- [x] Ubuntu 12.04.2 LTS (EC2 instance)
- [x] Mint 15 (VirtualBox 4.2.12 r84980)  

See http://github.com/dreggz/ubuntu-setup to install prerequisite
programs and [Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index) for more details.
