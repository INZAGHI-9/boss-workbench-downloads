# BOSS 招聘工作台安装包

这里提供客户安装包。源码仓库保持私有；客户下载无需源码仓库权限，仓库不存放客户业务数据或凭证。

| 系统 | 当前正式版本 | 安装方式 |
|---|---|---|
| Windows x64 | [6.1.2 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v6.1.2/BossWorkbench-6.1.2-win-x64.exe) | 从托盘安全退出现有工作台，再运行 EXE，保留原数据。 |
| Mac M 系列 | [6.1.4 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v6.1.4/BossWorkbench-6.1.4-mac-arm64.dmg) | 从菜单栏安全退出，再打开 DMG，将应用拖入 Applications。 |

[Mac 6.1.4 发布说明、附件与校验收据](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/tag/v6.1.4)。Mac 独立更新频道已提供 6.1.4；共享频道保留 [Windows / Mac 6.1.2](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/tag/v6.1.2)。旧 Mac 6.1.1 先升级至过渡 6.1.2，再检查独立频道。

Mac 6.1.4 增加顶部可信任务进度，修补列表毕业/教育信息、关闭简历安全隔离和材料失败原步骤接续。6.1.2 是最后一份兼容 ZIP 的过渡版；6.1.4 提供 DMG 和独立差量，不再提供 ZIP。6.1.3 可直接差量更新，6.1.2 在后台连续应用历史差量后最终只安装一次最新版。全部独立差量和版本清单保留，本次未清理旧版安装包。

已装 Mac 6.1.0 的旧更新器元数据有误，请安全退出后以 DMG 覆盖应用，其结构4数据库无需迁移。6.1.2 安装包可对明确支持的已知 v3 原库执行保数据升级；未知结构和身份冲突仍拒绝，不要求手工改库或删除旧数据。Windows 6.1.2 已完成原生封包、资源核对、隔离运行时启动/退出及存储回放验证。

Mac 6.1.4 已核对最终资源、DMG 内应用一致性、严格签封、远端大小与 SHA-256；正式 6.1.3 / 6.1.2 原更新模块的单段/两段实际差量重放、隔离运行时两次启动/安全退出及两条合成业务流程通过。本票专项和独审已完成；全仓后端仍有失败与未归因项，未声称全套通过。正式 Mac GUI 升级和真实招聘未计为通过。Mac 为 ad-hoc 签封且未公证，Windows 未签名。完整校验见各版 `macos-SHA256SUMS.txt` 或 `windows-SHA256SUMS.txt`。

安装包自带 Python、Node 和数据库，客户无需开发工具。首次启动下载缺失浏览器组件、使用模型和 BOSS 仍需网络及相应账户。更新不自动恢复招聘任务，请保留原数据目录。覆盖前正常安全退出并备份业务数据；已经发生的结构升级不能通过覆盖旧应用撤销，降级需升级前备份。

目标系统：Windows 10 1903+ x64、Windows 11 x64；Mac M 系列 macOS 14+。程序文件可从安装包提取，Git 源码仓库私有不代表安装包具备源码保密能力。
