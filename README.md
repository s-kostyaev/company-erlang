# company-erlang

[![License GPL 3](https://img.shields.io/badge/license-GPL_3-green.svg)](http://www.gnu.org/licenses/gpl-3.0.txt)
[![MELPA](https://melpa.org/packages/company-erlang-badge.svg)](https://melpa.org/#/company-erlang)
[![MELPA Stable](https://stable.melpa.org/packages/company-erlang-badge.svg)](https://stable.melpa.org/#/company-erlang)


`company-erlang` is company backend for erlang based on
[`ivy-erlang-complete`](https://github.com/s-kostyaev/ivy-erlang-complete).

## Setup
Add this in your init file:
``` emacs-lisp
(add-hook 'erlang-mode-hook #'company-erlang-init)
```

