<h1 align="center">
  <img src="./assets/icon-v2.svg" alt="qBitRemote" width="160" />
  <br>
  qBitRemote — Android 原生 qBittorrent 远程管理客户端
</h1>

<h3 align="center">
基于 <a href="https://kotlinlang.org/">Kotlin</a> + <a href="https://developer.android.com/compose">Jetpack Compose</a> 的 <a href="https://www.qbittorrent.org/">qBittorrent</a> 远程管理客户端。&nbsp;|&nbsp; <a href="README_EN.md">English</a>
</h3>

## 特点

- **轻量纯净**
    - 安装包仅 2.61 MB；无广告、无遥测、无崩溃上报，所有连接直连你自己的 qBittorrent
- **功能完整**
    - 多服务器管理，凭据 Android Keystore 加密存储，每服务器独立会话
    - 种子列表实时刷新、搜索、状态/分类/标签筛选、多选批量操作
    - 种子详情：信息 / 文件 / Tracker / Peers 四视图 + 进度区块条；文件优先级、重命名
    - Tracker 管理、Peers 管理（含永久禁止与解封）、队列优先级、做种/限速/分享限制、导出 .torrent
- **服务器设置对齐 WebUI**
    - 速度（全局/备用限速、限速计划）、连接（端口、UPnP、连接数上限、IP 过滤）
    - BitTorrent（DHT/PeX/LSD、加密模式、匿名模式、Torrent 队列、做种限制、自动追加 Tracker）
    - 下载（默认保存路径、TMM 策略、.torrent 备份）
- **体验**
    - 简体中文 / 繁體中文 / English 应用内切换；17 种主题色 + 动态取色（Android 12+）
    - 分享 / 打开方式 / 磁力链接一键转入添加面板；qB 服务器日志查看

## 安装

- [GitHub Releases 下载](https://github.com/westoi/qBitRemote/releases/latest)

### 系统要求

- Android >= 8.0
- qBittorrent 4.x（Web API 2.9+）；5.x 基本可用，个别 5.x 新增设置项暂未提供

### 语言文件

三份语言资源位于 [`app/src/main/res/`](app/src/main/res/)：`values/`（English）、`values-zh-rCN/`（简体中文）、`values-zh-rTW/`（繁體中文）。

## 提交需求 / Bug

- [欢迎报告 issue](https://github.com/westoi/qBitRemote/issues)

## 捐赠

请开发者喝杯咖啡 ☕

<img src="./assets/donate.jpg" width="240" alt="捐赠二维码" />

## Projects

### 致谢：qBitRemote 基于或受到这些项目的启发：

- [qBittorrent](https://www.qbittorrent.org/)：自由开源的 BitTorrent 客户端
- [Jetpack Compose](https://developer.android.com/compose) / [Material 3](https://m3.material.io/)：Android 现代声明式 UI
