<p align="center">
    <img src="assets/coldark-banner.png" alt="Coldark Banner" width="400" />
</p>

# Coldark - Zsh Theme

![GitHub License](https://img.shields.io/github/license/ArmandPhilippot/coldark-zsh-theme?colorA=111B27&color=d8e0eb&logo=Github&logoColor=E3E9F2&style=for-the-badge) ![GitHub package.json version](https://img.shields.io/github/package-json/v/ArmandPhilippot/coldark-zsh-theme?colorA=111B27&color=d8e0eb&logo=Github&logoColor=E3E9F2&style=for-the-badge)

An optimized theme for web development that comes with two versions: light & dark.

## Presentation

[Coldark](https://github.com/ArmandPhilippot/coldark/) is a gray-blue theme. The colors used respect the Web Content Accessibility Guidelines (WCAG) in order to provide sufficient reading comfort.

It is recommended to use it with [Coldark for XFCE4 terminal](https://github.com/ArmandPhilippot/coldark-xfce4-terminal) so that the colors match those of Coldark.

## Colors

Coldark consists of three color palettes. The first is common to both versions. The other two each apply to a version.

Coldark uses 16 colors for each theme. However, the Coldark ZSH theme only uses 10 colors.

|                | Light Theme |                                                          | Dark Theme |                                                          |
| -------------- | ----------- | :------------------------------------------------------: | :--------: | :------------------------------------------------------: |
| **Usage code** | **Hex**     |                       **Preview**                        |  **Hex**   |                       **Preview**                        |
| `coldark02`    | `#ccd6e4`   | ![#ccd6e4](https://placehold.it/20/ccd6e4/000000?text=+) | `#304259`  | ![#304259](https://placehold.it/20/304259/000000?text=+) |
| `coldark03`    | `#304259`   | ![#304259](https://placehold.it/20/304259/000000?text=+) | `#ccd6e4`  | ![#ccd6e4](https://placehold.it/20/ccd6e4/000000?text=+) |
| `coldark06`    | `#213043`   | ![#213043](https://placehold.it/20/213043/000000?text=+) | `#f0f3f8`  | ![#f0f3f8](https://placehold.it/20/f0f3f8/000000?text=+) |
| `coldark07`    | `#f0f3f8`   | ![#f0f3f8](https://placehold.it/20/f0f3f8/000000?text=+) | `#213043`  | ![#213043](https://placehold.it/20/213043/000000?text=+) |
| `coldark08`    | `#007474`   | ![#007474](https://placehold.it/20/007474/000000?text=+) | `#5dc2c2`  | ![#5dc2c2](https://placehold.it/20/5dc2c2/000000?text=+) |
| `coldark09`    | `#7d6600`   | ![#7d6600](https://placehold.it/20/7d6600/000000?text=+) | `#cdb74a`  | ![#cdb74a](https://placehold.it/20/cdb74a/000000?text=+) |
| `coldark10`    | `#005c99`   | ![#005c99](https://placehold.it/20/005c99/000000?text=+) | `#6ab3e4`  | ![#6ab3e4](https://placehold.it/20/6ab3e4/000000?text=+) |
| `coldark11`    | `#237800`   | ![#237800](https://placehold.it/20/237800/000000?text=+) | `#82c366`  | ![#82c366](https://placehold.it/20/82c366/000000?text=+) |
| `coldark12`    | `#b800b8`   | ![#b800b8](https://placehold.it/20/b800b8/000000?text=+) | `#ea89ea`  | ![#ea89ea](https://placehold.it/20/ea89ea/000000?text=+) |
| `coldark15`    | `#bf0100`   | ![#bf0100](https://placehold.it/20/bf0100/000000?text=+) | `#f57a73`  | ![#f57a73](https://placehold.it/20/f57a73/000000?text=+) |


- **`coldark02`: Dark gray**  
  Used as foreground for Git indicators (if bold is bright checked).
- **`coldark03`: Light gray**  
  Used as foreground for text (if bold is bright unchecked).
- **`coldark06`: White**
  Used as foreground for text (if bold is bright checked).
- **`coldark07`: Black**
  Used as foreground for Git indicators (if bold is bright unchecked).
- **`coldark08`: Cyan**  
  Used as background for Git unmerged.
- **`coldark09`: Yellow**  
  Used as foreground for prompt indicator and git branch. Also used as background for Git changed.
- **`coldark10`: Blue**  
  Used as foreground for username and time. Also used as background for Git renamed.
- **`coldark11`: Green**  
  Used as foreground for current path and clean Git repo. Also used as background for Git added.
- **`coldark12`: Magenta**  
  Used as background for Git untracked.
- **`coldark15`: Red**  
  Used as foreground for dirty Git repo. Also used as background for Git deleted.

## Features

Coldark Zsh Theme uses the Git feature of [Oh my Zsh](https://github.com/ohmyzsh/ohmyzsh). You can see the current branch and if your repo is clean or dirty (untracked, modified, ...). The theme also displays the time to the right of the prompt.

## Screenshots

These screenshots were taken with the Coldark for XFCE4 terminal theme.

|                             Light Theme                              |                             Dark Theme                             |
| :------------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Coldark Terminal Light](./assets/coldark-zsh-theme-light.jpg) | ![Coldark Terminal Dark](./assets/coldark-zsh-theme-dark.jpg) |

## Install & Activation

1. Place the theme in `~/.oh-my-zsh/custom/themes/`.
2. Edit `~/.zshrc` and replace `ZSH_THEME` value with `coldark` (e.g. `ZSH_THEME="coldark"`)
3. Reload ZSH config: `source ~/.zshrc`

## License

This project is open source and available under the [MIT License](https://github.com/ArmandPhilippot/coldark-zsh-theme/blob/master/LICENSE).
