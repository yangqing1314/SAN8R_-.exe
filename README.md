# SAN8R 编辑器

《三国志8 REMAKE 威力加强版》编辑器项目。

## 当前版本

当前仓库先包含已经制作完成的 Windows x64 中文编辑器：

- 中文界面
- 中文武将/能力/语音数据库
- 基于原编辑器的 Windows 可执行程序

GitHub Actions 会在 Windows Server 2025 Runner 上把现有 EXE 作为构建产物上传。

## GitHub Actions

进入：

Actions → Build SAN8R Editor → Run workflow

构建完成后：

Artifacts → SAN8R-Editor-Windows-x64

即可下载：

`SAN8R_中文编辑器.exe`

## 重要说明

“突破男性正常 3 名配偶限制”的存档修改逻辑目前尚未作为最终版本加入本项目。

此前对存档关系表的一个定位被确认是假阳性，因此没有把未经验证的存档修改代码放进项目，以避免损坏存档。

后续需要在确认真实配偶数据结构后，再加入配偶编辑功能。
