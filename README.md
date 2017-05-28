Recruit
=======

### 一. 功能（目前是开发阶段，以下功能仅实现部分）
1. 根据提示输入关键字搜索相关职位信息，并将信息部分呈现出来。
2. 程序根据搜索得到的信息绘制成图像，供用户观看或使用。
3. 提供每个职位招聘信息的URL，用户可点击URL进入网页，查看招聘的详细信息。
4. 程序根据得到的数据自动的进行一定的分析，并展现给用户（难度较大，目前不知道如何做）

> __Ps__: 程序应该是一个图形用户界面，使用pyQt5

### 二. 使用的技术（或框架）

#### 语言：
- python

#### 类库:
- requests (用于爬虫)
- BeautifulSoup (用于提取数据)
- threading (用于支持多线程爬虫)
- matplotlib （用于绘制并生成图像）
- pandas (用于数据处理，使matplotlib方便绘图)

#### 框架：
- pyQt5 (著名的C++框架Qt 的python版本吧,用于GUI部分)

### 三：操作演示

![](/resource/Example/example_1.png)
> 上图是初始界面，在位置输入框输入要搜索的位置，如果不输入，则默认是北京，关键值就是需要搜索的职位关键字，比如C++，爬取界面数目大小可以自定义，最大100，最小1。左下方的两张分析图用于分析刚刚搜索到的数据，右侧是职位名称，双击可打开链接，通过浏览器进入详细介绍的界面

![](/resource/Example/example_2.png)
> 从图中可以看到一个进度条，显示爬取的进度，用户切勿点击多次

![](/resource/Example/example_3.png)
> 这就是双击职位名称后跳转到的界面，现版本使用的是智联招聘，下个版本考虑增加多个网站，但是分开搜索，因为存在相同职位在不同网站发布招聘信息的情况



### 四：未来展望

这是第一个版本，目前功能较少，界面比较难看（哎。。。UI麻烦啊）,但是核心部分已经基本完成（爬虫，基本界面，生成数据分析图），且项目结构应该问题不大,未来应该只需要往上增加功能就行了。

-> 连续写了4天，快40个小时，肝不行了，先暂停吧，以后再写。

