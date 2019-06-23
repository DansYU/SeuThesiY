## SeuThesiY

**SeuThesiY** 提供了一个用于排版东南大学硕博学位论文的LaTeX模板。该模板主要是在[seuthesix](https://github.com/zhimengfan1990/seuthesix)基础修改了参考文献排版，采用了[biblatex-gb7714-2015](https://github.com/hushidong/biblatex-gb7714-2015)替代[seuthesix](https://github.com/zhimengfan1990/seuthesix)提供的参考文献格式。


目前该模板支持博士、硕士学位论文。


## 功能特色
> 该模板除了参考文献其他功能特色均与[seuthesix](https://github.com/zhimengfan1990/seuthesix)相一致

* 参考文献采用SEU特有的GBT7714-2015格式
> 主要是硕博参考文献的形式, 需要在bib文件中加上type域，如：type={[博士学位论文]}

> 博士学位论文：周义炎. GPS 电离层反演与地震—电离层效应研究[D]. [博士学位论文]. 武汉: 武汉大学, 2015.
```tex
@PhdThesis{zhouGPS2015,
    langid = {中文;},
    title = {GPS电离层反演与地震—电离层效应研究},
    institution = {{武汉大学}},
    type={[博士学位论文]},
    urldate = {2019-05-14},
    date = {2015},
    author = {周, 义炎},
    location = {武汉},
}
```
> 硕士学位论文：余勇. 劲性混凝土柱抗震性能的试验研究[D]. [硕士学位论文]. 南京: 东南大学土木工程学院, 1998.
```tex
@Mastersthesis{余勇1998--,
    title = {劲性混凝土柱抗震性能的试验研究},
    author = {余勇},
    school = {东南大学土木工程学院},
    year = {1998},
    type={[硕士学位论文]},
    location = {南京},
}
```


## 编译方式
采用的编译方式为  **XELATEX -→  BIBER -→    XELATEX -→    XELATEX**
若使用vscode作为LaTeX编译器，可以使用.vscode/setting里面的配置文件



## License
[GPL](https://www.gnu.org/licenses/gpl-3.0.txt)


## 其他

原[seuthesix](https://github.com/zhimengfan1990/seuthesix)README

``` txt
This project provides a LaTeX document class: ``seuthesix''
for typesetting thesis of Southeast University, Nanjing, China.
This package provides three important files:
1. `seuthesix.cls'.
2. `seuthesix.cfg', this is the configuration file of seuthesix and
will be loaded by `seuthesix.cls' at runtime. This file must be in the same directory as
`seuthesix.cls'.
3. `seuthesix.bst', this is the accompanying bibliography style file
for `seuthesix.cls'.

Maintainer: James Fan
project homepage: https://github.com/zhimengfan1990/seuthesix
package version: 1.0.1
Copyright (c) 2007--2012 Xu Yuan, email: xuyuan.cn@gmail.com
Copyright (c) 2016 James Fan, email:zhimengfan1990@163.com
License: GNU General Public License, version 3(see LICENCE)

Note: This package is based on the package: ``seuthesis''
maintained by Xu Yuan(email: xuyuan.cn@gmail.com), 
which has many bugs now and not usable
due to lack of maintenance for many years.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```
