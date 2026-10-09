# xlanstar/homebrew-tap

[MacMeow（貓貓谷 for Mac）](https://github.com/xlanstar/mac-meow) 的 Homebrew tap。

```sh
brew install --cask xlanstar/tap/macmeow   # 安裝
brew upgrade --cask macmeow                # 更新
brew uninstall --cask macmeow              # 移除 App（--zap 另外刪除設定、記錄與 LaunchDaemon）
```

需要 Apple Silicon Mac、macOS 13 以上與 [Cyder](https://github.com/dspp779/CyderBits/releases)；使用方式、完整移除步驟與已知問題見 [MacMeow 的 README](https://github.com/xlanstar/mac-meow#readme)。

`Casks/` 由 MacMeow 的發佈流程自動產生（範本：[`packaging/homebrew/macmeow.rb`](https://github.com/xlanstar/mac-meow/blob/main/packaging/homebrew/macmeow.rb)），請不要直接修改；問題請到 [MacMeow 的 issues](https://github.com/xlanstar/mac-meow/issues) 回報。
