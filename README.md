Cloned and updated http://sourceforge.net/projects/jdee/trunk (without web dir).

# Building #
1. git clone git@github.com:pwojnowski/jdee.git
2. cd jdee
3. ant bindist

# Emacs configuration
```emacs-lisp
(setq jde-dir "/path/to/jdee/dist/jdee-2.4.2/lisp")
(add-to-list 'load-path jde-dir)
(load "jde-autoload")
```
