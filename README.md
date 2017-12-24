# Configuration

[see configuration.org](configuration.org)

# dependencies

* [mu](https://www.djcbsoftware.nl/code/mu/)
* [offlineimap](http://www.offlineimap.org/)
* [pandoc](http://pandoc.org/)
* [js-beautify](https://github.com/beautify-web/js-beautify)

# Installation:

```
$ cd ~/git 
$ git clone http://github.com/pascalhuber/emacs
$ ln -s ~/git/emacs ~/.emacs.d
```

get mu4e ready
```
$ sudo pacman -S offlineimap 
$ pacaur -S mu
$ mu index --maildir=~/.mail
```

(Re)compile the modeline with `M-x spaceline-compile`.

Python:
```
$ sudo pacman -S python-pip python-virtualenv python2-virtualenv
$ pip install --user jedi flake8 autopep8 yapf
$ mkdir $WORKON_HOME
```
