## tmux-screen-compat

This is a config for tmux that tries to make it behave like screen.

These are bindings that I use, and I believe are common for screen users with a
mostly default config, you may be using other screen bindings I did not add, if
so, please send me a pull request!

## installation

```bash
mkdir ~/src
cd ~/src
git clone https://github.com/rkitover/tmux-screen-compat.git
cd tmux-screen-compat
(echo 'source-file ~/src/tmux-screen-compat/.tmux.conf'; \
	cat ~/.tmux.conf 2>/dev/null) > tmux.conf
mv tmux.conf ~/.tmux.conf
```

On Mac OS X make sure you have `reattach-to-user-namespace` installed, you can
install it from [brew](http://brew.sh).
