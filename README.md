# BOSS 招聘工作台安装包

这里提供客户安装包。源码仓库保持私有；客户下载无需源码仓库权限，仓库不存放客户业务数据或凭证。

| 系统 | 当前正式版本 | 安装方式 |
|---|---|---|
| Windows x64 | [6.1.2 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v6.1.2/BossWorkbench-6.1.2-win-x64.exe) | 从托盘安全退出，再运行 EXE，保留原数据。 |
| Mac M 系列 | [6.2.0 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v6.2.0/BossWorkbench-6.2.0-mac-arm64.dmg) | 从菜单栏安全退出，再打开 DMG，将应用拖入 Applications。 |

[Mac 6.2.0 发布说明、附件与校验收据](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/tag/v6.2.0)。Mac 独立更新频道提供 6.2.0；Windows/共享频道保持 6.1.2。

Mac 6.2.0 新增精准寻访三阶段流程，统一名单、简历浮窗、任务进度、报告与提醒。搜索配置按岗位保存和读取，新任务依据最新保存的画像；已确认收藏的成果在停止后仍可复用，由用户选人并确认联系。

Mac 6.1.2–6.1.5 通过独立差量链升级，历史差量在后台连续应用，最终只安装一次最新版。旧 Mac 6.1.1 先升级至过渡 6.1.2，再检查独立频道；6.1.0 的旧更新器元数据有误，应安全退出后手动覆盖安装。6.2.0 涉及 schema4→10 数据库升级，未知结构和身份冲突仍拒绝，不手工改库或删除旧数据。本次保留历史安装附件和差量。

最终资源、DMG、严格签封和远端大小/SHA-256已核对；隔离原版更新器回放及公开频道验证见附件收据。真实 GUI 安装、新版服务现场确认与真实招聘未计为通过。Mac 为 ad-hoc 签封且未公证，Windows 未签名。校验见各版 `macos-SHA256SUMS.txt` 或 `windows-SHA256SUMS.txt`。

安装包自带 Python、Node 和数据库，客户无需开发工具。首次启动下载缺失浏览器组件、使用模型和 BOSS 仍需网络及相应账户。更新不自动恢复招聘任务或补发未知动作，请保留原数据目录。覆盖前正常安全退出并备份业务数据；结构升级不能通过覆盖旧应用撤销，降级需升级前备份。

目标系统：Windows 10 1903+ x64、Windows 11 x64；Mac M 系列 macOS 14+。程序文件可从安装包提取，Git 源码仓库私有不代表安装包具备源码保密能力。
