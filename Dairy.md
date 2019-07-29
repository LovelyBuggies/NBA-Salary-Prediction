# 日记簿

**Begin in 2019/07/19.**

---

## 7.19

前几天参加了微软的实习，去Gallery和公众号“云就该这么玩儿”上逛了逛，发现大部分同质的实习都是用Azure云服务做各种Experiments。看了一下自己研究的领域Blockchain+IoT，感觉配置很难，环境难以搭建（而且花费大量时间搭建环境很耗时伤财）。...  总之，就是敲定了仿照[NBA Salary Prediction using Multiple Regression](https://www.kaggle.com/koki25ando/nba-salary-prediction-using-multiple-regression)的思路，用Azure做个**NBA球员薪资预测**。

昨儿看了一下[Studio ML的Tutorial](https://docs.microsoft.com/en-us/azure/machine-learning/studio/create-experiment)，会用那个没有代码的工具（图形化工具）进行ML工程了，会的内容很基础，但是为了加快项目进度，还是先上手了——一边做实验一边看吧（*[那个详细介绍](https://docs.microsoft.com/en-us/azure/machine-learning/studio/tutorial-part1-credit-risk)*）。创建Workspace要注册账号，准备在Free Workspace上先创建一个实验跑着看看。不能太Ambitious！

`player_data.csv`和`players.csv`都是描述球员基本信息的（什么大学啊、年龄啊、blablabla...）没啥用处。

---

## 7.20

Azure 好慢啊！

那些modules的API呢？

R好难啊！

先用python notebook写出来然后放到Azure上吧！

~~当然要是能找到modules的API就继续做咯...~~

---

## 7.22

立了个flag，说7.27之前给wild老师写个report。😊终于找了个[好repo](https://github.com/ak4248)。这几天对着看代码然后写report算了。最后一天拿到Azure上跑一下。。。[坏笑...]

---

## 7.23

终于脱离了那个慢到令人发指的Azure AI Studio 的束缚。

用Microsoft Azure Notebook 不仅加速了还可以改python版本（*因为f\"的语法仅在3.5之后支持，所以一定要change到3.6的kernel*）。Studio不能改版本，所以很多语法等等很难支持。Notebook简直跟服务器一样好用。

Merge 不太好但先这样，最后再改，然后特例找几个好写文档。

竟然写完了model之前的内容😊

![相关性分析](https://i.loli.net/2019/07/24/5d382597e178695201.png)

---

## 7.24

遇到了一个神奇的问题！我竟然神奇滴解决了！

打开notebook反应不出来啊！反应不出来！显示`Error loading notebook`，弄了一下午终于找到原因了（*确切地说是找到解决办法了*），login/logout就可以解决——https://github.com/Microsoft/AzureNotebooks/issues/508。真是nice极了！

提了一个issue。

![](https://i.loli.net/2019/07/24/5d381e58a27c352260.png)

完成了LR和Lasso，好像LR需要正则化一下？

![](https://i.loli.net/2019/07/24/5d38262d504b540641.png)

![](https://i.loli.net/2019/07/24/5d382db46b8dc68916.png)

---

## 7.24 干（gan）完了！

另外，Azure不适合导出文件，markdown还是下载下来ipynb之后再导出吧。

*最后一个图的纵坐标写错了，改一下*

---

## 7.25

已经把ipynb弄到本地了，以后就在本地上玩了，最后给传到Azure上交差。

完善了一些细节。

---

## 7.29 

开始写中文版。

---

