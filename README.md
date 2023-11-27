Thanks for using my Automatic Layer Enums! I hope it serves you well.

This plugin is configured to generate enums for all types of layers including
physics, render, navigation, and avoidance.

To run the plugin and generate enums, go to Project/Tools/Layer Enums/ and click
on one of the generation options. By default, new .gd files will be generated in
res://generated/enum/

Custom configuration is not necessary but may be desired.
To configure the output of the generator, please edit plugin_options.cfg

"name" is what will appear in the drop-down
"script" is the absolute path the enum will be generated at
"class_name" will be assigned to the script for global access
"enum_name" is what the enum property will be named
"project_setting" is the layers setting to pull layer name values from
"max_count" is how many layers at most are available in project settings

After editing plugin_options.cfg, disable then re-enable Automatic Layer Enums
from Project/Project Settings/Plugins to apply the changes.

- award
- adamwardell@gmail.com
