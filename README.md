# vs_code_configuration
Visual Studio Code configuration files

To use, run the following (exact path may need to be adjusted based on your specific environment):

Move the current settings.json file away:
```
mv ~/.config/Code/User/settings.json ~/.config/Code/User/settings_old.json
```

Add a symlink to the settings.json file in this repository:
```
ln -s <path_to_this_repo>/vs_code_configuration/settings.json ~/.config/Code/User/settings.json 
```
