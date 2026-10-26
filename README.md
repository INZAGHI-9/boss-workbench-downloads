# BOSS 本机工作台安装包

这里提供客户安装包，源码仓库保持私有，不存放客户业务数据。

| 电脑 | 当前可下载候选 | 安装方式 |
|---|---|---|
| Windows x64 | [5.0.5 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/v5.0.5/BossWorkbench-5.0.5-win-x64.exe) | 先安全退出已有工作台，再运行 EXE，保留原数据安装。 |
| Mac M 系列 | [5.0.2 安装包](https://github.com/INZAGHI-9/boss-workbench-downloads/releases/download/candidate-2026-10-26/BossWorkbench-5.0.2-mac-arm64.dmg) | 打开 DMG，将应用拖入 Applications；新版升级流程待 Mac 实机确认。 |

均为测试候选，尚未作为正式版本推广。Windows 5.0.4→5.0.5 已在 Windows 11 x64 通过真实公开下载、应用内升级、新工作台确认和隔离历史保留检查；本机原数据重开结果见交付记录。Mac 5.0.2 沿用已有安装验收和用户正常使用反馈，不代表 Mac 新版升级已通过。

Windows 5.0.5 内置本仓库的匿名更新来源。旧 Windows 5.0.3 和 Mac 5.0.2 尚无此来源，须手动安装具备来源的新候选。更新频道目前仅提供 Windows；后续补充验收通过的 Mac 5.0.5。校验值见各候选附件 `SHA256SUMS.txt`。

安装包自带 Python、Node 和数据库，客户无需开发工具。首次启用浏览器在缺少 Chrome 或缓存时可能需要联网；模型和 BOSS 日常使用也需要相应网络和账户。更新不会自动恢复招聘任务，请保留原数据目录。

目标系统：Windows 10 x64 1903+、Windows 11 x64；Mac M 系列 macOS 14+。本机 Windows 11 及已有 Windows Server 2025/macOS 15 原生记录不代表所有客户系统组合均已实测。Windows 包未签名，Mac 包未公证，请遵循电脑的安全策略。

安装所需程序文件可被提取；保持 Git 源码仓库私有不代表安装包具备防逆向能力。本仓库不提供源码访问凭证。
