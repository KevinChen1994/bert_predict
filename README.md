# BERT分类任务以及预测

将分类任务训练代码与预测代码进行分离。  
训练代码基本不动。    
目前预测代码有两种方式，一种是使用Estimator的方式，另一种是将图进行restore，使用feed_dic进行数据输入。  
先实现了使用feed_dic的方法。  
预测代码在run_predict.py中，只需要修改dataProcessor就OK。

