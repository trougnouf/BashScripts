# BashScripts
toggleKeyboards can toggle keyboards on and off.
The default behavior is to look for all keyboards and toggle them.
If one or more parameter is specified, only what matches the given string(s) will be toggled (eg: ./toggleKeyboards G710)
A list of keyboard names can be found under "xinput --list | awk '/slave/ && /keyboard/'"
