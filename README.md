<h2> Hi there, I'm Lydia Schönpflug! <img align='right' src="https://user-images.githubusercontent.com/62755943/167626161-d15e046b-4cd9-4cfc-b8d5-3d225400697a.png" width="250"> </h2> 
<p>
Data Scientist @ <a href="https://dbe.unibas.ch/en/research/medical/computational-pathology/">CTP Lab Uni Basel/USB</a></br>
</p>
<!---<img align='right' src="https://user-images.githubusercontent.com/62755943/167622812-d977ea06-8e88-40c8-8dc2-0352de13893d.png" width="250"> --->

[![Linkedin: Lydia Schönpflug](https://img.shields.io/badge/-LinkedIn-blue?style=plastic&logo=linkedin)](https://www.linkedin.com/in/lydia-schoenpflug)
[![Xing: Lydia Schönpflug](https://img.shields.io/badge/-Xing-3b8071?style=plastic&logo=xing)](https://www.xing.com/profile/Lydia_Schoenpflug)


### About me...  
I enjoy solving data-related problems especially with Deep Learning methods and have a passion for its biomedical application, with a focus in Computational Pathology.

Beyond just coding I like to dig deeper into the mathematical aspects of Deep Learning, which is supported and motivated by lectures during my masters degree, such as Advanced Mathematics for Stastical and Signal Processing, Detection and Pattern Recognition, Stastical and Adaptive Signal Processing, Deep Learning and Computer Vision. Due to the mostly interdisciplinary nature of Deep Learning applications I believe it is crucial to familiarize with the data and fully understand the desired objective, before implementing a solution.

Key skills: Designing Deep Learning models in <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"> with <img align='center' src="https://img.shields.io/badge/PyTorch-000000?style=flat&logo=pytorch">, <img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv"> and <img align='center' src="https://img.shields.io/badge/Tensorflow-000000?style=flat&logo=tensorflow">.
### Projects
* **SoftCTM: Cell detection in H&E images by soft instance segmentation and consideration of cell-tissue interaction** [Link to paper](https://arxiv.org/abs/2312.12151)
  
  <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"><img align='center' src="https://img.shields.io/badge/PyTorch-000000?style=flat&logo=pytorch"><img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv">
  <img src="https://github.com/lely475/lely475/assets/62755943/74c0b66e-caaf-496c-9ed3-a626aed1da3f" width="800">
  
  **Motivation** Detecting and classifying cells in histopathology H\&E stained whole-slide images is a core task in computational pathology, as it provides valuable insight into the tumor microenvironment.
  
   **Methods** In this work we investigate the impact of ground truth formats on the models performance. Additionally, cell-tissue interactions are considered by providing tissue segmentation predictions as input to the cell detection model.
  
  **Results&Conclusion** We find that a "soft", probability-map instance segmentation ground truth leads to best model performance. Combined with cell-tissue interaction and test-time augmentation our Soft Cell-Tissue-Model (SoftCTM) achieves 0.7172 mean F1-Score on the Overlapped Cell On Tissue (OCELOT) test set, achieving the third best overall score in the [OCELOT 2023 Challenge](https://ocelot2023.grand-challenge.org/).

* **Multi-task learning for tissue segmentation and tumor detection in colorectal cancer histology slides**  [Link to paper](https://arxiv.org/abs/2304.03101)
  
  <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"><img align='center' src="https://img.shields.io/badge/PyTorch-000000?style=flat&logo=pytorch"><img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv">
  <img src="https://github.com/lely475/lely475/assets/62755943/6575c413-42c7-46f5-bd76-fa6e44991cb8" width="900">
    
  **Motivation** Automating tissue segmentation and tumor detection in histopathology images of colorectal cancer (CRC) is an enabler for faster diagnostic pathology workflows. At the same time it is a challenging task due to low availability of public annotated datasets and high variability of image appearance. The semi-supervised learning for CRC detection [SemiCOL](https://www.semicol.org/) challenge 2023 provides partially annotated data to encourage the development of automated solutions for tissue segmentation and tumor detection.
  
   **Methods** We propose a U-Net based multi-task model combined with channel-wise and image-statistics-based color augmentations, as well as test-time augmentation, as a candidate solution to the SemiCOL challenge.
  
  **Results&Conclusion** Our approach achieved a multi-task Dice score of .8655 (Arm 1) and .8515 (Arm 2) for tissue segmentation and AUROC of .9725 (Arm 1) and 0.9750 (Arm 2) for tumor detection on the challenge validation set.
  
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
  
* **Deep Learning Lab 2021**: Diabetic Retinopathy Detection and Human Activity Recognition [private] <!-- [check it out](https://github.com/lely475/Deep-Learning-Lab-2021) -->
  
  <img align='center' src="https://img.shields.io/badge/Python-000000?style=flat&logo=python"><img align='center' src="https://img.shields.io/badge/Tensorflow-000000?style=flat&logo=tensorflow"><img align='center' src="https://img.shields.io/badge/OpenCV-000000?style=flat&logo=opencv">

  Two projects implemented during the Deep Learning Lab 2021 of the Institute of Signal Processing and System Theory ([ISS](https://www.iss.uni-stuttgart.de/en/)) 
  1. Deep-learning based classification of retina image into cases of referable and non-referable diabetic retinopathy. 
  2. Human activity recognition based on smartphone sensor data classified with a RNN

