# Brain-Tumor-Classification-Using-Convolutional-Neural-Networks
In this project we create a neural network model which can be used to predict the class of the Magnetic Resonance Image (​MRI) scan if there exists any of the following types of tumor
- Meningioma
- Glioma 
- Pituitary tumor. 

The dataset that we will be using for our project is a brain tumor dataset posted by Jun Cheng on figshare.com. The link for the dataset is [here](https://figshare.com/articles/brain_tumour_dataset/1512427). This data is organized in matlab data format (.mat file).

- *Data Structure*
1) cjdata.label: ​1​ ​for​ meningioma, ​2​ ​for​ glioma, ​3​ ​for​ pituitary tumor
2) cjdata.PID: patient ​ID
3) cjdata.image: image ​data

We have a total of 3064 image files. Toaccomplish the task, we go through the following steps: 
- Data Preprocessing
- Data Modeling
- Model Evaluation.

> For detailed information of each step, refer to the report in docs folder.

In this project, we have also implemented the approach of Transfer Learning where we used pre-trained ResNet 50 model for image classification.

The links for the dataset can be found in the report. The source code files are located in src folder.

> BT_DataWrangling.ipynb: Source code for Data Preprocessing 

> BT_DataModeling.ipynb: Source code for Data Modeling 



