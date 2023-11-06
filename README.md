# Introduction to the Practical Assignments
<p align = "justify">This repository contains the assignments and code for the Practical Assignment of the Course SOW-MKI85 Machine Hearing 2023-2024. 

<p align = "justify">This practical aims to provide you with a hands on experience with deep learning approaches for machine hearing. You will learn to pre-process audio, to extract relevant audio features, to train a ResNet-18 model on an environmental sound classification task and to evaluate the performance of the trained model.

<p align = "justify">The practical consists of six sessions. Session 1 and Session 2 introduce the assignment, the dataset, relevant concepts, frameworks, libraries, and audio feature extraction. Session 3 to Session 6 cover data preprocessing, training the ResNet-18 model on different sets of features, and evaluating and visualizing model performance.

## Intended learning outcomes
After successful completion of the practical assignments, you can...
<br>
•	Describe, extract and analyse relevant audio features for sound classification.
<br>
•	Implement a ResNet-18 model using either a single audio feature or combinations of three features. 
<br>
•	Evaluate and compare model performance for a sound classification task using relevant performance metrics.
<br>
•	Visualize data and results in a meaningful, informative way. 

# Materials
## Dataset
<p align = "justify">The dataset that we are using in this practical is the Environmental Sound Classification 50 (ESC-50) dataset[1]. This dataset consists of sound clips of 5 second duration in five categories: “Natural soundscapes & Water sounds”, “Human, non-speech sounds”, “Interior/Domestic sounds”, “Exterior/Urban noises”. More information about the dataset can be found [here](https://github.com/karolpiczak/ESC-50).  

<p align = "justify">The link to the ESC-50 database and metafile is on Brightspace in 'Content' --> 'Practical' --> 'Dataset'.  

## The Resnet-18 model
<p align = "justify">For this assignment, we make use of the ResNet-18 model [2]. ResNet models use skip connections to learn residual functions with respect to the input, rather than learning unreferenced functions as is the case in most neural networks. These skip connections mitigate the vanishing/exploding gradient problem that deep neural networks encounter, resulting in faster convergence and better performance. 

<p align = "justify">Here, we make use of the ResNet model with 18 layers. Although this relatively small ResNet performs on par with other state-of-the-art architectures, it has relatively low complexity and converges faster [2].

## Libraries, frameworks, platforms
* **Pytorch:** The assignments use the open-source library [Pytorch](https://pytorch.org/) to implement the ResNet-18 model. 
*	**Torchaudio:** The assignments use [Torchaudio](https://pytorch.org/audio/stable/index.html) to compute and extract relevant audio features. Torchaudio is a library for audio and signal processing with Pytorch.  A good alternative to Torchaudio is [Librosa](https://librosa.org/doc/latest/index.html). 
*	**WandB (Weights and Biases):** The assignments use the [Weights & Biases ML Ops platform](https://wandb.ai/site) to visualize and track training progress.  
*	**Colab:** You can work on the assingments using [Google Colab](https://colab.google/). Colab is a hosted Jupyter Notebook service. Use Google Drive for data storage. If you do not yet have an account, please sign up and create an account. 

## The assignments
<p align = "justify">You can download assignments, clone the repository or open an assignment in Google Colab using the link at the top of the script. Assignments will be added at the latest on the evening before the practical session. In total, there will be six assignments.   

# Practical report
The Practical Assignments are completed with a Practical Report consisting of two parts:
<br>
* **Part 1:** Audio feature extraction; [template practical report part 1](https://www.overleaf.com/read/htdgvkcwjcdn#eaa6eb). 
* **Part 2:** Sound classification using the Resnet-18 model; [template practical report part 2](https://www.overleaf.com/read/qdzdmzpnnqjb#45d1a7).


# References
[1] Piczak, K. J. (2015, October). ESC: Dataset for environmental sound classification. In Proceedings of the 23rd ACM international conference on Multimedia (pp. 1015-1018).
<br>
[2] He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep residual learning for image recognition. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 770-778).




