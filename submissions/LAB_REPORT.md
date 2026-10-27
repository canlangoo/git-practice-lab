# 实验报告 / LAB_REPORT

> 做题者填写本文件后，随功能分支一并提交，并在 PR 中带上。

## 基本信息

- **GitHub 用户名：** canlangoo 
- **功能分支名：** `lab/canlangoo`
- **PR 链接：** 

## 阶段清单

- [x] Stage 0 — Fork、clone、upstream、创建 `lab/<username>`
- [x] Stage 1 — 工作区 / 暂存区 / commit
- [ ] Stage 2 — 分支、merge、冲突解决
- [ ] Stage 3 — 坏提交 + revert
- [ ] Stage 4 — 添加 submodule `third_party/kit`
- [ ] Stage 5 — fetch upstream、push、开 PR

## 简答题

### 1. 工作区、暂存区、已提交（commit）分别是什么？

工作区：正在编写的文件，其中作出的改动还未被git记录
暂存区：工作区完成改动的文件，下一次commit的快照
commit：写进历史，无法改变的快照


### 2. `git pull` 和 `git fetch` 有何不同？你通常何时用哪个？

<!-- 你的回答 -->

### 3. 什么情况下不应该对已推送的共享分支使用 `git reset --hard`？为什么？

<!-- 你的回答 -->

### 4. 带 submodule 的仓库 clone 后子目录是空的，常见原因是什么？怎么处理？

<!-- 你的回答 -->

## 关键 commit（填写短 hash 或完整 hash）

| 说明 | Hash |
|------|------|
| Stage 1 第一次较好的 commit |8e60e0defcf78f6efe0394143f9e0466f914e950 |
| Stage 2 冲突解决（或合并）commit | |
| Stage 3 revert 产生的 commit | |
| Stage 4 submodule add 的 commit | |

## Stage 2 补充

- 普通 merge 结果：□ 快进（fast-forward）　□ 合并提交（merge commit）　□ 其他：
- 冲突解决简述：

## Stage 5 补充

- 同步 `upstream/main` 时使用：□ merge　□ rebase
- 选择理由：

## 其他备注（可选）

<!-- 例如：只用了非交互式 add、环境限制、踩过的坑等 -->
