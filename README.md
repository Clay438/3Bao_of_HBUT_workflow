# 3BAO_OF_HBUT_WORKFLOW

![b](pic/b.png)

3BAO_OF_HBUT_WORKFLOW是一个旨在积极重构[思维导图](/templates/mindmap/)，[文献阅读](/templates/文献阅读/)，[每科三问](/templates/每科三问/)完成方式的项目，以便：

- 在ddl之前(通常位于期末周),以较短时间完成三宝，提高学习效率。

- 利用typst排版以便减少在word中遇到的排版问题

- 采用markdown格式编写mindmap,操作方便快速，利于扩展。

- 减少重复劳动，提高效率。

## Dependence

- [Typst](https://typst.app/docs/)

- [Markdown](https://markdown.com.cn/basic-syntax/)

- Xmind

- [pandoc](https://pandoc.org)

## Usage

---

### mindmap:

- 思维导图可以被以markdown格式写出，下面是一个示例：

```markdown
- Python基础
  - 语法
    - 变量
    - 数据类型
    - 运算符
  - 控制流
    - 条件语句
    - 循环
  - 函数
    - 定义和调用
    - 参数和返回值
    - 递归
- 数据结构
  - 列表
  - 元组
  - 字典
  - 集合
```

- 一旦完成markdown格式的mindmap，将该文件以markdown格式导入Xmind，导出为png

![a](/pic/a.png)
![c](/pic/c.png)

- 利用pandoc将png转换为pdf

### 文献阅读：

[利用typ模版](/templates/文献阅读/文献阅读表.typ)//（！！！未完成的模版！！！）

### 每科三问：

[利用typ模版](/templates/每科三问/每科三问.typ)//（！！！未完成的模版！！！）
