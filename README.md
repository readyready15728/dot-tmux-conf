# dot-tmux-conf
## .tmux.conf and any ancillary files (if needed)

So far it's just `.tmux.conf` but there again I just got started. `.tmux.conf` is obviously meant to be copied or linked to `$HOME` but there is a further matter to take care of. As described in the documentation for [tmux Plugin Manager](https://github.com/tmux-plugins/tpm), it is necessary to install TPM like so: 

```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Additionally, it will be necessary to type `<prefix>` + `I` from within `tmux` to install plugins. Questions about the functionality of the plugins are best resolved by their respective Markdown pages.
