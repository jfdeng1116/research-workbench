# Research Workbench

低轨卫星网络方向的研究工作台：写作、整理、汇报的**方法与模板**集中在这里，具体研究内容与数据放在私有仓 [`research-lab`](https://github.com/jfdeng1116/research-lab)。

## 目录

| 目录 | 放什么 | 不放什么 |
| --- | --- | --- |
| [`01-writing/`](01-writing/) | 期刊模板、术语表、投稿检查清单、写作提示词 | 论文正文草稿 |
| [`02-docs/`](02-docs/) | 文件命名规范、纪要/实验记录/周报模板、文献库 | 原始数据 |
| [`03-slides/`](03-slides/) | 答辩 / 组会 / 会议报告模板与素材 | 大体积视频 |

## 使用方式

1. **写论文** → 从 [`01-writing/journal-templates/`](01-writing/journal-templates/) 取模板，正文统一术语见 [`glossary.md`](01-writing/glossary.md)
2. **交稿前** → 逐项过 [`submission-checklist.md`](01-writing/submission-checklist.md)
3. **建新文档** → 先看 [`02-docs/naming.md`](02-docs/naming.md) 再建文件
4. **要做汇报** → 从 [`03-slides/templates/`](03-slides/templates/) 取版式

## 目标期刊

- 《宇航学报》
- 《通信学报》
- 《电子学报》

> 各刊格式细节以官方投稿须知为准。本仓模板只提供一个不断完善的起点，不作为格式依据。

## 约定

- 本仓**公开**，因此只放方法与模板，不放未发表内容、实验数据、审稿意见。
- 目录结构由各级 `README.md` 说明「放什么 / 不放什么」，新增目录必须补 README。
- 大文件不进 Git：`*.pdf`、`*.docx`、`*.mat`、`*.bag` 已在 `.gitignore` 中排除。
