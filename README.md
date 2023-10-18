包里包含了多种可能涉及到版权问题的字体。

有衬线：SIMFANG（仿宋），SIMSUN，SIMKAI，（楷体：GB2312，SIMKAI），Courier New

无衬线体：Helvetica，SIMHEI（黑体）Times New Roman

等宽字体：Helvetica，Courier New，



```latex
%！xeltaex，utf-8

\usefonttheme{professionalfonts} % 使用非标准字体
\usefonttheme{serif}

%%%%%%%% 设置中文字体 %%%%%%%%%%
\usepackage{xeCJK} %导入中文包
\setCJKmainfont{SIMSUN.TTC}[AutoFakeSlant,AutoFakeBold,Path=fonts/]
\setCJKsansfont{SIMFANG.TTF}[AutoFakeSlant,AutoFakeBold,Path=fonts/]
\setCJKmonofont{SIMKAI.TTF}[AutoFakeSlant,AutoFakeBold,Path=fonts/]

%%%%%%%% 设置英文字体 %%%%%%%%%%
\usepackage{fontspec}
\setmainfont{Times New Roman}[AutoFakeSlant,AutoFakeBold,Path=fonts/]
\setsansfont{Helvetica.ttc}[AutoFakeSlant,AutoFakeBold,Path=fonts/]
\setmonofont{Courier New}[AutoFakeSlant,AutoFakeBold,Path=fonts/]
```
```latex
%！xeltaex，utf-8
\text{中午\fontname\font}%显示当前字体格式
```
