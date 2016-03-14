# 百度ife第一次任务

该项目用于百度ife第一次任务协作之用.

所属团队:兴趣使然的前端小组.

任务列表如下:

 - [ ] [零基础HTML编码](http://ife.baidu.com/task/detail?taskId=1)
 - [ ] [零基础HTML及CSS编码（一）](http://ife.baidu.com/task/detail?taskId=2)
 - [ ] [三栏式布局](http://ife.baidu.com/task/detail?taskId=3)
 - [ ] [定位和居中问题](http://ife.baidu.com/task/detail?taskId=4)
 - [ ] [零基础HTML及CSS编码（二）](http://ife.baidu.com/task/detail?taskId=5)
 - [ ] [通过HTML及CSS模拟报纸排版](http://ife.baidu.com/task/detail?taskId=6)
 - [ ] [实现常见的技术产品官网的页面架构及样式布局](http://ife.baidu.com/task/detail?taskId=7)
 - [ ] [响应式网格（栅格化）布局](http://ife.baidu.com/task/detail?taskId=8)
 - [ ] [使用HTML/CSS实现一个复杂页面](http://ife.baidu.com/task/detail?taskId=9)
 - [ ] [Flexbox 布局练习](http://ife.baidu.com/task/detail?taskId=10)
 - [ ] [移动Web页面布局实践](http://ife.baidu.com/task/detail?taskId=11)
 - [ ] [学习CSS 3的新特性](http://ife.baidu.com/task/detail?taskId=12)

团队协作工作流程:

团队五名成员需要建立自己的分支并在自己的分支上进行修改,哪个人做哪个任务不做具体要求.

建立分支的方法,如建立分支"test1"

```
git checkout -b test1
```

然后运行`git branch`就能看到自己新建的分支了.当前编辑的分支前面会有一个*符号.

*提示:切换分支时,使用*`git checkout <分支名>`*.新建一个分支但不跳转到这个分支,运行*`git branch <要新建的分支名>`

然后进行自己的修改,修改完成后执行三条命令:(建议在项目根目录下面)

```
git add --all
git commit -m "在这里写一些能够描述你修改的信息,可以是中文"
git push origin <你自己的分支名>
```

接下来你就能在github上看到你自己的分支里面的内容更新了.

当你希望将自己的分支合并到主分支时(主分支的代码为我们所提交的最终版本的代码),先在github网站上切换到你自己的分支,分支切换的下拉菜单旁边有一个**New pull request**按钮,点击并且创建一个pull request,这样大家就可以在pull request那里看到你的代码了,通过了解,最终决定是否合并到主分支上面.
