# default-workspace

DSH（DeepSeek Harness）默认工作区仓库。

## 用途

本仓库用于存放并版本化管理在此工作区中产出的代码与文档，并推送到 GitHub 进行备份与协作。

## 环境

- 平台：Windows
- Git：2.55.0.windows.3
- 主分支：`main`
- 认证方式：HTTPS + Git Credential Manager（凭据存于 Windows 凭据管理器）

## 快速开始

```powershell
# 克隆
git clone https://github.com/<你的用户名>/<仓库名>.git

# 日常提交
git add .
git commit -m "描述本次改动"
git push
```

## 说明

- `.gitignore` 已预置 Node / Python / 编辑器 / 系统垃圾文件规则，并**默认排除密钥与 `.env` 等敏感文件**。
- 提交前请确认没有误提交密钥、Token 或个人隐私数据。
