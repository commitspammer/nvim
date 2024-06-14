# nvim

because i'm tired of reconfiguring nvim from scratch

simply follow these steps:

1. install nvim 0.9.5
- cuz it's the version i use
- and cuz telescope requires at least 0.7.0
- idk about the other plugins tho, might require even higher
- also, ik nvim 0.10.0+ exists, but i haven't tested that
- if you downloaded a tar.gz, dont forget to add it to $PATH

2. install packer:
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

3. clone this repo inside `~/.config`

4. open nvim, ignore all errors, run `:PackerSync`, restart nvim

5. profit
