# R语言练习题

1. R语言和RStduio是什么关系？
2. R语言和R包是什么关系？
3. CRAN和Bioconductor是什么关系？
4. 如果一个朋友给你发了一个R脚本，但是你用Rstudio打开发现是乱码，你应该如何处理？
5. 如何安装R包，ggplot2?如何安装R包clusterProfiler?
6. 如果一个R包放在GitHub上，应该如何安装？
7. 如何加载一个已经安装的R包？
8. 如果你已经安装了ggplot2, 但是在写代码的时候，发现ggplot函数运行的时候，输出Error in ggplot() : 没有"ggplot"这个函数
9. 如果一个R函数，你不懂，你应该如何查看这个函数的帮助文档？
10. 运行代码的时候，出现错误: 找不到对象'a'(object 'a' not found)  这个问题，原因是什么？
11. 在数据类型中，整型和浮点型有什么区别？R语言的数字默认是什么类型？
12. 请学习布尔运算的含义，R语言应该如何做布尔运算？101 > 102 | 101 < 102输出是什么？
13. 向量和矩阵有什么区别？
14. 矩阵和数据框有什么区别？
15. 数据框和列表有什么区别？
16. 如何创建一个内容为aabbccdd的字符串
17. 如何创建一个内容为"A1", "A2","A3", "A4"...."A100"的向量，命名为mystr
18. 在第5题第基础上，请提取出变量中的的数字部分。也就是1,2,3..100
19. 请查找相关资料，理解R语言中因子(factor)的含义？
20. 代码理解，变量的a的构建形式为a<- factor(c("22323","11231","3123")),  请写出代码，将a转换成数值型
21. R语言自带了一个数据集，iris, 请写出代码，查看它的前10行，后10行，查看1到3行，2到3列
22. 继续上一题，iris$Sepal.Length和iris['Sepal.Length']有什么区别, 思考一下原因？
23. 继续上一题, 请筛选出iris数据中Species为setosa第结果
24. 请使用write.table将iris这个数据集输出成csv格式，（请查阅csv格式的含义）
25. 请认真阅读read.table这个函数，理解sep, row.names, col.names, head,comment.char这些参数的含义
26. 请用read.table读取之前用write.table输出的数据
27. 请说出read.table和read.csv之间的区别
28. 请学习data.table的fread函数，并用它读取write.table输出的csv文件
