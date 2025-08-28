---
apply: 始终
---

# 提交信息准则

提交信息应遵循 [Angular 提交信息规范](https://github.com/angular/angular/blob/main/contributing-docs/commit-message-guidelines.md)
，并做如下补充：

1. 提交信息的首选语言为中文，但允许英语等主要维护者能够阅读的语言
2. 版本发布统一使用 `chore: release ${version}` 的格式

## Type

1. 对于项目依赖变动，均使用 chore(deps)
2. build 仅适用于影响构建产物的变动，对于 lint 等开发辅助工具的调整应使用 chore
