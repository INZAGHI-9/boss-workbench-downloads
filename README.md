# BOSS 招聘工作台安装包

这里提供客户安装包。源码仓库保持私有；客户下载无需源码仓库权限，仓库不存放客户业务数据或凭证。

| 系统 | 当前正式版本 | 安装方式 |
|---|---|---|
| Windows x64 | [6.1.1 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v6.1.1/BossWorkbench-6.1.1-win-x64.exe) | 从托盘安全退出现有工作台，再运行 EXE，保留原数据。 |
| Mac M 系列 | [6.1.1 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v6.1.1/BossWorkbench-6.1.1-mac-arm64.dmg) | 从菜单栏安全退出，再打开 DMG，将应用拖入 Applications。 |

[发布说明、全部附件与校验收据](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/tag/v6.1.1)。客户端更新频道现为同版本 Windows / Mac 6.1.1；仅具备兼容更新合同的旧客户端适用。Windows 完整校验见 `windows-SHA256SUMS.txt`。

已装 Mac 6.1.0 的旧更新器元数据有误，请安全退出后以 DMG 覆盖应用；其数据库已为结构4，无需迁移。旧6.0.0不能仅凭新清单直接跨结构升级，覆盖应用也不授予数据库迁移许可，需后续桥接或显式迁移路径。

6.1.1 两端包均已核对最终资源、远端大小与 SHA-256；隔离运行时启动/安全退出和两条合成业务流程通过，Windows另完成解包实包GUI检查。NSIS原生安装/卸载、旧版本跨结构安装升级尚未验收；历史版本的安装记录不替代本版验收。Mac为ad-hoc签封且未公证，Windows未签名。

安装包自带 Python、Node 和数据库，客户无需开发工具。首次启动下载缺失浏览器组件、使用模型和 BOSS 仍需网络及相应账户。更新不自动恢复招聘任务，请保留原数据目录。

目标系统：Windows 10 1903+ x64、Windows 11 x64；Mac M 系列 macOS 14+。程序文件可从安装包提取，Git源码仓库私有不代表安装包具备源码保密能力。
