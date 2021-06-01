# Abnormal-Traffic-Detection-Unsupervised
本代码提出一种EAD-PCA特征提取方法，基于此对AE，LSTM-AE，IF，LOF，DAGMM五个模型进行验证实验

# Dependencies：
* Python 3.6
* Tensorflow 2.1.0
* keras 2.3.1
* numpy 1.19.2
* matplotlib 3.1.1

# Folders:
* AE+LSTM：存放LSTM-AE模型
* Autoencoder：存放AE模型
* DAGMM：存放DAGMM模型
* IsolationForest：存放IF、LOF模型
* DataProcessing：数据预处理代码
* Picture：绘图代码
* allservice_allfeature_nonpac：五个模型在全服务全特征无pca数据处理下的代码
* allservice_allfeature_pca：五个模型在全服务全特征有pca数据处理下的代码
* allservice_delete_pca：五个模型在全服务删除部分特征有pca数据处理下的代码
* http_allfeature_pca：五个模型在http服务全特征有pca数据处理下的代码
* http_delete_pca：五个模型在http服务删除部分特征有pca数据处理下的代码
