# Video Analytics for Understanding Pedestrian Mobility Patterns in Public Spaces: The Case of Milan

<p align="center" float="left">
  <img src="https://github.com/lorenzlorg/MSc-Thesis/blob/main/images/tt.png" width="200" />
  <img src="https://github.com/lorenzlorg/MSc-Thesis/blob/main/images/Immagine1.png" width="110" /> 
  <img src="https://github.com/lorenzlorg/MSc-Thesis/blob/main/images/Immagine2.png" width="200" />
</p>


Nowadays, thanks to the recent developments of ICT tools for collecting traffic data in the urban environment, there is ever-growing availability of videos regarding the nerve centres of cities. This enables detailed analyses of public spaces and their users, for a better understanding of hidden mobility patterns. Having a clear view of pedestrian dynamics can be very helpful for various applications in modern days such as urban planning.

The main objective of this research project is to characterise public spaces through a mobility study on pedestrian patterns analysed by means of video analytics. The analysis focuses on the different types of pedestrian dynamics and on pedestrian route choices to obtain pedestrian utilisation profiles through observable behavioural parameters.

This work revolves around the case study of Piazza Duomo (Milan, Italy). A tracking-by-detection approach was chosen for the analyses; YOLOv7 was used to detect pedestrians after being trained on a custom dataset and, in order to handle pedestrian tracking, SORT algorithm was considered. 

The distribution of detections was analysed using QGIS software, whereas, point pattern analysis and trajectory data mining were performed using specific Python libraries. The trajectory data mining part was aimed at clustering the trajectories in order to identify pedestrian utilisation profiles (namely, commuters and tourists). Secondly, group analysis was carried out to identify groups of pedestrians that might be representative of specific mobility patterns in the public space considered.

The results of the study show that conducting analysis in crowded scenes can be challenging, both with a human eye and with video analytics techniques. Nonetheless, computer vision techniques can provide great advantages, especially in speeding up the overall process. Within the Urban Informatics discipline, the results of this research could support the definition of evidence-based/ parametric approach for regeneration projects of urban public spaces. Moreover, the proposed methodology could be of notable interest for the calibration/ validation of computer-based pedestrian modelling and simulation systems, and for further development of computer vision techniques.

<p align="center">
<img src="https://github.com/lorenzlorg/MSc-Thesis/blob/main/images/tracks_img_new.png"  width="600" height="340">
</p>

[Thesis](https://github.com/lorenzlorg/MSc-Thesis/blob/main/Lorgna__Lorenzo%20_Tesi_LMDS_24_03_2023.pdf)  
[Slides](https://github.com/lorenzlorg/MSc-Thesis/blob/main/Lorgna__Lorenzo%20_Presentazione_LMDS_24_03_2023.pdf)  
[Notebooks](https://github.com/lorenzlorg/MSc-Thesis/tree/main/notebooks)  

