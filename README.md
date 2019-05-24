# gitignore
## 目录
[TOC]

### 1.作用
.gitignore文件配置匹配规则后可忽略部分文件的上传.
### 2.忽略文件的原则
1> 忽略编译系统自动生成的文件, 比如缩略图等;

2> 忽略编译生成的中间文件, 可执行文件.

3>  忽略带有敏感信息的配置文件.

### 3.强制提交被忽略的文件
git rm filename --cached
### 4.忽略文件配置规则
忽略指定文件 : config.php 

忽略指定文件夹: config/

忽略某一类文件(例如 '.class'文件) : *.class

忽略名称中已ignore结尾的文件:  *ingore/

忽略文件名称中包含ignore 的文件:  * ingore */

忽略文件夹名称中以ignore结尾的的文件夹:  *ingore/