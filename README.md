<h2> Hi there, I'm Lydia Schönpflug! <img align='right' src="https://user-images.githubusercontent.com/62755943/167626161-d15e046b-4cd9-4cfc-b8d5-3d225400697a.png" width="250"> </h2> 
<p>Data Scientist </br>
M. Sc. Electrical Engineering @ <a href="https://www.uni-stuttgart.de/en/">University of Stuttgart</a></br>Backend Developer @ <a href="https://vica.one">vica.one</a>
</p>
<!---<img align='right' src="https://user-images.githubusercontent.com/62755943/167622812-d977ea06-8e88-40c8-8dc2-0352de13893d.png" width="250"> --->

[![Linkedin: Lydia Schönpflug](https://img.shields.io/badge/-LinkedIn-blue?style=plastic&logo=linkedin)](https://www.linkedin.com/in/lydia-schoenpflug)
[![Xing: Lydia Schönpflug](https://img.shields.io/badge/-Xing-3b8071?style=plastic&logo=xing)](https://www.xing.com/profile/Lydia_Schoenpflug)


### About me...  
I enjoy solving data-related problems especially with Machine Learning methods and have a passion for the (bio-)medical field.

Beyond just coding I like to dig deeper into the mathematical aspects of Machine Learning, which is supported and motivated by lectures during my masters degree, such as Advanced Mathematics for Stastical and Signal Processing, Detection and Pattern Recognition, Stastical and Adaptive Signal Processing, Deep Learning and Computer Vision.
Due to the mostly interdisciplinary nature of Machine Learning applications I believe it is crucial to familiarize with the data and fully understand the desired objective, before implementing a solution.

Key skills: Designing Deep Learning models in <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"> with <img align='center' src="https://img.shields.io/badge/Tensorflow-000000?style=flat&logo=tensorflow">, <img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv"> and <img align='center' src="https://img.shields.io/badge/PyTorch-000000?style=flat&logo=pytorch">, but I also have experience in Backend Development with <img align='center' src="https://img.shields.io/badge/Javascript-000000?style=flat&logo=javascript"> and Embedded System design with C and VHDL.

### Projects
* **Master Thesis:** ConvLSTM-based cell lineage analysis in optical microscopy sequences [private]

  <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"><img align='center' src="https://img.shields.io/badge/Tensorflow-000000?style=flat&logo=tensorflow"><img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv">
  | <img src="https://user-images.githubusercontent.com/62755943/167618346-8dc670e0-b50b-4567-954c-82afdb6b5e5e.png" width="500">| <img src="https://user-images.githubusercontent.com/62755943/167620269-1597cab2-3f71-4e1a-a71d-e61f6cb1b031.gif" width="250">|
  |:--:|:--:| 
  | Learning goal | Tracking prediction for HeLa cell|

  **Motivation** Cell lineage analysis, including cell tracking, mitosis, and apoptosis detection in microscopy sequences, is a common tool in biomedical research. Manual analysis is time consuming and limits the number of cells that are considered. This motivates the develop- ment of an automatic analysis tool.

  **Methods** This thesis investigates a ConvLSTM-based automated approach (Cell-STN) to cell lineage analysis, focusing on human cancer cell lines imaged with optical time-lapse microscopy. Cell-STN consists of a core network, which extracts spatio-temporal features of the target cell from the input sequence and initial target cell position. The features are then input to three task-specific networks, respectively predicting a 2D probability map for cell positional probability, probability of a mitosis and an apoptosis event.

  **Results** The method was evaluated on three in-house datasets and one private dataset from the University of Arizona. Two experiments were conducted. For the first experiment the configurations from the original paper were kept, while they were adapted to address shortcomings for the second experiment. The first experiment revealed limitations in the algorithm with regards to short-cut learning, sensitivity to microscopy type and image quality and low performance in an inference-near setting. Despite improvements in the second experiment all limitations are still present.

  **Conclusion** It needs to be considered, whether further method improvements can overcome the limitations, or an entirely different approach is required.

* **Research Thesis:** DL-based automated detection and tracking of human cells in microscopy image sequences [private]
  
  <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"><img align='center' src="https://img.shields.io/badge/PyTorch-000000?style=flat&logo=pytorch"><img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv">
  | <img src="https://user-images.githubusercontent.com/62755943/167648765-ec0f7ffd-9cd2-4913-aa57-a8287b4090d7.jpg" width="600">| <img src="https://user-images.githubusercontent.com/62755943/167648884-941b92f3-a9ac-4544-a93d-6222c8a541ff.gif" width="400">|
  |:--:|:--:| 
  | MPM-Net method | Prediction results for lung cancer cells|

  **Motivation** The study of biological processes requires detecting and tracking cells in time-lapse microscopy images. Manual analysis is time consuming and limits the number of cells that are considered. With support of algorithms the analysis could be reduced in time and increased in quantity, resulting in higher statistical significance. One automation approach are deep learning-based algorithms. They require labeled datasets, however, the number of public human cancer cell microscopy datasets is limited. Therefore the performance of state of the art deep learning approaches is mostly unknown. 
  
   **Methods** Out of three algorithms the Motion-and-Position-Map-Network (MPM-Net) was selected as the approach to cell detection and tracking. It was evaluated on the Cell Tracking Challenge DIC-C2DH-HeLa dataset, and the NCI-H460 in-house dataset.

  **Results** MPM-Net achieved a detection F1-score of 87.27% on the HeLa and 91.82% on the NCI-H460 dataset. Tracking performance was slightly lower with an association accuracy of 83.94% for the HeLa and 79.05% for the NCI-H460 dataset. Mitosis events were detected with an F1-score of 72.75% for the HeLa and 72.00% for the NCI-H460 dataset.
  
  **Conclusion** Overall results prove that the MPM-Net based algorithm is applicable to detecting and tracking human-cancer cell lines, but shows limitations with regard to overdetection and detecting mitosis events reliably. At the same time the model is generalizable to similar, unseen cell lines and learned to identify real biological structures, such as cell nuclei, as a critical feature for high cell probability. 
  
* **Deep Learning Lab 2021**: Diabetic Retinopathy Detection and Human Activity Recognition [public] [check it out](https://github.com/lely475/Deep-Learning-Lab-2021)
  
  <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"><img align='center' src="https://img.shields.io/badge/Tensorflow-000000?style=flat&logo=tensorflow"><img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv">

  Two projects implemented during the Deep Learning Lab 2021 of the Institute of Signal Processing and System Theory ([ISS](https://www.iss.uni-stuttgart.de/en/)) 
  1. Deep-learning based classification of retina image into cases of referable and non-referable diabetic retinopathy. 
  2. Human activity recognition based on smartphone sensor data classified with a RNN
* **REST API backend**: [private]
  
  <img align='center' src="https://img.shields.io/badge/Javascript-000000?style=flat&logo=javascript"><img align='center' src="https://img.shields.io/badge/Express.js-000000?style=flat&logo=express">

  Implementation of a REST API connecting a Postgresql database with a User Interface. Implemented using Javascript, Express.js and Node.js.
