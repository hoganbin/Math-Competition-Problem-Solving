 ![](https://img.shields.io/badge/Language-TeX-yellow.svg)![](https://img.shields.io/badge/version-0.1-red.svg)![](https://img.shields.io/github/last-commit/hoganbin/TeX-degree-template-making.svg)![](https://img.shields.io/github/repo-size/hoganbin/TeX-degree-template-making.svg)![](https://img.shields.io/github/languages/code-size/hoganbin/TeX-degree-template-making.svg)![](https://img.shields.io/github/followers/hoganbin.svg?label=Follow)

# Math-Competition-Problem-Solving

完善蒲和平大学生数学竞赛课后习题解析

###分工

- 第一章（八一）
- 第二章（朝信）
- 第三章（静安）
- 第四章（蛋蛋）
- 第五章（刘力手，杨彦坡）
- 第六章（帅帅，董朔，闫皖民）
- 第七章（周星，宋洋）
- 第八章（田文涛 ，yh）

###排版约定

1. **中英文之间一定要加空格！！！**
2. 标点符号全部使用英文符号，文本模式中，标点符号后需要加空格
3. 行内数学模式内，分数用 `\tfrac` 或者 `/`，行间公式用 `\frac` 或者 `\dfrac`
4. 使用 `\leqslant` 和 `\leq` 均可
5. 自然对数底定义新命令 `\newcommand{\ee}{\mathrm e}` 在指数形式比较复杂时，用 `\exp` 表示自然对数这
6. 关键词用 `\textbf{关键词}`，然后建立索引 `\index{G!关键词}` `G` 表示名词首字母用于排序，`!` 后面的就是关键词的名字
7. 积分里面的微分符号 `d` 定义为`\newcommand{\dd}{\,d}` 输入的时候就输入 `\dd`，这样即便有必要改为正体也容易
8. 数学公式中，使用 `\ldots` 进行罗列，如果两边是操作符，用 `\cdots`
9. 交叉引用-引用
   - 使用`~\ref{label}` 进行引用，注意空格，示例：`在表~\ref{tab:3.1.2} 中...`
10. 公式里面距离，一般距离用 `\;`，然后大距离用 `\quad` 或者 `\qquad`（基本用 `\quad`）

###几点说明

____

1. 蒲和平更侧重于学生的计算能力，针对于那些报考`华中科技大学`、`天津大学`、`兰州大学`、`大连理工大学`与`电子科技大学`等院校的同学可以在考研期间可参考蒲和平数学竞赛教程；
2. 对准备`第十一届全国大学数学竞赛`可以说是很好的辅导资料，当然基础不好的同学用陈兆斗也没问题，基础好的同学除了蒲和平，也可以选择裴礼文与陈纪修等人的数分辅导资料，对你参加数学竞赛来说是有益的；
3. 单第1章就有98道，整本书下来至少题量保证700-850道之间。我计划是先一道题一道解答这样进行解析，大概如果把八章内容解析全部写完，预估是大概要写到400页左右，这本书完整解析的工程量巨大。

这里我征稿一下，如果有愿意帮我一同做蒲和平数学竞赛解析的同学，可与我邮箱联系hoganbin1995@outlook.com，这个项目会让你锻炼到通过LaTeX排版书籍，同时可以很快地让你熟悉github操作，谢谢支持！

### 贡献

如果您有任何改进意见或者功能需求，欢迎提交 [issue](https://github.com/stone-zeng/fduthesis/issues) 或 [pull request](https://github.com/stone-zeng/fduthesis/pulls)。

### 许可证

本模板的发布遵守 [LaTeX Project Public License](http://www.latex-project.org/lppl.txt)（版本 1.3c 或更高）

### Contributing

[Issues](https://github.com/stone-zeng/fduthesis/issues) and [pull requests](https://github.com/stone-zeng/fduthesis/pulls) are always welcome.

### License

This work may be distributed and/or modified under the conditions of the [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), either version 1.3c of this license or (at your option) any later version.

------

Copyright (C) 2019-2021 by hoganbin.

......

......

#其他工具效率推荐

1. notepad++ 文本编辑器
2. VSCode  前端编辑器/文本编辑器
3. f.lux 护眼工具
4. 火萤酱 快速搜索工具，功能自己摸索吧。 打开快捷键：CTrl+Q  自定义设置
5. mathpix  截图latex公式转化 
6. screenshot 截图文字转化或同声翻译
7. Snipaste 一个简单但强大的贴图工具，同时也可以执行截屏、标注等功能。 打开快捷键：F1 
8. PicGo 呢？—— 图床客户端。
9. 幕布—— 文档管理+思维导图。

- 关于如何设置软件开机自启。把你需要开机自启的软件.exe创建快捷方式，然后剪切在命令行输shell:startup复制到该文件夹中，最后你在命令行输入msconfig就会发现在你的启动程序项目就有你设置的软件。

好了，我暂时就推荐这么几个工具给大家。回到 Git 教学。

#开始安装Git

打开Git的官方网站，下载下来之后安装时选择默认选项即可

安装完成之后，在任意位置点击鼠标右键，菜单栏里看到**Git Bash**代表安装完成

安装完成后，还需要最后一步设置，在命令行输入：

**$ git config --global user.name"Your Name"**

**$ git config --global user.email"email@example.com"**

注意 git config 命令的 --global 参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。

------

### 使用 Git 和 GitHub 步骤：

_________

提前推荐个软件，你在用的：`typora/sumline/VS-vode/notepad++`。

1. 先配置 SSH（一个协议）。请看演示
   1. 电脑 Git Bash： ssh-keygen -t rsa  过程中，回车即可。
   2. 打开github--> setting --> SSH,添加 SSH  public 文件内容。
      测试下：ssh git@github.com 看到：You've successfully authenticated 表示成功。
2. 可以使用 Git 命令玩了。 就是这么简单。经常用的命令就是如下几个：
   1. git status 查看本地仓库状态
   2. git add .   添加所有改动到暂缓区，git add a.txt 这是添加a.txt单个文件
   3. git commit -m "你的注释说明"
   4. git push 提交到GitHub

如何使用 Git 提交自己的文件到 GitHub？

```
1. 选择仓库的 ssh 的地址
2. 克隆(下载),比如：git clone git@github.com:mathflow/LaTex_Notes.git可以看到克隆下来后有个.git 后缀隐藏文件，即为记录本地仓库的一切改动。
3. 切换到仓库目录
4. 修改
5. git add .
6. git commit - m "注释说明"
7. git push 提交到远程服务器GitHub
注：随时可以使用 git status 查看仓库状态。另外，git branch -a 查看和
	远程服务器关联情况。
这个期间应该会要求你配置下name和email的，你这里肯定是你之前已经配置过了。
```

#如何使用 GitHub 作为图床？

1. Github上新建一个仓库，作为存储图片的。（仓库私有、公有，随你吧）
2. 新建 token，比如这是你的：8692ec2d94698d7cc14408257ee5bf4e***..
3. 在PicGo配置下即可。其中的，分支名设置为默认的：master即可

注1：我帮你设置的上传快捷键为 Ctrl+W(被占用了，你自己重新设置为自想要的吧)
注2：还是设置仓库为公有仓库吧，避免出现莫名其妙问题！
注3：上传成功之后，默认粘贴板的地址为这样的：![](https://raw.githubusercontent.com/mathflow/ImagesBed/master/images/20190202224740.jpg)

注4：如果要上传到仓库的文件夹 /images 下，在存储路径处设置为：/images。

注5：自定义域名不设置也行。
?	（但如果出问题，那就设置为这样的：
https://github.com/hoganbin/ImagesBed/blob/master，但前提是你的仓库是公开仓库）

注6：建议还是设置为时间戳重命名把，这样文件名称就为时间戳形式。

注7：使用github做图床，速度上你懂得，有点慢。每个仓库有1000g存储容量。

This team is mainly used for template making in universities. Welcome to LaTeX users!

TeX-degree-template-making

#Git 分支操作

1. 创立分支 test `git branch test`
2. 切换到分支 test `git checkout test`
3. 在分支下操作
   - 切换到 test 分支 `git checkout test`
   - 添加内容到暂存区 `git add chapterx.tex`
   - 提交到本地库 `git commit -m "commit msg"`
   - 提交到远程 test 分支 `git push origin test`
4. 更新主分支内容
   - 切换到主分支，`git checkout master`
   - 拉取主分支最新内容 `git pull`
   - 添加到暂存区 `git add files....`
   - 提交到本地库 `git commit -m "commit msg"`
   - 提交到远程 master 分支 `git push origin master`
5. 合并主分支更新的内容 有时候，主分支更新了内容，这时候想要把主分支的内容合并到 test 分支下：
   - 切换到 test 分支，`git checkout test`
   - 合并主分支，`git merge master`
   - 提交合并之后的 test 分支内容到远端 test 分支 `git push`

**注：** 为了让本地 test 分支能够 pull github 上的 test 分支的内容，需要设置远端分支。

```
git checkout test
git branch --set-upstream-to=origin/test
```

