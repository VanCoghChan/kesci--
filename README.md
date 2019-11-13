### kesci文本情感分类baseline
使用tfidf进行特征提取，多项式贝叶斯分类，没有调参，线下AUC86左右，线上AUC85左右
调参后效果更好，可以试着使用LR等其他模型
运行：
  数据带clean的都可以直接用，直接运行tfidf_MNB即可
  代码简单没有分析和注释，单纯为了水过预选赛
注：其中比赛的测试集文件一直在变动，使用时要重新替换测试集，链接：https://www.kesci.com/home/competition/5cb80fd312c371002b12355f/content/1
