
脚本主要用来解析QQ的好友、群聊天消息，使用jieba分词，统计大家常说的关键字。一年前写的，
一直没有更新，这次更新移除了用ruby写的数据解析入库脚本，全部改用python。支持python3.x。

##### 安装

1. 安装jieba分词
2. `git clone https://github.com/jiyaping/qq-msg-analysis.git`

##### 使用
1. 使用QQ客户端的消息导出功能，格式选择txt格式.
2. `python todb.py my-msg.txt` 解析文本数据 
3. `python analysis.py` 分析文本数据
4. `python report.py` 生成报表
5. 打开result文件夹下面的report.htm即可查看结果


##### 截图示例

![pic1](https://raw.githubusercontent.com/jiyaping/qq-msg-analysis/master/pic1.png)
![pic2](https://raw.githubusercontent.com/jiyaping/qq-msg-analysis/master/pic2.png)
