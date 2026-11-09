# Use configs

Map the config files to the ones expected by the programs:

```bash
mkdir -p ~/.config/fish/functions

ln -sfn "$PWD/fish_prompt.fish" ~/.config/fish/functions/fish_prompt.fish
ln -sfn "$PWD/fish_right_prompt.fish" ~/.config/fish/functions/fish_right_prompt.fish"

ln -sfn "$PWD/settings.json" ~/.config/Code/User/settings.json
ln -sfn "$PWD/keybindings.json" ~/.config/Code/User/keybindings.json
```
