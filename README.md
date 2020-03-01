                                           # Image Classification

Main goal of code is to deliver best accuracy of image classification out of very small dataset.

Dataset: Product                  no. of images
       1: shaver                     16
       2: smart baby bottle          16
       3: toothbrush                 16
       4: wakeup Light               16

Challenge: Maximum accuracy out of small dataset without adding any extra images.

solution:
1) As small dataset and we are not planning to add extra image. we will be using same images for traning as well as  validation.
2) To get maximum out of our dataset we are using different transforms with training and validation set.
3) We will try to use as much as possible image transformation to train our model with every possible aspect.
4) using small batch size.
5) We will be using Transfer learning technique so it will be eaiser to achieve maximum accuracy.  
  
Result:
<img width="317" alt="Baby" src="https://user-images.githubusercontent.com/12019353/75631997-090bb280-5bf8-11ea-8dfd-9d782ab04535.PNG">
<img width="332" alt="baby2" src="https://user-images.githubusercontent.com/12019353/75631998-09a44900-5bf8-11ea-83a5-dc771561092c.PNG">
<img width="334" alt="shave" src="https://user-images.githubusercontent.com/12019353/75631999-0a3cdf80-5bf8-11ea-9472-32271350c002.PNG">
<img width="342" alt="tooth" src="https://user-images.githubusercontent.com/12019353/75632000-0a3cdf80-5bf8-11ea-8e4e-956a98833f71.PNG">
<img width="324" alt="wkl" src="https://user-images.githubusercontent.com/12019353/75632001-0a3cdf80-5bf8-11ea-878c-c361386017cb.PNG">
