# kaogong-workbench-data · 题库数据（私有）

考公工作台的题库数据备份，配合 [kaogong-workbench](https://github.com/1422671081-hub/kaogong-workbench) 使用。

## 内容

- `questions.json` —— 全部 43867 题（含答案/解析/分类），约 76MB
- `img_part1.zip ~ img_partN.zip` —— 4181 张题目配图（已压缩 JPEG），解压后合计约 225MB

## 换电脑恢复步骤

1. clone 本仓库
2. 解压全部 `img_part*.zip` 到同一个 `img/` 文件夹
3. 目录结构放成：

```
考公工作台/
├── 考公工作台.html   （从 kaogong-workbench 仓库的构建输出，或用 local_store.py build 重新生成）
└── img/              （解压出来的图片）
```

4. 双击 考公工作台.html 即可刷题

## 更新数据

AI 录入新卷子后重新生成 questions.json 与图片压缩包，commit + push 即可。
