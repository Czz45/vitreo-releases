# Vitreo Releases

Vitreo（Android 音乐播放器）的安装包发布仓库。

源码仓库：`Czz45/Vitreo`（private）。

## 安装

到 [Releases](../../releases/latest) 下载最新 `vitreo-<version>.apk` 直接安装。
首次安装需在系统里允许「安装未知来源应用」。

## 说明

- 每个 release 的 tag 形如 `v1.1.0`，与 app 内 `versionCode` 对应（major*10000+minor*100+patch）。
- App 启动时静默查询 `releases/latest`，有新版本会在应用内提示下载安装。
