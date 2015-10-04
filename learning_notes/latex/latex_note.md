添加sty包
---
路徑：
/usr/local/texlive/2014/texmf-dist/tex/

還需要運行命令：
texhash

自由設置字體
---
\setCJKfamily{kai}{標楷體}
在文中需要的地方鍵入
\CJKfamily{kai} 
恢復默認字體
\rmfamily

自由設置字號
---
如果需要 48pt 的字号，那么需要用 \fontsize 命令。用法是
    \fontsize{<实际字号>}{<基础行距>}\selectfont
比如：
    \documentclass{article}
    \begin{document}
    \fontsize{48pt}{57.6pt}\selectfont
    48pt Fonts.
    \end{document}
这里 48pt 是实际的字号大小。
