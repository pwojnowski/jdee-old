Clone of http://sourceforge.net/projects/jdee/trunk (without web dir).

# Building #
git clone git@github.com:pwojnowski/jdee.git
cd jdee
ant bindist

# Emacs configuration
```Emacs Lisp
(setq jde-dir "/path/to/jdee/dist/jdee-2.4.2/lisp")
(add-to-list 'load-path jde-dir)
(load "jde-autoload")
```
