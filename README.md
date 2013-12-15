# BUAAthesis

北航毕设论文LaTeX模板

## 项目说明

这是北航开源俱乐部开发并维护的的北航毕设论文的LaTeX模板，旨在满足学校教务处和研究生院规定和要求的基础上，提供一个简单易用的
tex模板，解决各位同学对于论文格式的烦恼，提高论文效率。

## 模板使用简介

### 软件环境

####编译环境要求

1、Windows用户：
使用[CTEX](http://www.ctex.org/HomePage "CTEX")套装；
或者更为推荐使用[TeXLive](http://www.tug.org/texlive/)2012以上版本+[texmaker](https://code.google.com/p/texmaker/)编辑器。

2、Linux用户：
推荐使用[TeXLive](http://www.tug.org/texlive/)2012以上版本。

3、Mac用户：
推荐使用[MacTex](http://tug.org/mactex/)2012及以上版本。

#### 其他要求

字体要求：华文行楷字体、宋体、黑体、隶书、仿宋和Times New Roman，以及其他因为论文需要所使用的字体。

参考文献管理工具：推荐使用[JabRef](jabref.sourceforge.net/download.php)。


### 编译过程及方式

编译方式：xelatex

完整编译过程：xelatex -> bibtex -> xelatex -> xelatex

注：当涉及交叉引用的改动时，需要xelatex编译两遍；涉及参考文献的改动时，需要完整编译过程编译；若二者均无涉及时，仅xelatex编译一遍即可。

或者，在windows下可以使用msmake.bat脚本，在linux下使用makefile脚本来进行编译。

## 免责声明

本模板为BHOSC开源爱好者使用tex代码，基于[北航研究生撰写学位论文的规定](http://graduate.buaa.edu.cn/ch/u/cms/www/201301/10175613d292.doc)
与 北航本科生毕业设计(论文)撰写规范及要求 的规定和要求而编写，由于学校教务处和研究生院给出的规范和规定均基于Word特性，与tex有一定的
差别，因此本模板在代码编写上也尽量满足教程处及研究生院的规定。由于TeX和Word的不同，也使得本模板并不能完全按照教务处及研究生院给出的规定
所设计，而是加入了代码编写者的一些主观猜测，但并不影响模板的正常使用。

本模板并未得到学校教务处及研究生院的承认和认可，教务处和研究生院也不会发布Word或TeX模板，本模板仅为开源爱好者的爱好和开源奉献精神
而作，但由此所引发的可能的问题，BHOSC对此并不负责。

## 联系我们
Google Group : https://groups.google.com/d/forum/beihang-open-source-club
