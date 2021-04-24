# Change Log

## [3.0.3] - 2021.4.24
- 大封面及中文封面填空处加粗
- 完善对工程硕士学位论文的支持
- 增加华文中宋字体的支持



## [3.1.0] - TODO

<!-- TODO 更改章节字号 -->
### Changed
- [ ] 更新东南大学版权声明
- [ ] 更改章节字号
- [ ] 更改图名编码方式(可能不需求)
- [ ] 增加表格样式的包

## [3.0.1] - 2019-12-16

### Changed
- 页边距设置为 2cm
- 最后的参考文献加中括号



## [3.0.2] - 2019-12-16

### Debuged
- 参考文献字号设置为小五

## [3.0.1] - 2019-12-12

### Debuged
- 术语与符号约定目录页码不对

## [3.0.0] - 2019-10-06

### Added
- 增加本地字体

### Changed
- 加载config文件夹中字体
- 标题黑体加粗
- 更新vscode编译方式
- seu论文声明和版权格式


## [2.0.0] - 2019-06-28

### Changed
- 将seuthesiY.cls的继承从ctexrep更改为ctexbook

### Fixed
- 奇偶页页眉显示方式，将奇数页页眉`东南大学..学位论文`更改到偶数页
- 摘要定义方式
- `\mainmatter`定义方式
- 致谢和简历的章节定义方式

### Added
- `\backmatter`命令

## [1.0.2] - 2019-06-23

### Changed
- 采用了[biblatex-gb7714-2015](https://github.com/hushidong/biblatex-gb7714-2015)替代[seuthesix](https://github.com/zhimengfan1990/seuthesix)提供的参考文献格式

### Fixed
- 封皮夹缝中文标题带英文.
- 有`术语与数学符号约定`时的编译方式

