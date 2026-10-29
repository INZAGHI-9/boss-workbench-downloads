# BOSS 本机工作台安装包

这里提供客户安装包，源码仓库保持私有，不存放客户业务数据。

| 电脑 | 当前正式版本 | 安装方式 |
|---|---|---|
| Windows x64 | [5.1.0 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v5.1.0/BossWorkbench-5.1.0-win-x64.exe) | 先从托盘安全退出已有工作台，再运行 EXE，保留原数据安装。 |
| Mac M 系列 | [5.1.0 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v5.1.0/BossWorkbench-5.1.0-mac-arm64.dmg) | 先从菜单栏安全退出，再打开 DMG，将应用拖入 Applications。 |

[发布说明、全部附件及 SHA256SUMS](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/tag/v5.1.0)。两端自动更新频道现为 5.1.0；旧版未内置本仓库来源时，请先手动安装一次。CDN 可能短时缓存旧清单，直接下载链接可用。

用户已确认核心安装升级验收：Windows 5.0.4→5.0.5 与 Mac 5.0.8→5.0.9 按各自实际产物记录；5.1.0 两端发行包分别经过本机运行时及合成数据核验，不把这些检查扩大为所有客户系统均已实测。Windows 构建摘要见附件 windows-build-summary.json。

安装包自带 Python、Node 和数据库，客户无需开发工具。首次启用浏览器在缺少 Chrome 或缓存时可能需要联网；模型和 BOSS 日常使用也需要相应网络和账户。更新不会自动恢复招聘任务，请保留原数据目录。

目标系统：Windows 10 1903+ x64、Windows 11 x64；Mac M 系列 macOS 14+。Windows 包未签名，Mac 包未公证，请遵循电脑的安全策略。

程序文件可以从安装包提取；保持 Git 源码仓库私有不代表安装包具备防逆向能力。本仓库不提供源码访问凭证。
