# dot-nvchad

rm -rf ~/.config/nvim && git clone https://github.com/phucvinh52/dot-nvchad.git ~/.config/nvim && nvim
## apt upgrade (required from termux) 
```
apt upgrade
pkg install lua-language-server
```

# remove .local/share/nvim if reach error
```
rm -rf ~/.local/share/nvim
```

# for rust 2 tab
```
mkdir -p ~/.config/rustfmt
touch ~/.config/rustfmt/rustfmt.toml
echo -e "\ntab_spaces = 2" >> ~/.config/rustfmt/rustfmt.toml
cargo fmt
``` 
