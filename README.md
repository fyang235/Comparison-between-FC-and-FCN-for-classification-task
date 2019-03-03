# Comparison-between-FC-and-FCN-for-classification-task
This repository explores if FCN suitable for classification tasks.

### We built two models with the same number of parameters. One uses the conventional FC head and the other use a FCN head.  
The speeds of those two model are statistically the same:  

**For FC to converge:**  
![fc-speed](https://github.com/fyang235/Comparison-between-FC-and-FCN-for-classification-task/blob/master/results/fc-training.png)  

**For FCN to converge**
![fcn-speed](https://github.com/fyang235/Comparison-between-FC-and-FCN-for-classification-task/blob/master/results/fcn-training.png)  

### And their accuracies are comparatable.  
**The perfomance of FC classifier:**  
![fc-acc](https://github.com/fyang235/Comparison-between-FC-and-FCN-for-classification-task/blob/master/results/fc-image.png)  


**The performance of FCN classifier:**  
![fcn-acc](https://github.com/fyang235/Comparison-between-FC-and-FCN-for-classification-task/blob/master/results/fcn-image.png)   


So FCN classifiers are competent and why people keep using FC classifiers?
