---
layout: post
title: "有些文章太短了，只能让页脚固定在底部"
categories: 杂项
---

# 一级标题 `#`

## 二级标题 `##`

### 三级标题 `###`

---

## 📝 段落与格式

这是一个普通段落。可以**加粗**、*斜体*、~~删除线~~、以及`代码高亮`。

---

## 🔗 链接与图片

这是一个 [Jekyll 官网链接](https://jekyllrb.com/)

图片展示（本地或网络图片）：

![Jekyll Logo](https://jekyllrb.com/img/logo-2x.png)

---

## 🔢 列表

**无序列表：**

- 苹果 🍎
- 香蕉 🍌
  - 黄色
  - 有皮
- 西瓜 🍉

**有序列表：**

1. 第一步
2. 第二步
3. 第三步

---

## 📦 代码块（支持语法高亮）

**行内代码**：比如使用 `jekyll serve` 启动服务。

**多行代码（Python）：**

```python
def greet(name):
    print(f"Hello, {name}!")
```

**多行代码（C++）：**

```cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

---

## 📐 数学公式（需要启用 MathJax）

行内公式示例：爱因斯坦质能关系 $E = mc^2$

块级公式示例：

$$
\int_{-\infty}^\infty e^{-x^2} dx = \sqrt{\pi}
$$

---

## 📊 表格

| 姓名 | 年龄 | 城市     |
|------|------|----------|
| 张三 | 25   | 北京     |
| 李四 | 30   | 上海     |
| 王五 | 22   | 广州     |

---

## 📌 引用块

> 这是一个引用块，用于强调重要内容。

---

## 🧾 脚注示例

Markdown 脚注语法[^1] 是一种非常优雅的方式来提供额外注解。

[^1]: 这就是脚注的内容。

---

## 🧰 混合 HTML

你也可以直接在 Markdown 中嵌入 HTML：

<div style="color: red; font-weight: bold;">
这是红色加粗的 HTML 段落。
</div>

---

## ✅ 任务列表

- [x] 学习 Jekyll
- [x] 配置博客
- [ ] 撰写第一篇博客
- [ ] 部署到 GitHub Pages

---

## 🔄 折叠内容（需要主题支持）

<details>
  <summary>点击展开更多内容</summary>
  <p>这里是详细说明的内容，默认隐藏。</p>
</details>

---

## 🔗 锚点与跳转

你可以[点击这里跳转到代码块部分](#-代码块支持语法高亮)
