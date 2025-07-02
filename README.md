# Patch for Telegram Theme for Icalingua++

一个基于 [Telegram Theme for Icalingua++ v1.0.2](https://github.com/wibus-wee-ac/icalingua-theme-telegram/releases/tag/v1.0.2) 的补丁，使其与 Telegram 进一步一致。

## 安装

1. 禁用 `fix-message-content-width`。
1. 在 `sass` 环境下执行 `build.bat`。
1. 重启 Icalingua++。

## TODO

- [ ] 尽可能将各组件做到和 Telegram 完全一致：
    - [x] `basic`
    - [ ] ~~`toast`~~（不好调试）
    - [x] `room`
    - [x] `contact`
    - [x] `info`
    - [x] `conversation`
    - [x] `input`
    - [ ] `emoji`
- [ ] `input`：支持快捷表情面板和 @ 面板。（不好调试）
- [ ] `info`, `conversation`, `input`：支持单面板模式
- [ ] `room`：支持分组
- [ ] 整理 `color` 和 `mixin`，日久成💩山。~~（已经是了）~~
