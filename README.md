# AEDC : Age Estimation of Dental radiographs based on CNN

### 💻 Skills
<span>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=Tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Opencv-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/Sklearn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
</span>

### ⚒️ Tools
<span>
<img src="https://img.shields.io/badge/VScode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/>  
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>  
<img src="https://img.shields.io/badge/Anaconda-44A833?style=flat-square&logo=Anaconda&logoColor=white"/>
</span>

<br/>

## Dental Panoramic Image-based Age Estimation Network



![Untitled](./README/Untitled.png)

<br/>

## DATA


The panoramic dental images are segmented to separate individual teeth, each identified by their specific tooth number. Simultaneously, crowned teeth and treated teeth are also distinguished within the images.

![Untitled](./README/Untitled%201.png)

![Untitled](./README/Untitled%202.png)

After segmenting the dental images to isolate individual teeth objects, they are then saved in the following format:

![Untitled](./README/Untitled%203.png)

<br/>

## CNN regression model 


I created a regression model using CNN and sigmoid. 

In forensic odontology, when inferring age from panoramic dental images, an error margin of up to 10 years is considered significant. Therefore, using a regression model allows for a more meaningful interpretation within this allowable error range.

The structure of the CNN Regression model is as follows:



![Untitled](./README/Untitled%2012.png)


<br/>

## Result

![Untitled](./README/Untitled%2017.png)

![Untitled](./README/Untitled%2018.png)