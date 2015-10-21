# Minimal Emacs Config

Pretty minimal Emacs configuration as discussed in the CUGB's Emacs workshop series.
For a more complete setup, see [dotemacs](https://github.com/hemmvm/dotemacs).

## Install
Clone the repo and create a symlink
```bash
git clone https://github.com/hemmvm/dotemacs-starter.git
ln -s dotemacs-starter ~/.emacs.d
```

## Migration

Initially, you might want to switch back and forth between your new
configuration and the existing one (i.e. `~/emacs.d`).

You can make Emacs temporarily use another configuration by adjusting the process' environment, e.g.:
```bash
HOME=~/repos/dotemacs-starter emacs .
```

## License
MIT
