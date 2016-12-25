# company-erlang

[![License GPL 3](https://img.shields.io/badge/license-GPL_3-green.svg)](http://www.gnu.org/licenses/gpl-3.0.txt)

`company-erlang` is company backend for erlang based on
[`ivy-erlang-complete`](https://github.com/s-kostyaev/ivy-erlang-complete).
[![MELPA](https://melpa.org/packages/company-erlang-badge.svg)](https://melpa.org/#/company-erlang)

## Setup
Add this in your init file:
``` emacs-lisp
(add-hook 'erlang-mode-hook #'company-erlang-init)
```

