# Post-Modern Helix Editor Configuration (config.toml)
A post-modern Helix editor configuration (config.toml) for new users, because everything old is new again.

## Introduction

The settings in this config help new users avoid some problems and show how to configure Helix editor with useful examples.

Notably, this config maps `esc` key to reset Helix to default state of:
- normal mode
- single cursor
- not having multiple chars selected.

This post-modern `esc` key shortcut is helpful to new users and reviewers. See:
- https://github.com/helix-editor/helix/pull/5289
- https://www.youtube.com/watch?v=8L308PdmhMY&t=887s

Some advanced Helix users dislike the post-modern `esc` key shortcut.  They prefer to use distinct keys (extra steps) to escape back to fully default state.  Each way has its pros and cons, with this post-modern config being easier for new users.

### Instructions:

#### Linux, macOS, *BSD
Copy this file to ~/.config/helix/config.toml

#### Windows
Copy this file to %AppData%\helix\config.toml

## Notable Helix Settings for New Users

This config makes Helix editor:
- Map `esc` key to reset Helix to fully default state.
- Use dark_plus theme, which works without problems in `hx --tutor` and looks like "Dark+" theme from Visual Studio Code.
- Make cursor shape indicate normal, insert, and select modes.
- Fix true color detection problem on some platforms like Linux on Windows WSL2.

Some other useful settings are included as examples.

## Vim-Like Configuration for Helix

See https://github.com/LGUG2Z/helix-vim

## Copyright Notice

Copyright © 2022 Montgomery Edwards⁴⁴⁸ (github.com/x448)  
Licensed under the MIT License. See [LICENSE](LICENSE).

