# tmux-setup
tmux configuration setup

## 先手动安装插件管理器tpm
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## Deploy configuration files
```bash
git clone https://github.com/apot1624/tmux-setup.git /tmp/tmux-setup
cp ~/.tmux.conf ~/.tmux.conf.bak
cp /tmp/tmux-setup/.tmux.conf ~
cp /tmp/tmux-setup/.tmux.conf.plugins ~
rm -r /tmp/tmux-setup
```

## Install plugins
`prefix` + <kbd>I</kbd>
- Installs new plugins from GitHub or any other git repository
- Refreshes TMUX environment

`prefix` + <kbd>U</kbd>
- updates plugin(s)

`prefix` + <kbd>alt</kbd> + <kbd>u</kbd>
- remove/uninstall plugins not on the plugin list

## 快速应用简约主题，并同步开启鼠标窗格控制功能。 
```bash
x tmux --setup
```
