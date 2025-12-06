[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/quick-peek.svg)](https://jcs-emacs.github.io/jcs-elpa/#/quick-peek)

# quick-peek

[![CI](https://github.com/emacs-vs/quick-peek/actions/workflows/test.yml/badge.svg)](https://github.com/emacs-vs/quick-peek/actions/workflows/test.yml)

![](etc/screencast.gif)

An inline pop-up library for Emacs Lisp.

## 🔌 API

See the docstrings of `quick-peek-show` and `quick-peek-hide`.

Complex programs may need to use the lower-level `quick-peek-overlay-ensure-at`, `quick-peek-overlay-contents`, and `quick-peek-overlay-update` methods.

## 🧪 Customization

See docstrings of `quick-peek-background-face`, `quick-peek-border-face`, and
`quick-peek-padding-face`.

## ✏️ Changes

![](etc/vs.png)

## 🛠️ Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple?logo=gnuemacs&logoColor=white)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!

### 🔬 Development

To run the test locally, you will need the following tools:

- [Eask](https://emacs-eask.github.io/)
- [Make](https://www.gnu.org/software/make/) (optional)

Install all dependencies and development dependencies:

```sh
eask install-deps --dev
```

To test the package's installation:

```sh
eask package
eask install
```

To test compilation:

```sh
eask compile
```

**🪧 The following steps are optional, but we recommend you follow these lint results!**

The built-in `checkdoc` linter:

```sh
eask lint checkdoc
```

The standard `package` linter:

```sh
eask lint package
```

*📝 P.S. For more information, find the Eask manual at https://emacs-eask.github.io/.*

## ⚜️ License

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

See [`LICENSE`](./LICENSE.txt) for details.
