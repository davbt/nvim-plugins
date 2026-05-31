# nvim-plugins
Plugins as submodules.

Also see [nvim-config](https://github.com/davbt/nvim-config) for full setup script.

Add submodule:
```bash
git submodule add https://github.com/random/<some-plugin>.git start/<some-plugin>
cd start/<some-plugin>
git checkout <some-commit>
```

Remove submodule:
```bash
git rm start/<some-plugin>
rm -r .git/modules/start/<some-plugin>
git config --remove-section submodule.start/<some-plugin>
```

