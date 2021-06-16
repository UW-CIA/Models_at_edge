___
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FUW-CIA&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=users&edge_flat=false)](https://hits.seeyoufarm.com)
[![License](https://img.shields.io/pypi/l/mia.svg)]() 
<a href="https://https://github.com/UW-CIA/Models_at_edge/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/UW-CIA/Models_at_edge"></a>
<a href="https://github.com/kaiiyer/UW-CIA/Models_at_edge"><img alt="GitHub forks" src="https://img.shields.io/github/forks/UW-CIA/Models_at_edge"></a>
<a href="https://github.com/UW-CIA/Models_at_edge/graphs/contributors" alt="Contributors">
<img src="https://img.shields.io/github/contributors/UW-CIA/Models_at_edge" /></a>
<a href="https://github.com/UW-CIA/Models_at_edge/graphs/stars" alt="Stars">
<img src="https://img.shields.io/github/stars/UW-CIA/Models_at_edge" /></a>
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=shields)](http://makeapullrequest.com)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


# Models_at_edge
*Running the generative model (VAE) anomaly detector at the edge - IOS/Android/IoT* 

<br> <br> 
Part of the following effort: 
**HARNESSING THE POWER OF GENERATIVE MODELS FOR MOBILE CONTINUOUS AND IMPLICIT AUTHENTICATION**

Interconnecting the following works: 
* Generative AI Models
* Continous Authentication 
* Implicit Authentication 
* Outlier Detection 

### Abstract 
Authenticating a user’s identity lies at the heart of securing any information system.
A trade off exists currently between user experience and the level of security the system
abides by. Using Continuous and Implicit Authentication a user’s identity can be verified
without any active participation, hence increasing the level of security, given the continuous
verification aspect, as well as the user experience, given its implicit nature.
This thesis studies using mobile devices inertial sensors data to identify unique movements and patterns that identify the owner of the device at all times. We implement,
and evaluate approaches proposed in related works as well as novel approaches based on a
variety of machine learning models, specifically a new kind of Auto Encoder (AE) named
Variational Auto Encoder (VAE), relating to the generative models family. We evaluate
numerous machine learning models for the anomaly detection or outlier detection case of
spotting a malicious user, or an unauthorised entity currently using the smartphone system. We evaluate the results under conditions similar to other works as well as under
conditions typically observed in real-world applications. We find that the shallow VAE
is the best performer semi-supervised anomaly detector in our evaluations and hence the
most suitable for the design proposed.
The thesis concludes with recommendations for the enhancement of the system and
the research body dedicated to the domain of Continuous and Implicit Authentication for
mobile security.
Keywords: Machine Learning, Generative Models, Continuous Authentication, Implicit
Authentication, Artificial Intelligence



## Description 

Two different implementations are successfully converted to tflite models that are easily ran at edge thanks to the tflite framework. 

REF: https://www.tensorflow.org/lite

## Instructions 
* Train models using the jupyter notebooks 
* Generate ".tflite" files using the jupyter notebooks 
* For Android: Make sure you have Android Studio (>=3.2). You need an Android device and Android development environment with minimum API 21. Template app can be found here https://github.com/tensorflow/examples/tree/master/lite/examples/sound_classification/android/
* For IOS: You must have Xcode installed and a valid Apple Developer ID. You don't need to build the entire TensorFlow library to run the demo, it uses CocoaPods to download the TensorFlow Lite library. You'll also need the Xcode command-line tools: xcode-select --install If this is a new install, you will need to run the Xcode application once to agree to the license before continuing. Template app can be found here https://github.com/tensorflow/examples/tree/master/lite/examples/sound_classification/ios 
