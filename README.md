# Update
使用时遇到了ET格式文件爬取问题，此格式中难以正确使用换行符。
更新了parserET函数和ET函数，支持了ET格式解析，且对doc&txt格式做了优化，可以获得更整齐的格式

![优化前](https://s1.ax1x.com/2020/07/04/NxgZ5j.png)
![优化后](https://s1.ax1x.com/2020/07/04/NxgmPs.png)
# 百度文库爬虫
对于百度文库给出的可见型文档，百度进行了保护，难以正确复制，故使用此爬虫进行爬取。(对[jk50505k](https://github.com/jk50505k/wenku_spider)的爬虫进行了修改和优化)。