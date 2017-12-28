##17-18赛季NBA常规赛结果预测

###提示：不需要在本机额外安装python库，项目不兼容python3

####(1）安装virtualenv

    $ sudo apt-get install virtualenv

####(2）克隆项目

    $ git clone https://github.com/Li-Yingmin/nba_prediction.git

####(3)激活`python2.7`虚拟环境

    $ source 项目之前的目录/nba_prediction/nba_pre_demo/bin/activate

####(4)修改需要预测的比赛日程

修改以下目录的`17-18Schedule.csv`文件即可：

    目录/nba_prediction/nba_pre_demo/proj/data/17-18Schedule.csv

如不需要修改，可以保留原文件，原文件中存储的是12月份和1月份的比赛日程。

####(5)执行程序

使用python命令执行以下可执行文件：

    $ python 目录/nba_prediction/nba_pre_demo/proj/prediction.py

执行效果如下图：

![image.png-899.2kB][1]
![image.png-1225kB][2]

####(6)运行结果

执行结束之后会在`prediction.py`所在目录生成`17-18Result.csv`




[1]: http://static.zybuluo.com/CrazyHenry/xfractlhyr2i8ymcda854mtp/image.png
[2]: http://static.zybuluo.com/CrazyHenry/jyvmvwe8x5id6t4j4p7vvkee/image.png