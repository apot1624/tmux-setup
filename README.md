# tmux-setup
tmux configuration setup

## 执行 x tmux --setup 即可快速应用简约主题，并同步开启鼠标窗格控制功能。 
```bash
x tmux --setup
```

## 先手动安装插件管理器tpm
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## tpm Key bindings
`prefix` + <kbd>I</kbd>
- Installs new plugins from GitHub or any other git repository
- Refreshes TMUX environment

`prefix` + <kbd>U</kbd>
- updates plugin(s)

`prefix` + <kbd>alt</kbd> + <kbd>u</kbd>
- remove/uninstall plugins not on the plugin list
