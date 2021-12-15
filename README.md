# Alzheimer-Detection
### Abstract 
Alzheimer's is a progressive condition that starts 
with a mild loss of memory that can lead to a loss of the 
capacity to speak and respond to the environment. 60 to 80 
percent of dementia cases end in Alzheimer's Disease (AD). 
Among individuals that are older than 60 years, AD is 
most commonly seen. Around 200,000 Americans under 
the age of 60 (also known as early-onset Alzheimer's) have 
younger-onset Alzheimer's disease. More than 4 million 
individuals are projected to suffer from AD and other 
types of dementia in India, making the country the third 
largest case load in the world, after China and the US. AD 
cases are expected to cross about 7.5 million by 2030 in 
India. Early identification of AD will also assist in the 
prevention of this illness. So the aim is to provide an 
application based on the MRI image that forecasts the 
stage of AD. Many pre-trained CNN models can be used 
for this project. But these models are pre-trained for the 
images of specific dimensions, which will not help in 
providing more accurate results for the MRI images 
provided in the dataset. Also, existing training models 
could be an overhead due to more number of layers used 
in it. For each stage category, the suggested model is 
trained with 885 labelled images and we have derived a 
new convolutionary neural network (CNN) model based on 
this available dataset that predicts the stage of AD with 
greater accuracy using fewer layers compared to existing 
models. When the CNN model was finalized, we also 
discussed comparative research for various variants 
carried out.
### Introduction
Alzheimer Disease (AD) is a neuron degenerative disorder type of disease in which patient loses his/her thinking ability. Among individuals that are older than 60 years, AD is most commonly seen. In AD the count of the neurons in the brain is comparatively less than the healthy human brain. More than 4 million individuals are projected to suffer from AD and other types of dementia in India, making the country the third largest case load in the world, after China and the US. The cases of AD are forecasted to reach around 7.5 million in India by 2030. Early identification of AD will also assist in the prevention of this illness.
There are different stages of Alzheimer Disease that we have focused in this work. Those are as follows:
<p align="justified">
   <img src="https://user-images.githubusercontent.com/35445472/146240004-1cead2ff-b007-472a-8766-c71e6c6e877a.png" width="10%"></img> 
   <img src="https://user-images.githubusercontent.com/35445472/146240204-49197597-775a-4aa4-9e57-6debdd742c94.png" width="10%"></img>
   <img src="https://user-images.githubusercontent.com/35445472/146240281-a714b18c-ed9c-4850-81e7-eccf4e58ce88.png" width="10%"></img>
</p>





   	    (a) Mild Demented                               (b) Non Demented                               (c) Very Mild Demented
The target is to provide an application that correctly identifies the stage of AD based upon the MRI image.



  
