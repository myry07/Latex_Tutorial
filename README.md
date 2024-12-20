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

2. 章节
2.1 添加目录
主目录 \section{...}
副目录\subsection{...}

2.2 添加条款
主条款\paragraph{...}
副条款\paragraph{...}


4. 加粗 斜体 下划线
加粗
\textbf{...}

下划
\underline{...} 

斜体 
\textit{...}


6. 添加图片
