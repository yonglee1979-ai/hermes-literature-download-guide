# Hermes Agent 文献下载攻略

从第一次下载到批量归档的中文图文教程，适合准备课题、综述和学术报告的读者。

![教程封面](images/00-cover.png)

## 从哪里开始

- **直接阅读**：[图文文章](docs/guide.md)
- **阅读与分享**：[下载 PDF（11 页）](downloads/hermes-guide.pdf)
- **一次取齐**：[下载完整素材包](downloads/hermes-guide-package.zip)
- **在线网页**：打开本仓库 About 栏的 Website 入口。页面适配手机，支持复制命令和提示词。
- **跟着练习**：[操作提示词](prompts/tasks.txt) · [示例文献清单](examples/papers.csv)
- **公众号排版与文件用法**：[使用说明](docs/usage.md)

## 教程包含什么

保留完整的九个主题：

1. 明确全文文件、文献清单和未完成清单三项交付物。
2. 安装 Hermes，配置模型，检查工具与保存位置。
3. 用 arXiv:1706.03762 完成第一次单篇论文下载练习。
4. 根据题名、DOI、PMID 获取全文，并处理文献清单。
5. 从研究主题制定检索与筛选方案。
6. 了解医学全文来源和 PMC 自动获取入口。
7. 核验 PDF 的格式、身份、正文和版本。
8. 建立可追溯的文献目录和处理记录。
9. 按失败环节排查问题，依据清单继续未完成任务。

资料包含 **1 张封面、7 张操作图、9 组任务提示词、示例 CSV 和可编辑 SVG**。

## 第一次练习

先安装并配置 Hermes，完成教程第二节的工具与文件读写检查。之后打开 [图文文章的第三节](docs/guide.md)，将单篇下载提示词发送到 Hermes 聊天框。

确认 PDF 真实保存、可以打开，并且清单记录来源与路径后，再使用 [示例清单](examples/papers.csv) 练习批量任务。

![第一次下载路线](images/01-route.png)

## 资料目录

```text
README.md
index.html                       在线图文阅读页面
docs/guide.md                    完整公众号文章
docs/usage.md                    阅读、练习与公众号排版说明
docs/cover-generation.txt        封面生成方式与提示词
images/                          封面及七张操作图 PNG
figures/                         七张操作图的可编辑 SVG
prompts/tasks.txt                九组可复制操作提示词
examples/papers.csv              文献清单输入示例
downloads/hermes-guide.pdf       图文 PDF
downloads/hermes-guide-package.zip  完整资料包
CHECKSUMS.sha256                 文件完整性校验清单
```

## 版本和验证范围

官方文档核对日期：**2026 年 10 月 1 日**。

配图为 AI 插画、流程或界面结构示意，不是 Hermes 实际截图或真实下载记录。任务提示词为操作模板，Hermes 下载流程尚未在本机实测。

本次资料已检查正文、配图引用、手机页面显示、PDF 页数与可读文本、资料包完整性。实际执行结果仍需在使用者的 Hermes 环境中核验。

## 原始依据

正文在对应操作旁保留官方来源链接。主要依据包括：

- [Hermes Agent 官方文档](https://hermes-agent.nousresearch.com/docs/)
- [PubMed 帮助](https://pubmed.ncbi.nlm.nih.gov/help/)
- [PMC 开发者文档](https://pmc.ncbi.nlm.nih.gov/tools/developers/)
- [arXiv API 使用条款](https://info.arxiv.org/help/api/tou.html)
- [Unpaywall 数据格式](https://unpaywall.org/data-format)
- [Zotero 操作说明](https://www.zotero.org/support/adding_items_to_zotero)

本仓库是一份独立教程，不代表 Nous Research 官方发布。示例清单仅含公开题录与标识符，未附带研究论文全文。
