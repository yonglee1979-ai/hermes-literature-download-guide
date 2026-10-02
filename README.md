# Hermes Agent 文献下载图文教程

面向科研读者的中文教程。从安装和模型配置开始，逐步完成公开论文下载、医学全文获取、清单去重、核验归档及断点续做。

**当前推荐版本：v2.0.0 公众号发表版，2026-10-02。**

![公众号教程封面](wechat/images/00-cover.png)

## 阅读与发表

- **在线阅读**：打开本仓库 About 栏 Website，适配手机，支持复制正文、命令与提示词。
- **完整文章**：[公众号发表稿 Markdown](wechat/Hermes文献下载_公众号发表稿.md)
- **可编辑文稿**：[Word](downloads/hermes-wechat-guide.docx)
- **排版阅读**：[PDF 15 页](downloads/hermes-wechat-guide.pdf)
- **离线发表稿**：[内嵌图片的 HTML](wechat/Hermes文献下载_公众号排版稿.html)，下载后在电脑浏览器打开。
- **一次取齐**：[完整公众号素材包](downloads/hermes-wechat-package.zip)
- **怎样放进公众号**：[发表使用说明](wechat/公众号发表使用说明.md)

## 新版包含什么

- 12 个正文章节，约 6000 个汉字；另含命令、提示词与来源链接。
- 1 张封面和 12 张高清操作图，配套 13 份可编辑 HTML 图稿。
- 8 组可复制任务提示词，3 行 CSV 去重练习。
- Word、15 页 PDF、单文件 HTML、Markdown 和 ZIP。
- arXiv 真实页面局部截图；医学题录根据 PubMed 官方记录核对。
- 修正 PMC 2026 年数据分发服务调整后的自动获取路线。

## 跟着做

1. 阅读文章第 02 至 04 节，在电脑终端完成安装与配置。
2. 启动 Hermes，将第 05 节检查提示词发送到对话输入区，验证工具、网络和保存路径。
3. 按第 06 节获取 arXiv:1706.03762；自己打开文件，核对 manifest.csv。
4. 再按第 07 节练习 PMID 获取；用 [papers.csv](wechat/papers.csv) 练习三条输入识别为两篇不同文献。
5. 对照第 10 至 11 节核验文件、分类失败原因，按清单继续未完成项。

## 文件与版本

```text
index.html                   当前在线阅读版
wechat/                      v2.0.0 公众号文章及完整配套素材
  images/                    13 张 PNG
  figures/                   13 份 HTML/CSS 图稿
  papers.csv                 清单去重练习
downloads/hermes-wechat-*     新版 Word、PDF 和 ZIP
docs/guide.md                v1.0.0 历史图文稿，已标注版本
images/ 和 figures/          v1.0.0 历史图片与图稿
CHECKSUMS.sha256              仓库文件校验清单
```

v1.0.0 的 Release 与历史文件保留用于版本追溯。实际操作使用新版；特别是 PMC 自动获取路线应参考当前官方文档。

## 来源与验证范围

见 [来源与核验说明](wechat/来源与核验说明.md)。命令、功能与文献标识符依据官方来源核对；图5为真实页面局部截图，其余是明确标注的指令卡或流程图。

没有在本机运行 Hermes 论文下载任务。提示词是工作流模板，实际结果需要在使用者环境中验收。资料已检查文字、图片、手机排版、PDF、Word、示例输入和资料包；发布后还核对公开文件完整性。

本教程为独立创作，不代表 Nous Research 官方发布。素材不包含论文全文、个人账号配置、凭据或私人研究资料。
