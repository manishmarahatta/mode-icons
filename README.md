# Mode-icons

Show icons instead of mode names in emacs.

Modes that have icons instead of names now:

* Emacs-Lisp
* Python
* Scheme
* Lisp
* PHP
* HTML

## Installation

To install use either method:

### package.el

If you have [Emacs](http://gnu.org/software/emacs) 24 or `package.el`
installed manually you can just create the tar file and use
`package-install-file` to install it.

#### Create the tar file

Use `make dist` to create the tar file needed for `package.el`.

### manually

Place `mode-icons.el` somewhere in your `load-path` and copy the
`icons/` directory there as well.  Then `require` `mode-icons` in your
[Emacs](http://gnu.org/software/emacs) init file.
