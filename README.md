# Blackboard 课件工作台

Blackboard Learn Ultra 课件采集与整理工作台（macOS / Windows 桌面版）。

## 功能

- **SSO 静默登录**：复用 CUHK 等学校的 ADFS 会话，一次登录，之后免密采集
- **整门课采集**：PDF / PPT / 讲义按章节自动归档
- **AI 对话整理**：基于课件内容总结、划重点、出题自测
- **日程同步**：作业截止日期（DDL）一键导出 `.ics` 订阅到系统日历

## 下载

| 平台 | 下载 |
|---|---|
| macOS (Apple Silicon) | 见 [Releases](https://github.com/kodakku-sudo/blackboard-workbench/releases) |
| Windows | 见 [Releases](https://github.com/kodakku-sudo/blackboard-workbench/releases) |

> 应用内置自动更新：启动时检查 `https://ledakku.hk.cn/update.json`，发现新版本自动下载安装包。

## 更新机制

版本清单文件 `update.json` 结构：

```json
{
  "version": "0.3.1",
  "notes": "本次更新说明",
  "macUrl": "https://github.com/.../xxx.dmg",
  "winUrl": "https://github.com/.../xxx.exe"
}
```

## License

ISC
