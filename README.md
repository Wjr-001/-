包里包含了多种可能涉及到版权问题的字体。

有衬线：SIMFANG（仿宋），SIMSUN，SIMKAI，（楷体：GB2312，SIMKAI）

无衬线体：Helvetica，SIMHEI（黑体）

等宽字体：Helvetica



```latex
%！xeltaex，utf-8

%%%%%%%% 设置中文字体 %%%%%%%%%%
\setCJKmainfont{SIMSUN.TTC}[AutoFakeSlant,AutoFakeBold,Path=fonts/]
\setCJKsansfont{SIMHEI.TTF}[AutoFakeSlant,AutoFakeBold,Path=fonts/]


%%%%%%%% 设置英文字体 %%%%%%%%%%
\usepackage{fontspec}
\setmainfont{Times New Roman}
\setsansfont{Helvetica.ttc}[Path=fonts/]
```

