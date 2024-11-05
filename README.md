# karabiner-config

Karabiner-Elements 設定ファイル

## 概要

- 日本語キーボードを US 配列キーボードとして使う。
  - macOS 側でキーボードの種別を US 配列にする。
- 「英数」を Escape にマッピング
- 「かな」を Fn キーにマッピング
- Fn キーと同時押しに次のようなキーをマッピング
  - Fn + H/J/K/L ... 矢印キー（vi のカーソル移動に対応）
  - Fn + I/O ... PageDown/PageUp
  - Fn + ,/. ... Home/End
  - Fn + 1/2/3/.../0 ... F1/F2/F3/.../F10
  - Fn + A/Z/W/S/X/E/D/C/R/F/V/T/G ... アプリケーションの Focus or Launch
- Ctrl+J ... 「かな」
- Ctrl+L ... 「英数」

## インストール

    mkdir -p ~/.config
    git checkout https://github.com/hre-i/karabiner-config.git ~/.config/karabiner
