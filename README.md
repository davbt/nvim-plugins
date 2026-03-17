# nvim-plugins

Also see [nvim-config](https://github.com/davbt/nvim-config) for full setup script.

Plugins as submodules at specific commit hashes:

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

