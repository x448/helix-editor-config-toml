# Post-Modern Helix Editor Configuration (config.toml)
A Helix editor configuration (config.toml) for new users.

## Introduction

[Helix](https://github.com/helix-editor/helix) is a modal text editor (similar to Vim) but Helix has "batteries included".  You don't need to install a bunch of plugins to make Helix great for editing and navigating source code.

This small config helps new users avoid some early problems and shows how to configure Helix editor with useful examples.

Notably, this config maps `esc` key to reset Helix to default state of:
- normal mode
- single cursor
- not having multiple chars selected.

This `esc` key shortcut is especially helpful to new users and reviewers. See:
- https://github.com/helix-editor/helix/pull/5289
- https://www.youtube.com/watch?v=8L308PdmhMY&t=887s

As of Helix 22.12 (December 2022), most color themes (including default) [don't work well in Helix tutorial](https://github.com/helix-editor/helix/pull/5309) (`hx --tutor`).  This config uses "dark_plus" theme which works great in Helix tutorial and it looks like "Dark+" from Visual Studio Code.

NOTE: Some advanced Helix users dislike the `esc` key shortcut.  They [prefer to use distinct keys](https://github.com/helix-editor/helix/pull/5289#issuecomment-1365344355) (extra steps) to escape back to fully default state.  However, `esc` key shortcut doesn't prevent users from pressing comma and semicolon for distinct operations, so using `esc` to fully reset makes Helix easier and more ergonomic.

### Instructions:

#### Linux, macOS, *BSD
Copy this file to ~/.config/helix/config.toml

#### Windows
Copy this file to %AppData%\helix\config.toml

## Notable Helix Settings for New Users

This small config (~15 settings) makes Helix editor:
- Map `esc` key to reset Helix to fully default state.
- Use dark_plus theme, which works without problems in `hx --tutor` and looks like "Dark+" theme from Visual Studio Code.
- Make cursor shape indicate normal, insert, and select modes.
- Fix true color detection problem on some platforms like Linux on Windows WSL2.

Some other useful settings are included as examples.

## Vim-Like Configuration for Helix

Helix (and Kakuone) intentionally use some different keys and key combinations, which are worthwhile to try with an open mind.  Thankfully, many keys are the same.

But if you prefer to keep editing code the Vim way with Helix, then you can try a more extensive config that makes Helix more Vim-Like:  
- https://github.com/LGUG2Z/helix-vim

## Copyright Notice

Copyright © 2022 Montgomery Edwards⁴⁴⁸ (github.com/x448)  
Licensed under the MIT License. See [LICENSE](LICENSE).

