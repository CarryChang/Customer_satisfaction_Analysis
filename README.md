#### Customer_satisfaction_Analysis
##### 本软件开发的目的是实时对重庆地区在线民宿的满意度进行评测，使用Python实现了在线评论采集和情感可视化分析。主要功能包括在线原始评论采集、主题分类、评论情感分析与结果可视化展示等四个模块。本软件的主要技术特征在于：使用Selenium模拟浏览器点击翻页操作，并配合Request实现了携程网爬虫封锁和自动化的采集民宿UGC内容的功能，提取民宿地址和在线评论等信息；搭建了百度地图POI查询入口，可以进行自动化的批量查询POI信息的功能；构建了基于在线民宿语料的Word2vec主题聚类模型，利用主题中心词能找出对应的主题属性字典；以用户打分作为标注，然后通过实验贝叶斯、SVM、决策树等多种分类模型，选用最优模型对提出的评价主体 进行情感分类，最后通过POI热力图的方式对在线民宿满意度进行展示。