# 开心消消乐 - Android APK 构建指南

## 方法一：GitHub Actions 在线构建（推荐）

1. 把这个文件夹上传到你的 GitHub 仓库
2. 进入仓库 Actions 页面，点击 "Build Android APK" 工作流
3. 点击 "Run workflow" → 等待几分钟
4. 构建完成后，在 Actions 页面下载生成的 APK 文件

不需要安装任何本地工具！

## 方法二：本地构建（需要 Android Studio）

1. 安装 Android Studio（https://developer.android.com/studio）
2. 打开本项目的 `android` 文件夹
3. Android Studio 会自动安装 SDK
4. 点击 Build → Build Bundle(s) / APK → Build APK
5. 生成的 APK 在 `android/app/build/outputs/apk/debug/`

## 方法三：在线 APK 生成器（最简单）

访问下面任意一个网站，上传 `www/index.html` 文件：

1. **AppGyver** - https://www.appgyver.com/
2. **PWA Builder** - https://www.pwabuilder.com/
3. **APK Builder Online** - https://apk-builder.online/

上传我们的 HTML 文件即可生成 APK。

## 方法四：HBuilder 云打包

1. 下载 HBuilder（https://www.dcloud.io/hbuilderx.html）
2. 创建 Wap2App 项目
3. 把 `www/index.html` 设为启动页面
4. 选择 "发行" → "云打包" → 选 Android
5. 几分钟后自动下载 APK

---

游戏文件位置：`www/index.html`（完整游戏，可直接浏览器打开）
