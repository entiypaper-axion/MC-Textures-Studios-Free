🎨 MCTS Free 1.0.2.1 — 现在有 Windows 版了！

这是 1.0.0 之后的第一个公开版本，包含 1.0.1、1.0.2 和 1.0.2.1 的全部更新。

**下载**
• 安卓：`MCTS_1.0.2.1-Release-Fr.apk`（需要 Android 8.0 或以上）
• Windows：`MCTS_1.0.2.1-Release-Fr_Windows_Setup.exe`（Windows 10 1809+ / Windows 11 x64，自带 Java 运行时，不需要管理员权限）
• 源码：`..._Android_Source.zip`、`..._Windows_Source.zip`

⚠️ **安卓签名变更**：从这个版本起 APK 换了新的签名。装过 1.0.0 的话，请先导出项目、卸载旧版，再安装 1.0.2.1；以后的版本可以直接覆盖升级。
⚠️ Windows 安装包没有代码签名，首次运行时 SmartScreen 可能提示"未知发布者"，点"更多信息 → 仍要运行"即可。

**主要更新**
• Windows 版：和安卓同一套功能；键盘、鼠标、手写笔，快捷键可自定义
• 全新界面：顶栏三组、画板可放在左 / 中 / 右，自定义 UI（9 个模块随意拖放，横竖屏各存预设）
• 全部版本模板：Java 版 1.0 → 26.3 共 103 个，基岩版 51 个自动配对；只认 Mojang 官方 SHA-1，出错自动换线路（含国内镜像）
• 液态玻璃（可选）：透出实时界面，壁纸可选；模糊度、不透明度、折射、色散高光可调，大 UI / 小 UI 各一套，可逐个元素开关
• 3D 预览贴图修正：不完整方块按游戏官方模型贴图（门分上下两半、草方块侧面叠加层等）
• 游戏字体：我的世界 Java 版字体从官方 client.jar 在本机生成；原神、泰拉瑞亚、GTA 6 可导入自己的字体文件
• 开场动画、苹果式轻弹动效、自动保存、导入 PNG / 资源包、像素完美、镜像、容差填充、5 种语言、无障碍
• 修复：搜索纹理时输入法弹出又收回；小窗口和液态玻璃下透出的是壁纸而不是实时界面

**已知问题（将在 1.0.2.2 修复）**
• Windows 版导入壁纸 / 背景图会失败
• 1.0 – 1.5.2 的老版本模板下载会提示校验失败

使用前请备份项目，导出效果请在 Minecraft 中验证。反馈问题请附设备型号、系统版本、操作步骤与截图。

---

🎨 MCTS Free 1.0.2.1 — now on Windows too!

The first public release since 1.0.0, including everything from 1.0.1, 1.0.2 and 1.0.2.1.

• Android APK (Android 8.0+), Windows installer (Windows 10 1809+ / 11 x64, bundled Java runtime, no admin rights), and full sources.
• ⚠️ The Android signing key changed: if you have 1.0.0 installed, export your projects, uninstall it, then install 1.0.2.1. Later versions upgrade in place.
• ⚠️ The Windows installer is not code-signed; SmartScreen may warn about an unknown publisher.

Highlights: Windows edition; new workspace with movable canvas and fully custom layouts; templates for every Java release from 1.0 to 26.3 (103) plus 51 matched Bedrock versions, pinned by Mojang's SHA-1; optional liquid glass that shows the live UI, with adjustable blur, opacity, refraction and highlights; 3D previews of partial blocks now use the game's official models; a Minecraft Java UI font generated locally from the official client.jar; startup animation, spring motion, autosave, PNG and pack import, five languages and accessibility options.

Known issues (fixed in 1.0.2.2): importing a wallpaper or background image fails on Windows; downloading the 1.0 – 1.5.2 templates fails verification.

MCTS is an unofficial project, not affiliated with Mojang or Microsoft.
