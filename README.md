# Covid Detection From Lung X-rays

I would want to mention that the analysis has been done on a limited dataset and the results are preliminary and nothing conclusive can be inferred from the same. Clinical trials/medical validations have not been done on the approach.

Dataset:
To target the issue at hand, we’ve collected own dataset,combining the Kaggle Chest X-ray dataset with the COVID19 Chest X-ray dataset collected by Dr. Joseph Paul Cohen of the University of Montreal. Both of these datasets consist of posterior anterior chest images of patients with pneumonia. As the COVID19 dataset is being updated daily as more cases are published, we accessed the instance available on the 18th of March, 2020. Our dataset is split into 4 different categories, with 9 images per class used as a test set.
•	Healthy: 79 images
•	Pneumonia (Viral) : 79 images
•	Pneumonia (Bacterial): 79 images
•	Pneumonia (COVID-19): 69 images

Results:
When considering three classes (Healthy, COVID-19, Bacterial), after training for 100 epochs at a learning rate of 5E-4.
In all three cases, the model has performed significantly well. Moreover, the purpose of building three different models was also to check the model consistency with respect to the detection of the COVID-19 cases. In all three cases, both the precision and recall have been significantly high for COVID-19 cases in test data.

Thus, there is a huge potential to this approach and can be an excellent method to have an efficient, fast, diagnosis system which is the need of the hour. 
