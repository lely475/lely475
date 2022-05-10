<h2> Hi there, I'm Lydia Schönpflug! <img align='right' src="https://user-images.githubusercontent.com/62755943/167626161-d15e046b-4cd9-4cfc-b8d5-3d225400697a.png" width="250"> </h2> 
<p>Machine Learning Engineer </br>
M. Sc. Electrical Engineering @ <a href="https://www.uni-stuttgart.de/en/">University of Stuttgart</a></br>Backend Developer @ <a href="https://vica.one">vica.one</a>
</p>
<!---<img align='right' src="https://user-images.githubusercontent.com/62755943/167622812-d977ea06-8e88-40c8-8dc2-0352de13893d.png" width="250"> --->

[![Linkedin: Lydia Schönpflug](https://img.shields.io/badge/-Lydia%20Schönpflug-blue?style=plastic&logo=linkedin)](https://www.linkedin.com/in/lydia-schoenpflug)

### About me...  
I enjoy solving data-related problems especially with Machine Learning methods and have a passion for the (bio-)medical field.

Beyond just coding I like to dig deeper into the mathematical aspects of Machine Learning, which is supported and motivated by lectures during my masters degree, such as Advanced Mathematics for Stastical and Signal Processing, Detection and Pattern Recognition, Stastical and Adaptive Signal Processing, Deep Learning and Computer Vision.
Due to the mostly interdisciplinary nature of Machine Learning applications I believe it is crucial to familiarize with the data and fully understand the desired objective, before implementing a solution.

My key skills are designing Deep Learning models in Python with Tensorflow, OpenCV and PyTorch, but I also have experience in Backend Development with Javascript and Embedded System design with C and VHDL.

### Projects
* **Master Thesis:** ConvLSTM-based cell lineage analysis in optical microscopy sequences [private]
  | <img src="https://user-images.githubusercontent.com/62755943/167618346-8dc670e0-b50b-4567-954c-82afdb6b5e5e.png" width="500">| <img src="https://user-images.githubusercontent.com/62755943/167620269-1597cab2-3f71-4e1a-a71d-e61f6cb1b031.gif" width="250">|
  |:--:|:--:| 
  | Learning goal | Tracking prediction for HeLa cell|

  **Motivation** Cell lineage analysis, including cell tracking, mitosis, and apoptosis detection in microscopy sequences, is a common tool in biomedical research. Manual analysis is time consuming and limits the number of cells that are considered. This motivates the develop- ment of an automatic analysis tool.

  **Methods** This thesis investigates a ConvLSTM-based automated approach (Cell-STN) to cell lineage analysis, focusing on human cancer cell lines imaged with optical time-lapse microscopy. Cell-STN consists of a core network, which extracts spatio-temporal features of the target cell from the input sequence and initial target cell position. The features are then input to three task-specific networks, respectively predicting a 2D probability map for cell positional probability, probability of a mitosis and an apoptosis event.

  **Results** The method was evaluated on three in-house datasets and one private dataset from the University of Arizona. Two experiments were conducted. For the first experiment the configurations from the original paper were kept, while they were adapted to address shortcomings for the second experiment. The first experiment revealed limitations in the algorithm with regards to short-cut learning, sensitivity to microscopy type and image quality and low performance in an inference-near setting. Despite improvements in the second experiment all limitations are still present.

  **Conclusion** It needs to be considered, whether further method improvements can overcome the limitations, or an entirely different approach is required.

