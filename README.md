# USKey2JP

## 概要

**USkey2JP** は、日本語配列キーボードと英語配列キーボードを併用するためのソフトウェアです。  
“**US KEYboard TO Japanese Pc**” という意味から名付けています。  
特に、ノートPCのように標準のキーボードレイアウトを日本語配列から変更できない環境で、外部キーボードに英語配列キーボードを使う場合に便利です。


## インストール／アンインストール

### インストール

1. ダウンロードした実行ファイル（`uskey2jp.exe`）を任意のフォルダに配置してください。
2. そのまま実行すれば、インストール不要で使用を開始できます。
3. Windows 起動時に自動で実行したい場合は、Windows の「スタートアップ」フォルダにショートカットを作成するなどの方法で設定してください。

### アンインストール

- 配置したファイルを削除するだけでアンインストールは完了です。
- レジストリの変更やドライバの追加は行いませんので、不要なファイルは残りません。


## 使い方

1. **USkey2JP** を実行すると、タスクトレイにアイコンが表示されます。
2. タスクトレイアイコンをクリックすることで、本ソフトのオン／オフを切り替えられます。
    - **オン**：US配列のエミュレートが有効になります。
    - **オフ**：通常の日本語配列として動作します。


## 注意事項・制限

### 動作環境

- Windows 11 で動作確認済み（Windows 10 は未検証）
- 64bit CPU 用にビルド（32bit CPU では動作不可。要望があれば 32bit 版のビルドも検討）

### 既知の問題点

特になし


## 謝辞

本ソフトウェアの開発にあたり、大きなインスピレーションを与えていただいた [ULE4JIS](https://github.com/dezz/ULE4JIS) の開発者・コントリビューターの皆様に感謝いたします。

---

## Overview

**USkey2JP** is a software tool that enables the combined use of both Japanese-layout and English-layout keyboards. The name comes from "**US KEYboard TO Japanese Pc**." It is particularly helpful in situations where you cannot change your laptop’s default keyboard layout from Japanese (such as on many Japanese PCs), yet you wish to use an external English-layout keyboard.


## Installation / Uninstallation

### Installation

1. Place the downloaded executable file (`uskey2jp.exe`) in any folder of your choice.
2. Simply run the file to start using USkey2JP—no installation is required.
3. If you want it to launch automatically when Windows starts, place a shortcut in the Startup folder or configure auto-start in another way.

### Uninstallation

- To uninstall, just delete the file you placed.
- Since it does not modify the registry or install any drivers, no extra files remain on your system.


## Usage

1. When you run **USkey2JP**, an icon appears in the task tray.
2. Click the task tray icon to toggle the software on or off:
    - **On**: Emulates a US keyboard layout.
    - **Off**: Operates as the standard Japanese keyboard layout.


## Notes and Limitations

### Supported Environments

- Confirmed working on Windows 11 (untested on Windows 10).
- Compiled for 64-bit CPUs (will not run on 32-bit CPUs). If there is demand, a 32-bit build may be considered.

### Known Issues

none


## Acknowledgments

We extend our gratitude to the developers and contributors of **ULE4JIS**, whose work provided significant inspiration for creating this software.