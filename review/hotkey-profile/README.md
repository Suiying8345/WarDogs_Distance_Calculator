# 热键档案审核材料

对应 PR：[Ricoz217/WarDogs_Distance_Calculator#14](https://github.com/Ricoz217/WarDogs_Distance_Calculator/pull/14)

代码分支 `feature/upstream-hotkey-refinement`（6 个提交，基于 `131c9f3`）。本目录位于独立审阅分支，仅供审核，请勿合并。

## 内容

- `hotkey-profiles-review.pdf`：12 页中文说明，A4；含改造前后截图、键位对照、手势时序、设置页与档案管理、日志验证、主窗口对照、兼容性。
- `index.html`：PDF 源文件与同一份内容；用 Chrome 或 Edge 打开。追加 `?p=N` 只显示第 N 页。
- `assets/`：正文引用的截图与裁图，编号即 PDF 中的引用顺序。

## 说明

- 截图取自内置默认配置，未包含个人设置与本机路径。
- 改造前截图来自上游 `v1.4.2`（`131c9f3`）；改造后截图来自本 PR 的 Release 构建。
- 时序图中的 400 ms 为长按阈值；双击窗口跟随系统设置，Windows 默认 500 ms。
