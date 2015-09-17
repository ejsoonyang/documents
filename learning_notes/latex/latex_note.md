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
