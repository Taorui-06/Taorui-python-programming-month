# 问题日志 PROBLEM_LOG

每一个报错都值得记一笔。**格式固定为：现象 → 原因 → 解决 → 收获**，编号递增。

这样一个月下来回头看，会发现自己踩的坑其实集中在少数几类。

---

### #001 `git commit` 报错 `Please tell me who you are`

- **现象**：第一次提交时提示 `Author identity unknown`，提交失败
- **原因**：Git 需要知道每次提交的作者是谁，本机还没配 `user.name` 和 `user.email`
- **解决**：
  ```bash
  git config --global user.name "Taorui"
  git config --global user.email "你的邮箱"
  ```
- **收获**：Git 的配置分全局（`--global`，对本机所有仓库生效）和仓库级（不加参数，只对当前仓库生效）

---

### #002 示例：`IndentationError: unexpected indent`

- **现象**：代码看着没问题，一运行就报缩进错误
- **原因**：Python 靠缩进划分代码块，同一层级的语句必须左对齐，TAB 和空格混用也会出问题
- **解决**：编辑器设置为"用空格代替 TAB"，统一 4 个空格
- **收获**：Python 里缩进是语法的一部分，不是排版

---

<!-- 模板

### #00N 一句话标题

- **现象**：
- **原因**：
- **解决**：
- **收获**：

-->
