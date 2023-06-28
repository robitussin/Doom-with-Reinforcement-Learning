# Instructions

## When running in Google Collab
1. Upload basic.cfg and basic.wad in the runtime environment.
2. Add "game.set_window_visible(False)" in the create_environment() method.

## When running in VS Code/PyCharm
1. Put all game files, assets and the python notebook in one folder
2. Remove "game.set_window_visible(False)" in the create_environment() method.
3. Omit all install commands specific for Google Collab
4. If you have a CUDA enabled GPU, add the command below.

print(len(tf.config.list_physical_devices('GPU')) > 0)
