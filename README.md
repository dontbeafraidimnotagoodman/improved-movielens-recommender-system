# improved-movielens-recommender-system
Reference
#https://blog.csdn.net/qq_32453673/article/details/72593675
#https://grouplens.org/datasets/movielens/  
#https://github.com/elliotzhao/Recommend-movies

This project is a recommender and ranking system based , the data comes from Movielens, data contains around 9000 movies with user rating, this project uses resnet50 to find the similarity of posters then do a item-based collaborative filtering based on the feature extracted by resnet50. The result will follow the first reference and the second to be shown as posters. However, only posters are not enough to show the accuracy, so at the end , I did a prediction of the rating of 1 user,and calculate RMSE(root mean square). 
# 
need python3.6 tensorflow 1.8(with keras or you can just pip keras) need to add a directory named posters under the folder which your program is running
# 
tested on Windows 10 jupyter notebook, also google cloud (debian with built in tensorflow)

