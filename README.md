# COVID-19-classification

This project is aimed to use CNN to build a CNN model which can classify normal CT image and COVID ones. 

There are two datasets used in this time, and in the case 1, the model is trained by dataset1 and tested by dataset2, whereas in the case 2, the model is trained by dataset2 and tested by dataset1.

# The images used in this time

- Dateset 1

![Covid (7)](https://user-images.githubusercontent.com/81594307/119424029-3a115f00-bd37-11eb-9ef7-8b59e7d70eed.png)

![Non-Covid (10)](https://user-images.githubusercontent.com/81594307/119424109-662ce000-bd37-11eb-9cb2-2dd8b8376730.png)


- Dataset 2

![COVID-3](https://user-images.githubusercontent.com/81594307/119423929-09c9c080-bd37-11eb-8bce-7d1d51c5e8bc.png)

![Normal-83](https://user-images.githubusercontent.com/81594307/119424126-71800b80-bd37-11eb-8aa6-94f9763eb797.png)



# The results/observations in this project
- The training accuracy of the trained models is higher ( around 95% ).
- However, when deploying the model into other dataset, the effectioncy of the trained model is low , no matter in which cases. It shows that the models trained in this time are just ready for particular inputs. They are not able to predict the CT images came from different data source. 
- In the future, it can aim to trained the model with various datasets in order to increase the performance of the model. 
