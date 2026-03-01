# nvim-plugins

Plugins as submodules at specific commit hashes:

Setup:
```bash
git clone git@github.com:davbt/nvim-config.git $HOME/.config/nvim-plugins
```
Add submodule:
```bash
git add submodule https://github.com/random/<some-plugin>.git start/<some-plugin>
```

Remove submodule:
```bash
git rm start/cool-plugin.nvim
rm -rf .git/modules/start/cool-plugin.nvim
git config --remove-section submodule.start/cool-plugin.nvim
```

