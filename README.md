# qu

## 开发流程

1. 从 `main` 创建短期分支，例如 `feature/login` 或 `fix/login-error`。
2. 在分支上提交修改，向 `main` 发起 Pull Request。
3. 请其他协作者评审；处理完代码讨论后再合并。
4. 通过 Squash merge 合并，合并后删除短期分支。

`main` 是稳定分支。开发、测试、生产环境由部署配置区分，不使用长期的环境分支。
