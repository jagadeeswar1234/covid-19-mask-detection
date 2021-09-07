COVID-19 pandemic has rapidly affected our day-to-day life disrupting the world trade and movements. Wearing a protective face mask has become a new normal. In the near future, many public service providers will ask the customers to wear masks correctly to avail of their services. Therefore, face mask detection has become a crucial task to help global society.


# covid-19-mask-detection
In order to train a custom face mask detector, we need to break our project into two distinct phases, each with its own respective sub-steps (as shown by Figure 1 above):
1) Training: Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras/TensorFlow) on this dataset, and then serializing the face mask detector to disk
2) Deployment: Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as with_mask
or without_mask
Our COVID-19 face mask detection dataset
![image](https://user-images.githubusercontent.com/86997363/132296074-7c2b46b4-0b47-4f6a-8cb5-5b3962cf4600.png)
![image](https://user-images.githubusercontent.com/86997363/132296094-734b5dca-ce9a-430c-8aec-c2f637d4f2e2.png)

This dataset consists of 1,260 images belonging to two classes:

with_mask: 630 images

without_mask: 630 images
