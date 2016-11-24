# Djangoiv-theme

## Installation

Download djangoliv-theme.el to the directory ~/.emacs.d/themes/. Add this to your .emacs:
``` emacs-lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

Now you can load the theme with the interactive function load-theme like this:
```
M-x load-theme RET djangoliv
```

To load it automatically on Emacs startup add this to your init file:
``` emacs-lisp
(load-theme 'djangoliv t)
```
