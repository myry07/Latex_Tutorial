# Latex_Tutorial

1.引入
1.1 创建
\documentclass{...} 声明了文档类型 简历: CV
然后\begin{document} 和 \end{document} 在中间写文字

\documentclass[12pt, letterpaper]{article}
12pt 设置字体大小
letterpaper 设置纸张大小

2.2 抬头 作者 日期

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
 
隐藏页码
 \pagenumbering{gobble}
显示页码
\pagenumbering{arabic}


3. 添加备注 不生成
%


4. 加粗 斜体 下划线
加粗
\textbf{...}

下划
\underline{...} 

斜体 
\textit{...}


6. 添加图片
