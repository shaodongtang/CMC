# CMC

#### CMC的介绍
中国大学生数学竞赛LaTeX模板。如果你有其他问题、建议或者报告 bug，可以提交 issues 或者给我发邮件：shaodongtang@gmail.com。

#### 宏包的安装教程

1. cmc.sty放入 \texlive\texmf-local\tex\latex\local 然后 texhash
2. 安装mtpro2数学字体参考 http://www.latexstudio.net/archives/241.html 以及texlive安装MTPro2.mp4
3. varint宏包（最新版本已删除）参考 http://www.latexstudio.net/archives/771.html

#### 模板的使用说明

1. CMC宏包使用说明见 CMC_guide.tex
2. 模板例子见 17mathSJ_1028.tex
3. 文档中文字体：华文行楷、华文中宋、思源字体、adobe 楷体、adobe 黑体、adobe 仿宋、adobe 宋体
4. 文档英文字体：Times New Roman Bold Italic（好像没啥用）
5. 数学类字体：mtpro2宏包（需安装）

#### CMC.sty版本历史

1. v1.00 见 http://www.latexstudio.net/archives/11363.html
2. v1.10 引入数学字体宏包mtpro2 见 http://www.latexstudio.net/archives/51505.html
3. v1.20 见 http://www.latexstudio.net/archives/51635.html

#### 最新版本的修改说明

1. 加入result=noanswer（试卷），result=answer（答案）可选参数；
2. 装订线命令修改（0cm为默认，\defen{得分}）\defen[2cm]{得分}、\score[2cm]{得分}；
3. 大题命令修改为\dati{题目}

