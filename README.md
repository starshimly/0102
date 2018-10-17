# 作业仓库：0102

1.homework01。提交日期：2018-09-16，实现作业一要求的功能，共提交了两次。

第一次提交：使用宏实现，取出32位无符号整型数的最高8位（HHI）,次高8位（LHI），次低8位（HLO）和最低8位（LLO）,将结果存入QList<qint8>对象values中；

使用宏（MAX MIN）实现，返回最高8位和次高8位的最大值，次低8位和最低8位的最小值；

重新定义一个新的32位无符号整型数，其从高到低分别为原次低8位，最高8位，最低8位和次高8位，使用10进制和16进制分别输出该数字；

使用std::sort函数，将values中数字按从大到小排列，然后输出。

第二次提交：补充运行状态图，修改文件夹名字，修改作者名。

2.lab01.提交日期：2018-10-13，实现实验一要求功能，共提交了两次。

第一次提交：定义students类型结构体，将学生数据存入QList<students>对象student中，输出排序前结果；

使用std::sort函数，将student中姓名，课程1，课程2分别按照从大到小顺序排列，然后进行输出。

第二次提交：补充运行状态图。

3.homework02.提交日期：2018-10-17，实现作业二要求功能，共提交了一次。

第一次提交：定义studData类型结构，将学生数据存入QStringList对象student；

学生数据由ScoreSorter::readFile函数，从data.txt文件中读取；

重载运算符，使其可以直接输出stuData结构；

使用ScoreSorter::doSort函数对每一列进行排序，并输出屏幕；

对于数据导出成文件存在问题。
