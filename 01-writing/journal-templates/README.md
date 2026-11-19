# 期刊排版模板

## 目录约定

```
journal-templates/
├─ acta-astronautica-sinica/   # 宇航学报
├─ journal-on-communications/  # 通信学报
└─ acta-electronica-sinica/    # 电子学报
```

每个子目录至少包含：

| 文件 | 说明 |
| --- | --- |
| `template.tex` | LaTeX 骨架（若有官方 cls，放同目录） |
| `template.docx` | Word 版，自己按投稿须知调好样式 |
| `NOTES.md` | 记录该刊的特殊要求、投稿系统、审稿周期、注意事项 |

## 重要提醒

模板里**不要抄官方 cls**。官方类文件受版权保护且有版本更新，正确做法是在 `NOTES.md` 里写清下载地址和版本，用 `.gitignore` 排除，本地自己放。

仓库只保留：你自写的样式调整、章节骨架、图表命令封装。

## 待办

- [ ] 三刊 `NOTES.md` 初建（先填已知信息，不编着写）
- [ ] 通用 preamble（中文支持 / 公式 / 三线表 / 图包）
