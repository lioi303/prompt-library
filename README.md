# Prompt Library

每个模板都是独立 Markdown 文件：复制后填写 `{{变量}}` 即可使用。按文件名或标签搜索。

## 使用

1. 选与任务最接近的模板。
2. 只填写 `{{变量}}`；没有的信息删掉对应要求，别编造。
3. 有效的改动直接回写到该模板，保留一条简短的变更说明。

## 分类

- `writing/`：写作、改写、翻译
- `work/`：会议、决策、规划
- `analysis/`：研究、对比、抽取
- `coding/`：调试、评审

## 建议的版本管理

在此目录执行 `git init` 后，每次改进模板提交一次：`git add . && git commit -m "improve rewrite template"`。

## 新模板规范

从 [_templates/prompt-template.md](_templates/prompt-template.md) 复制；一个模板只解决一个任务。
