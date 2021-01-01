---
toc:
  depth_from: 1
  depth_to: 6
  ordered: true

html:
  embed_local_images: true
  embed_svg: true
  offline: false
  toc: true

print_background: false
---
# title
## title
### title
# markdown基本用法
啊啊啊**粗体**啊啊啊
啊啊啊 __粗体__ 啊啊啊
_斜体_
*斜体*
*__粗斜体__* 
e^2^
H~2~
==标记==
Content [^1]
[^1]: 脚注

![图片](/images/logo.png)
![不存在](https://ciphermanager.github.io/webnav/favicon.ico)
## 表格
Header1|Header2
---|---
data11|data12
data21|data22

Header1|Header2
---|---
data11|data12
^|data22

Header1|Header2
---|---
>|data12
data21|data22

头1|头2|头3
:--:|:--|--:
居中|左对齐|右对齐

[链接](https://github.com)
引用：
> We're living the future so
> the present is our past.

___
分割线
***

行内代码`<addr>` 才对。
代码块：
```python{.line-numbers}
def add(a,b):
    return a+b
```
任务列表
- [x] done!
- [ ] next do

_[HTML]: Hyper Text Markup Language
_[W3C]: World Wide Web Consortium
The HTML specification
is maintained by the W3C.


# 数学公式
[参考](https://blog.csdn.net/weixin_43786241/article/details/106583093)

[参考2](https://lolimay.cn/2019/01/22/katex语法测试/)

## 公式分隔符
行内 $s$  \(a\)
块级
$$s$$  \[a\]
```math
a
```
## 分隔符
```math
normal\bold{bold} 加粗\\
\space	 	空格\\
\quad		退一格\\
a\qquad a	退两格\\


```

## 字母与Unicode

```math
\Alpha|\alpha

\Alpha|\alpha
```


## 字母符号表示
## 矩阵 空间排列

## 逻辑与集合
## 运算符

# 图表

## Flow Charts

## Sequence Diagrams
## Mermaid