# baiguotv-release

白果TV 安卓应用发布仓库（源码保持私有：zqs1qiwan/baiguotv）。

## 下载

在 [Releases](https://github.com/zqs1qiwan/baiguotv-release/releases) 页面下载最新 APK。

## 应用内自动更新

应用启动后会读取 `https://github.com/zqs1qiwan/baiguotv-release/releases/latest/download/update.json` 检查新版本，前台空闲时每 6 小时检查一次，播放中不打扰。下载完成后校验 SHA-256 并提示安装。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `baiguotv-<版本>-android8.apk` | 正式版安装包（Android 8+） |
| `baiguotv-<版本>-debug.apk` | 调试版安装包 |
| `update.json` | 应用内自动更新清单（schema 1） |
| `SHA256SUMS` | 全部文件校验和 |
