# 东方绀珠传基础汉化内容

当前内容版本：2026.1019.3。main 为正式频道，dev 为开发频道。

- [游戏资源与译图](files/100b/data/)
- [启动框资源](files/100b/startup-dialogs/)
- [当前符卡名称表](files/100b/spell-names/)
- [当前内嵌文本表](files/100b/text-substitutions/)

对象统一位于 `files/100b/`；仓名表示作品，版本目录不重复作品名。
本次仅迁移发布路径，载荷、原资源 guard 和最低启动器要求保持；客户端无需重编译。
根 manifest.json / manifest.sig 授权对象及其大小、SHA-256、目标与原资源保护条件。
工作区规范和开发维护文件不随内容发布。
固定文本 JSON 的新适配器候选尚未在此频道发布；当前对象保留既有格式。

LilyPatch TH15 1.00b 原版 / Steam 共用的基础内容，版本 2026.1019.3。
自有内容源来自首次只读导出的既有 THWiki／喵玉汉化组译文；来源和逐项哈希保存在
LilyPatch/content/th15/import-lock.json 与 source/source-manifest.json。
原文参考：https://thwiki.cc/东方绀珠传 。自有协作源的修订由 LilyPatch 记录。

仅此仓中的 manifest.json / manifest.sig / files/ 参与基础内容更新。
可选跳关包在 [LilyCloudPatch/plugins](https://github.com/LilyCloudPatch/plugins) 的 thpatch-skipgame/th15 子树，独立使用 plugin 信任锚。
本树不提供游戏 EXE、DAT、Steam DLL 或第三方汉化补丁可执行代码。
