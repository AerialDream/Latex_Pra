# **Basic Of Latex**

## **从提纲开始**

```latex
\documentclass[UTF8]{ctexart}

\title{杂谈勾股定理}
\author{张三}
\date{\today}

\bibliographystyle{plain}  %声明参考文献的格式
%在\begin{document}之前的部分称为导言区
\begin{document}  %声明[document]环境

\maketitle  %实际输出论文标题
\tableofcontents  %输出目录
\section{勾股定理在古代}  %开始新的一节
\section{勾股定理的近代形式}
\bibliography{math}  %从文献数据库[math]中获取文献信息，打印参考文献列表

\end{document}
```

- **提纲部分写完，接下来开始写正文部分。**

------

## 正文

### **填写正文**

```latex
\begin{document}

\section{勾股定理在古代}
西方称勾股定理为毕达哥拉斯定理，将勾股定理的发现归功于公园前6世纪的毕达哥拉斯学派。 %使用空行分段

我国《周髀算经》载商高（约公元前12世纪）答周公问...  %段前不用打空格，会自动完成文字的缩进
```

### **命令与环境**

```latex
见于欧几里得\footnote{欧几里得，约公元前 330--275 年。}《几何原本》
%[\footnote{}]是脚注的命令，花括号里是脚注的内容。

整数称为\emph{勾股数}  %[\emph]表示强调的内容

答周公问：
\begin{quote}  %引用的内容
\zihao{-5}\kaishu 勾广三，股修四  %注意用空格把后面的文字分开
\end{quote}

\begin{abstract}  %摘要在\maketitle之后用[abstract]环境生成
这是一篇关于勾股定理的小短文
\end{abstract}
```

