# Patch for Telegram Theme for Icalingua++

一个基于 [Telegram Theme for Icalingua++ v1.0.2](https://github.com/wibus-wee-ac/icalingua-theme-telegram/releases/tag/v1.0.2) 的补丁，使其与 Telegram 进一步一致。

~~因为我懒得读源码，所以以补丁的形式呈现。~~

## 安装

1. 将原 `style.css` 和 `patch.css` 移至 `styles/`。
2. 新建 `style.css`，内容为
    ```css
    @import 'styles/style.css';
    @import 'styles/patch.css';
    ```