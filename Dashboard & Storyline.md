# Building a Dashboard

## Example 1

https://www.udemy.com/course/tableau10/learn/lecture/5618174#overviews

hierachy: city state country 拖拽到一起去

可以右键显示筛选器，可以右键自定义把all选项去掉并换成滑块型，这样可以移动滑块看数据随年份的变化

添加了一个度量 profit margin = sum(profits)/sum(sales)

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljnb4rd6xj31c00u0kjl.jpg)

将筛选用于所有的表中，这样一来新建并使用的工作表都会自动apply这个filter

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljppk272tj30oa0lyq52.jpg)



![](https://tva1.sinaimg.cn/large/0081Kckwly1gljpj73tn2j30m80ai78s.jpg)

scatterplot

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljprbvg3cj31c00u04dk.jpg)


## Create a Dashboard

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljpvv9bghj31c00u0dm1.jpg)

如果拖过来的图太大了，就回到这个图原来的worksheet去把图调小一点，也要调整一下仪表板中图的大小

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljq6k39x3j31c00u0nk0.jpg)

然后调整成滑块并应用到所有的图表里，这样这两个图都会随着filter里的数据一起变化了

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljq851um4j31c00u0x37.jpg)

## Adding Interactive Actions

要的效果: just simply click on map plot's bubble and then the scatterplot will automatically adjust to reflect.

There are 2 types of actions: filtering and highlighting.

### Filter

Dashboard -> action(操作)

但在这个case里，只需要用自动生成的action就可 总之就是：

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljqozz3gyj31c00u0kd6.jpg)

然后你在地图上选的地区scatterplot都会根据选中的地区调整（筛选）

打开action看看：

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljqscnce2j31c00u0h8r.jpg)

map of Erope这个图是the source of action 作用于这两个图里面

如果想选地图中的多个地点，可以用工具选，套索工具之类的

![](https://tva1.sinaimg.cn/large/0081Kckwly1gljqyzm89aj31c00u0nhk.jpg)


### Highlight

跟filter的区别：

![](https://tva1.sinaimg.cn/large/0081Kckwly1glnxanhbnzj314a04i0u2.jpg)

要先去scatterplot的worksheet里改变它的granularity才可以显现出来，因为highlight是在这个总结的图上显示。

这个例子中map是精确到state的 因此对应的scatterplot粒度也要精确到state，把state拽到detail里去，之后：

![](https://tva1.sinaimg.cn/large/0081Kckwly1glnx4wjrb1j31c00u0hcn.jpg)

## Example 2

拼接做完后，dropdown里选use as filter

![](https://tva1.sinaimg.cn/large/0081Kckwly1glo4e0pniwj31c00u01at.jpg)

做完后的interactivity，多个filter一起观察可获得很多信息：

![](https://tva1.sinaimg.cn/large/0081Kckwly1glo4ouc2ocj31c00u0dwl.jpg)

另：如果不想要鼠标悬停后显示出的小框框就 worksheet -> tooltip 勾掉show tooltip就可以

# Create a Storyline

一个story point只能拖一张图 or dashboard，但是可以添加多个point，然后陈述insights, 还可以添加annotate。

![](https://tva1.sinaimg.cn/large/0081Kckwly1glohbwqht0j31c00u0ase.jpg)



