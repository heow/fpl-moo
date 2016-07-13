
# fpl-moo

## MOO Client for Emacs


``` elisp
;; fpl-moo.el
;; Version: 1.1.22
;; Author: Francis Litterio (franl@world.std.com)
;;
;; This package is a MOO client for Emacs.  This package works fine in Emacs
;; version 20.4, but I don't know if it still works in version 19.  Let me know
;; if you have problems using this package in version 19.
;;
;; INSTALLATION INSTRUCTIONS:
;;
;; This package is based on fpl-react.el, so you must download that package as
;; well (it may have been included with this file in whatever archive you got
;; this file in).  Put both fpl-moo.el and fpl-react.el in some directory (I'll
;; call it ELISPDIR here), and add this code to your .emacs startup file:
;;
;; (setq load-path (append load-path '("/path/to/ELISPDIR")))
;; (require 'fpl-moo)
```

Then just use **M-x fpl-moo-connect**, tab-completion is supported so **L\<TAB\>** will connect to LambdaMOO.  

Happy Mooing!
