# Latex_Tutorial

1.引入
1.1 创建
\documentclass{...} 声明了文档类型 简历: CV

然后\begin{document} 和 \end{document} 在中间写文字

\documentclass[12pt, letterpaper]{article}
12pt 设置字体大小
letterpaper 设置纸张大小

1.2 抬头 作者 日期

抬头
\title{...}

作者
\author{...\thanks{...}}
(\thanks{...} -> *号 并且在末尾增加描述)
\date{...}


标题
\maketitle

创建新一页
 \newpage
 
吞掉页码
 \pagenumbering{gobble}
显示页码
\pagenumbering{arabic}

添加备注 不生成
%

加粗
\textbf{...}

下划
\underline{...} 

斜体 
\textit{...}

增加行距 \vspace{5cm}
增加间距 \hspace{5cm}

2. 章节
2.1 添加目录
主目录 \section{...}
副目录\subsection{...}

2.2 添加条款
主条款\paragraph{...}
副条款\paragraph{...}


3. 包
Linux Mac通常默认安装

4. 数学
equation环境
\begin{equation*}.....\end{equation*}
只能输入一个等式

align环境
\begin{align*}...\end{align*}
&对齐方程 \\换行

fraction倒数\frac{1}{x}
integrate积分\int^a_b
sqrt根号\sqrt{x}

5. 图片
所需要的图片 放在 .tex文件同样的目录下
使用包 \usepackage{graphicx}

begin{figure}[b!]...\end{figure}

 添加描述\caption{...}
 
h (here) – same location
t (top) – top of page
b (bottom) – bottom of page
p (page) – on an extra page
! (override) – will force the specified location

多张照片
使用包\usepackage{subcaption}

