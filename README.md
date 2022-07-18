# ouStanz.github.io

## introduce
ouStanz.github.io 下的hexo 分支，存放的是hexo的开发文件，在任意电脑上可以通过`git clone`来克隆文件并部署开发

## source 文件夹
source 文件夹内的内容单独保存在一个typero- 版本库中，需要单独clone

## submodule

添加typora-目录为子模块，要想获取需要使用如下方式

```md
递归克隆整个项目  git clone [子模块url][子模块名] --recursive
或者是使用如下方式
	git submodule update --init recursive
	
这等同于
	git submoduel init 
	git submodule update
	
如果有多个子模块
	git submodule foreach git init\update\pull等 
```



