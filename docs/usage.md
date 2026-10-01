# 阅读、练习与公众号排版

## 阅读

- 在 GitHub 中打开 docs/guide.md，可直接查看带配图的完整文章。
- 通过仓库 About 栏的 Website 入口打开在线阅读页面；页面支持复制命令和提示词。
- 下载 downloads/hermes-guide.pdf，可用于手机或电脑阅读和分享。
- 下载完整素材包并解压；保持目录结构，打开 index.html 进行离线阅读。

## 跟着练习

1. 使用你自己的 Hermes 环境，完成模型、工具和文件保存检查。
2. 打开 prompts/tasks.txt，选择单篇下载任务，发送到 Hermes 聊天框。
3. 自己打开取得的 PDF，并检查清单中的来源、路径和版本。
4. 把 examples/papers.csv 放到 Hermes 工作目录，先要求报告行数与核对题录，再进行清单获取练习。
5. 替换为自己的文献清单，先做小批量处理。
6. 云端或容器中的文件需要按实际运行环境取回。

安装和配置命令输入电脑终端或 PowerShell；论文获取任务提示词输入 Hermes 聊天框。

## 公众号排版

正文在 docs/guide.md；图片在 images。按正文图号上传：

- 00-cover.png：封面
- 01-route.png：第一次下载流程
- 02-input.png：终端与聊天框的区别
- 03-first-paper.png：单篇下载练习
- 04-fulltext.png：全文获取路径
- 05-verify.png：PDF 四项核验
- 06-archive.png：文件夹与清单归档
- 07-troubleshoot.png：任务卡住时排查顺序

正文、提示词、命令和来源链接均可编辑。不同公众号编辑器对网页图片粘贴的支持可能不同，请检查图片是否显示。

编辑操作图可使用 figures 中的 SVG；封面生成方式和提示词见 docs/cover-generation.txt。保留图示说明，避免将其表述为软件截图或真实下载结果。

## 下载资料包与文件校验

CHECKSUMS.sha256 记录仓库内容文件的 SHA-256；不包含清单自身、Git 数据和资料包 ZIP，以避免自引用。

ZIP 已检查完整性，并保留相同的文章、配图、示例文件和 PDF。
