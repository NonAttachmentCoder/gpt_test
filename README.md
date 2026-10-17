# gpt_test

这是一个用于验证 **ChatGPT ↔ GitHub** 直接协作能力的测试仓库。

## 测试目标

验证 ChatGPT 在获得 GitHub 授权后，能否直接完成以下操作：

1. 读取仓库信息及访问权限。
2. 创建并提交 Markdown 文件。
3. 读取 GitHub 上实际保存的文件，核对内容。
4. 修改已有文件，并检查更新后的提交记录。
5. （可选）通过分支和 Pull Request 管理后续变更。

## 使用方式

该仓库仅用于轻量测试，不包含实际科研项目代码。

克隆仓库：

```bash
git clone https://github.com/NonAttachmentCoder/gpt_test.git
cd gpt_test
```

## 测试记录

- **2026-10-17**：通过 ChatGPT 的 GitHub 连接初始化 README，测试远程文件创建与读取。

## 验证结果

- [x] GitHub 仓库读取
- [x] README 文件创建与首次提交
- [x] 首次提交后重新读取与核验
- [x] 修改已有文件并再次提交

## 说明

所有修改都通过 GitHub 仓库接口完成，不依赖用户本地电脑上的 Git 或 SSH 环境。

---

Repository: [NonAttachmentCoder/gpt_test](https://github.com/NonAttachmentCoder/gpt_test)
