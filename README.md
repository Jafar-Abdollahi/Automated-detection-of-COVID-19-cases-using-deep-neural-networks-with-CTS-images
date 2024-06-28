# Early-Detection-of-lung-cancer-using-machine-learning

The novel coronavirus 2019 (COVID-2019), which first appeared in Wuhan city of China in December 2019, spread rapidly around the world and became a pandemic. It has caused a devastating effect on both daily lives, public health, and the global economy. It is critical to detect the positive cases as early as possible so as to prevent the further spread of this epidemic and to quickly treat affected patients. The need for auxiliary diagnostic tools has increased as there are no accurate automated toolkits available. Recent findings obtained using radiology imaging techniques suggest that such images contain salient information about the COVID-19 virus. Application of advanced artificial intelligence (AI) techniques coupled with radiological imaging can be helpful for the accurate detection of this disease, and can also be assistive to overcome the problem of a lack of specialized physicians in remote villages. 

<h2> Pipline </h2>
<img src="https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images/blob/main/coronavirus-2.tmb-479v.jpg">
</br>

<h2> Skewed Data </h2>
Incremental training was used in the Resnet model because the Data was skewed. The negatives was way more than the postives so for example I trained on 100 postives and a hundered negatives and then inrementally adding more and more negatives so that the model will not always predict a negative.

<h2> Using Data anotations </h2>
In this study, CT images obtained from two different sources were used for the diagnosis of COVID-19. A COVID-19 CT image database was developed by Jafar Abdollahi using images from various open access sources. This database is constantly updated with images shared by researchers from different regions. At present, there are 1000 CT images diagnosed with COVID-19 in the database. Fig. 2 shows a few COVID-19 cases obtained from the database and the findings of the experts. 


<h2> GUI </h2>
<img src="https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images/blob/main/download1.png">

In this study, we have proposed several deep learning based model to detect and classify COVID-19 cases from CT images. Our model is fully automated with an end-to-end structure without the need for manual feature extraction. Our developed system is able to perform binary and multi-class tasks with an accuracy of 98.08% and 87.02%, respectively. The performance of the developed model is assessed by expert radiologists and is ready to be tested with a larger database. This system can be used in remote places in countries affected by COVID-19 to overcome a shortage of radiologists. Also, such models can be used to diagnose other chest-related diseases including tuberculosis and pneumonia. A limitation of the study is the use of a limited number of COVID-19 CT images. We intend to make our model more robust and accurate by using more such images from our local hospitals.

<img src="https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images/blob/main/download.png"> 
<img src="https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images/blob/main/2020-08-04_0-41-31.jpg"> 
<img src="https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images/blob/main/2020-08-04_0-41-47.jpg"> 
<img src="https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images/blob/main/2020-08-04_0-42-17.jpg"> 
<img src="https://github.com/Jafar-Abdollahi/Automated-detection-of-COVID-19-cases-using-deep-neural-networks-with-CTS-images/blob/main/2020-08-04_0-41-22.jpg"> 
