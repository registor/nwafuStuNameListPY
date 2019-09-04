# nwafuStuNameListPY
这是一个使用用xpinyin+pgfplotstable结合CSV文件实现学生名单加注拼音的LaTeX项目。

Happy LaTeXing！~

## 数据文件格式
数据存储于逗号分割的namelist.csv数据纯文本文件(*务必采用UTF8编码*)，该数据文件：

1. 该文件第1行是标题后续各行是具体数据

2. 前3列分别是学号、姓名、班级，最后一列是备注，建议不要更改标题名称

3. namelist.csv文件中数据可以为空，但逗号不能省略

4. namelist.csv数据文件结构示例如下：

```
﻿stno,name,class,1,2,3,4,5,6,7,8,9,10,11,12,notes
2019012800,许涵启,计算机类1905,,,,,,,,,,,,,
......
2019012830,云睿航,计算机类1905,,,,,,,,,,,,,
,,,,,,,,,,,,,,,
......
,,,,,,,,,,,,,,,

```

## 注意：

1. 本文档要求 TeXLive、MacTeX、MikTeX 不低于 2018 年的发行版，并且尽可能升级到最新，强烈建议使用TeXLive2019。

2. **不支持** [CTeX 套装](http://www.ctex.org/CTeXDownload)。
