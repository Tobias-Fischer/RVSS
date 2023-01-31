# Official Repository RVSS

![logo](Pics/RVSS-logo-col.med.jpg)

The material here provided was developed as part of the [Robotic Vision Summer School](https://www.rvss.org.au/).

---
# Workshops
Please see this [separate README](https://github.com/dimitymiller/RVSS_Need4Speed).

---
# Lectorials
You can run the notebooks via Colab: http://colab.research.google.com/github/Tobias-Fischer/RVSS.

Links to slide decks and information about the lectorials will appear below.


---
## Lectorial A: Robotic Vision
Presented by Peter Corke, Queensland University of Technology, and Donald G. Dansereau, University of Sydney

### A: Introduction to Robotic Vision
<details>
<summary>A general introduction and motivation about the importance/elegance/power of vision as a sensor, and why robots need it</summary>

<br>
Slides coming soon

</details>

### A1: Introduction To Image Processing (Peter Corke)
<details>
<summary>Pixels, images, image processing, feature extraction</summary>

#### Coding Session:
* [Image features](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/image_features.ipynb)
* [Finding blobs](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/finding-blobs.ipynb)

#### Supporting Resources:
The following chapters from the [Robotics, Vision and Control](https://link.springer.com/book/10.1007%2F978-3-319-54413-7) Textbook support this session:
* Chapters 12.1, 12.2, 12.3, 12.4 and 12.5
* Chapter 13.1
  * Those who are a bit rusty on homogenous transformation matrices, rotation matrices and similar concepts may find Chapters 2.1 and 2.2 - 2D and 3D Geometry useful.

The following masterclasses from the [QUT Robot Academy](https://robotacademy.net.au/) may also be used to help develop your knowledge:
* [Introduction to Robotic Vision](https://robotacademy.net.au/masterclass/robotic-vision/)
* [2D Geometry](https://robotacademy.net.au/masterclass/2d-geometry/) and [3D Geometry](https://robotacademy.net.au/masterclass/3d-geometry/)
* [Getting Images into a Computer](https://robotacademy.net.au/masterclass/getting-images-into-a-computer/)
* [Image Processing](https://robotacademy.net.au/masterclass/image-processing/)
* [Spatial Operators](https://robotacademy.net.au/masterclass/spatial-operators/)
* [Feature Extraction](https://robotacademy.net.au/masterclass/feature-extraction/)

</details>

### A2: Introduction to Visual Geometry (Donald Dansereau & Peter Corke)
<details>
<summary>From light to digital images, the front end of the robotic vision process</summary>

#### Coding Session:
* [Camera projection basics](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/camera_animation.ipynb)
* [Camera modeling](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/camera.ipynb)
* [Camera calibration](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/calibration.ipynb)
* [Fiducial makers (AprilTags and ArUco markers)](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/fiducuals.ipynb)

#### Supporting Resources:
The following chapters from the [Robotics, Vision and Control](https://link.springer.com/book/10.1007%2F978-3-319-54413-7) Textbook support this session:
* Chapters 11.1 and 11.2

The following masterclasses from the [QUT Robot Academy](https://robotacademy.net.au/) may also be used to help develop your knowledge:
* [How Are Images Formed](https://robotacademy.net.au/masterclass/how-images-are-formed/)
* [The Geometry of Image Formation](https://robotacademy.net.au/masterclass/the-geometry-of-image-formation/) 
  * You may find watching [3D Geometry](https://robotacademy.net.au/masterclass/3d-geometry/) prior to these two will be beneficial 

 </details>
 
 ### A3: Vision-based Control (Peter Corke)
<details>
<summary>Closing the loop from sensing to action</summary>

#### Coding Session:
* [Image motion](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/ImageMotion.ipynb)
* [Image-based visual servoing (IBVS)](https://githubtocolab.com/Tobias-Fischer/RVSS/blob/main/Robotic_Vision/IBVS.ipynb)

#### Supporting Resources:
The following chapters from the [Robotics, Vision and Control](https://link.springer.com/book/10.1007%2F978-3-319-54413-7) Textbook support this session:
* Chapters 15.2

The following masterclasses from the [QUT Robot Academy](https://robotacademy.net.au/) may also be used to help develop your knowledge:
* [Vision and Motion](https://robotacademy.net.au/masterclass/vision-and-motion/)

</details>
 
---
## Lectorial B: Spatial Awareness
Presented by Tom Drummond, University of Melbourne
 
### B1, B2: Coordinates and Transformations
<details>
<summary>Describing poses and uncertainty</summary>

<br>
Slides coming soon

#### Coding Sessions:
* [Basic Geometry](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Spatial_Awareness/Tutorial_B1_Basic_Geometry/Basic%20Geometry.ipynb)

</details>
 
### B3, B4: How do I model the world?
<details>
<summary>Keeping track of stuff with imperfect measurement: Kalman filters</summary>

<br>
Slides coming soon

#### Coding Sessions:
* [Motion Model](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Spatial_Awareness/Tutorial_B2_Robot_Localisation/1_MotionModel.ipynb)
* [Uncertainty](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Spatial_Awareness/Tutorial_B2_Robot_Localisation/2_Uncertainty.ipynb)
* [Kalman Filter 1D](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Spatial_Awareness/Tutorial_B2_Robot_Localisation/3_KalmanFilter1D.ipynb)
* [Multivariate Gaussian](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Spatial_Awareness/Tutorial_B2_Robot_Localisation/4_MultiVariateGaussian.ipynb)
* [EKF](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Spatial_Awareness/Tutorial_B2_Robot_Localisation/5_EKF.ipynb)
* [SLAM](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Spatial_Awareness/Tutorial_B2_Robot_Localisation/6_SLAM.ipynb)

</details>

---
## Lectorial C: Visual Learning
Presented by Simon Lucey, University of Adelaide

### C1: Introduction to Visual Learning
<details>
<summary>Artificial neural networks</summary>

<br>
Slides coming soon

#### Coding Session:
* [Image classification with multi-layer perceptron](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Visual_Learning/Session1/Classification_MLP_2021.ipynb#scrollTo=lvPV3WzCC6WL)

</details>

### C2: Deep Visual Learning
<details>
<summary>Deep networks and convolutional neural networks</summary>

<br>
Slides coming soon

#### Coding Session:
* [Image classification with Convolutional NN](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Visual_Learning/Session2/LeNetClassificationExcercise_2021.ipynb)

</details>

### C3: Visual Optimisation
<details>
<summary>The theory and practice of visual optimisation</summary>

<br>
Slides coming soon

</details>

### C4: Backbone Networks
<details>
<summary>Standing on the backbones of giants</summary>

<br>
Slides coming soon

</details>


---
## Lectorial D: Reinforcement Learning
Presented by Pamela Carreno-Medrano, Monash University

### D1: Introduction to Reinforcement Learning
<details>
<summary>Introducing the fundamental concepts and algorithms of RL</summary>

<br>
During this session we will start our discussion on reinforcement learning.  We will discuss the main components of the reinforcement learning framework, introduce the fundamental concepts and algorithms and test them in a simple 2D discretised environment.

#### Coding Sessions:
* [Introduction to Reinforcement Learning](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Reinforcement_Learning/Session%201%20IntroRL.ipynb)

</details>

### D2: Introduction to Model-Free RL and Deep RL
<details>
<summary>Learning without prior state and reward models, from discrete to continuous spaces</summary>

<br>
In this session we will continue our discussion on reinforcement learning: enabling robots to learn how to operate in their environment through interaction.  We will discuss how we can approximate the optimal policy even when we don't know the state and reward models, and extend from discrete to continuous state-action spaces.

#### Coding Sessions:
* [Introduction to Model-Free Reinforcement Learning](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Reinforcement_Learning/Session%202.1%20ModelFreeRL.ipynb)
* [Deep RL - Replay Memory](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Reinforcement_Learning/Session%202.2%20-%20DeepRL_ReplayMemory.ipynb)
* [Deep RL - Target Network](https://colab.research.google.com/github/Tobias-Fischer/RVSS/blob/main/Reinforcement_Learning/Session%202.3%20-%20DeepRL_DQNTarget.ipynb)

</details>

### Additional Resources
<details>
<summary>If you'd like to know more</summary>

* David Silver's RL [Video Lectures](https://www.davidsilver.uk/teaching/) at UCL 
* Prof. Pascal Poupart's [Video Lectures](https://www.youtube.com/watch?v=KOF_BM-fNPE&t=4s&ab_channel=PascalPoupart) at University of Waterloo, Canada
* Sutton and Barton's [Introduction to Reinforcement Learning](https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf) book
* Sergey Levine's [Video Lectures](http://rail.eecs.berkeley.edu/deeprlcourse/) on deep reinforcement learning at UCBerkeley

</details>

---
## Deep Dive I 
Presented by Richard Hartley, Australian National University

---
## Deep Dive II
Presented by Hanna Kurniawati, Australian National University

---
## Deep Dive III
Presented by Miaomiao Liu, Australian National University
