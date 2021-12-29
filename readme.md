# Casource: Combination of Cascadia Code & Source Han Sans

Cascadia Code SemiLight + Source Han Sans Regular
![regular](https://user-images.githubusercontent.com/12044683/147409882-d80dc5b4-fbdf-4556-9c8e-8b1b1dc57ba2.png)

Cascadia Code SemiBold + Source Han Sans Bold
![bold](https://user-images.githubusercontent.com/12044683/147409921-e1d79380-e79b-4888-ab8b-68e41784960b.png)

## Why?

Certain IDE \ console (s) don't have the ability to fallback Chinese characters into a user-specified Chinese font, which usually means Chinese will be displayed in Sim Sun, a serif font. Therefore, a Chinese font that is capable of programing is meaningful. However, few options are available aside from Sarasa, which sticks to the concept of half width and full width, making reading code (obviously mostly made up of letters) a real pain to me.

All fonts released here are built by a GitHub Action, making it totally at ease to update font version. you can easily swap both base font and CJK font with your favorite.

## How?

Most of the work is done by a [font merger](https://github.com/nowar-fonts/Warcraft-Font-Merger) originally written by CyanoHao, intended to make custom font for World of Warcraft. This tool, however, lacks the ability to customize output font name. So, I made my own fork with this function. For now, this workflow will checkout my fork but will switch to upstream once my pull request is merged.

## What'more

Italic Chinese isn't supported yet. ("Italic" in release are made up of italic letter and regular Chinese character) Although there isn't a concept corresponding with italic in Chinese, this might make some misleading in IDE using italic to represent certain syntax element.
