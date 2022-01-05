---
layout: splash
author_profile: false
permalink: /
toc: true
learning_from_demonstrations:
  - image_path: /assets/images/LFD.png
    alt: "Learning From Demonstrations img"
    title: "Learning Control From Expert Demonstrations"
    excerpt: '*(joint work with L. Fraile, L. Pannocchi, and P. Tabuada)*<br>
		We revisit the problem of learning a 
		stabilizing controller from a finite number of 
		demonstrations by an expert. The proposed algorithm
		requires only n+1 expert demonstrations, where n is the number of states of 
		the system being controlled. When we have more than n+1 
		demonstrations, at every time interval, we can choose the 
		best n+1 demonstrations to approximate the stabilizing controller
		in the best way. The 
		feasibility of the proposed algorithm is experimentally 
		demonstrated by applying it on a CrazyFlie 2.0 quadrotor.<br><br>
		**Keywords**: *learning from demonstrations, imitation learning, motion control* <br>
		**Technical skills**: *ROS, C++, Python, MATLAB, Simulink, Git* '
    url: "/assets/pdfs/UCLA-CyPhyLab-2021-03.pdf"
    btn_label: "PDF"
    btn_class: "btn--primary"
    url2: "https://youtu.be/sgVyrHctXBU"
    btn_label2: "Video"
    btn_class2: "btn--primary"
    url3: "https://github.com/sultangazin/cyphy_testbed/tree/LFD"
    btn_label3: "GitHub"
    btn_class3: "btn--primary"
privacy_in_control:
  - image_path: /assets/images/PrivacyInControl.jpg
    alt: "Privacy In Control img"
    title: "Privacy in Control Over the Cloud"
    excerpt: '*(joint work with P. Tabuada)*<br>
		Cloud computing platforms are being increasingly used 
		for closing feedback control loops, especially when 
		computationally expensive algorithms, such as 
		model-predictive control, are used to optimize
		performance. Outsourcing of control algorithms entails 
		an exchange of data between the control system and the 
		cloud, and, naturally, raises concerns about the privacy 
		of the control system’s data (e.g., state trajectory, 
		control objective). We propose several 
		transformation-based methods for enforcing data privacy. 
		We also quantify the amount of provided privacy and 
		discuss how much privacy is lost when the adversary has 
		access to side knowledge.<br><br>
		**Keywords**: *data privacy, optimization, predictive control*<br>
		**Technical skills**: *MATLAB, Simulink*'
    url: "https://arxiv.org/pdf/1906.07460.pdf"
    btn_label: "PDF"
    btn_class: "btn--primary"
    url2: "/assets/pdfs/CDC19_Presentation.pdf"
    btn_label2: "Slides"
    btn_class2: "btn--primary"
alphapilot:
  - image_path: /assets/images/alphapilot.jpeg
    alt: "AlphaPilot image"
    title: "AlphaPilot AI Drone Innovation Challenge"
    excerpt: '*(as a member of the team Formula Drone)*<br>
		Finished as the top qualifier among 424 teams, ahead of numerous
		teams and research groups. Worked on the design of the AI
		framework, written in C++ and powered by NVIDIA Jetson, that
		can pilot racing drones through aerial courses at high speed
		without GPS, data relay or human intervention. I designed 
		algorithms for optimal trajectory generation and obstacle avoidance.
		Was involved in development of the perception system, more specifically,
		during data collection and integration of the neural network with NVIDIA Jetson.<br>
		**Keywords**: *optimal trajectory generation, obstacle avoidance, control barrier functions, neural networks, object detection*<br>
		**Technical skills**: *ROS, C++, Python, MATLAB, ACADO, qpOASES, TensorFlow, NVIDIA TensorRT, Git*'
    url: "https://www.herox.com/alphapilot/82-teams"
    btn_label: "Website"
    btn_class: "btn--primary"
reinforcement:
  - image_path: /assets/images/RL_img.png
    alt: "RL Project img"
    title: "Learning to Control Mechanical Systems"
    excerpt: '*(joint work with M. Marchi, M. Lucas, and L. Fraile)*<br>
		We want to understand trade-offs inherent in applying learning-based control
		strategies to standard control problems, solvable with classical techniques.
		To this goal, we study the performance of [Model-Based Deep Reinforcement Learning 
		(MB-DRL)](https://arxiv.org/pdf/1708.02596.pdf) and [Generative Adversarial Imitation Learning (GAIL)](https://arxiv.org/pdf/1606.03476.pdf) in mechanical environments from OpenAI Gym. 
		For the limited number of environments we tested, we conclude that GAIL outperforms MB-DRL. 
		In the case of the model-based algorithm we believe that we can improve its performance 
		by changing the way the optimal action is chosen and by improving the policy with model-free 
		methods.<br>
		**Keywords**: *reinforcement learning, imitation learning, model predictive control*<br>
		**Technical skills**: *PyTorch, OpenAI Gym*'
    url: "/assets/pdfs/ECE239AS_Project_Final.pdf"
    btn_label: "PDF"
    btn_class: "btn--primary"
dmpc:
  - image_path: /assets/images/Quad_system.PNG
    alt: "DMPC project img"
    title: "Algorithms for Distributed Model Predictive Control"
    excerpt: '*(joint work with L. Fraile)*<br>
		In this project we consider two state-of-the-art algorithms for solving 
		distributed model predictive control (DMPC) problems. 
		[The first algorithm](https://www.sciencedirect.com/science/article/abs/pii/S0005109813000101?via%3Dihub) 
		utilizes dual decomposition and accelerated gradient methods 
		in a distributed fashion. [The second algorithm](https://ieeexplore.ieee.org/document/8264654) uses alternating direction method of 
		multipliers (ADMM) on the primal problem. We implement the three aforementioned algorithms
		and compare their results with those given by CVX. These algorithms were tested on the 
		[quadruple-tank process system](https://ieeexplore.ieee.org/document/845876). We evaluate the algorithms based on their convergence 
		to the solution.<br>
		**Keywords**: *optimization, model predictive control, gradient methods, ADMM*<br>
		**Technical skills**: *MATLAB, Simulink*'
    url: "/assets/pdfs/ECE236C_Project.pdf"
    btn_label: "PDF"
    btn_class: "btn--primary"
neural_net:
  - image_path: /assets/images/NN_confusion_matrix.png
    alt: "Neural Networks project img"
    title: "Task Classification of EEG Data with Neural Networks"
    excerpt: '*(joint work with T. Le, H. Unal, H.-C. Hung)*<br>
		In brain-computer interfacing, there has been an increased interest in the problem 
		of end-to-end electroencephalogram (EEG) signal decoding. In this project, we 
		studied deep neural networks with a range of different architectures for the purpose of 
		decoding four imagined tasks from raw EEG taken with 22 electrodes. First, two purely CNN architectures with different 
		network depths were considered. Next, performance of several architectures based on LSTM 
		and GRU was studied. The experiments have shown that the best testing accuracy of 62.8% 
		is achieved by using Deep ConvNet. This is unexpected because RNNs are known to handle 
		temporal series, like EEG, better than CNNs. <br>
		**Keywords**: *deep neural networks, convolutional neural networks, recurrent neural networks*<br>
		**Technical skills**: *Keras, TensorFlow, Python*'
    url: "/assets/pdfs/EE239_DeepLearning_EEG_Project.pdf"
    btn_label: "PDF"
    btn_class: "btn--primary"
pulse_est:
  - image_path: /assets/images/PPG_Estimate.png
    alt: "Computational imaging project img"
    title: "Remote PPG with POS and 2SR"
    excerpt: '*(joint work with J. Bunton)*<br>
		We explore the task of remote photo-plethysmography (rPPG), where we use 
		standard RGB videos to estimate a pulse signal of a human subject. We construct a simple 
		proof-of-concept algorithmic pipeline using both the Spatial Subspace Rotation (2SR) 
		and Plane-Orthogonal-to-Skin (POS) methods, requiring only one initial skin-pixel 
		identification step. We then verify output with a small sample from two 
		data sets, and discuss potential areas for improvement. <br>
		**Keywords**: *image processing, SVM, living skin tissue segmentation, remote photoplethysmography*<br>
		**Technical skills**: *MATLAB*'
    url: "/assets/pdfs/ECE_239AS_Imaging_Project.pdf"
    btn_label: "PDF"
    btn_class: "btn--primary"
---

{% include author-profile-inline.html type="left" %}

Independent problem solver with 
experience leading research and development – from 
conception to implementation – of cutting-edge algorithms 
for [*privacy in optimal control*](https://arxiv.org/abs/1906.07460) and [*learning from 
demonstrations*](https://github.com/sultangazin/cyphy_testbed/tree/LFD). Has more than 5 years of experience 
in *non-linear 
control and estimation* algorithms.  
{: .text-justify}  
   
Fast learner with a deep understanding of:
* nonlinear optimization
* motion planning algorithms 
* probabilistic robotics
* deep learning
* computer vision 
* reinforcement learning.  
{: .text-justify}  
 
Has a vast experience of 
clearly *communicating technical ideas* and a demonstrable 
[*track record of publications*](https://scholar.google.com/citations?hl=en&user=zf4Fxb0AAAAJ) in major journals and 
conferences. Adept in the modern software engineering tools
and practices.
{: .text-justify}  

## Research

{% include feature_row type="left" id="learning_from_demonstrations" %}

{% include feature_row type="left" id="privacy_in_control" %}

## Publications

A. Sultangazin, L. Fraile, and P. Tabuada, "Exploiting the experts: Learning to control unknown SISO feedback linearizable systems from expert demonstrations," to appear 2021 IEEE Conference on Decision and Control (CDC) 

A. Sultangazin and P. Tabuada, "Symmetries and isomorphisms for privacy in control over the cloud," in IEEE Transactions on Automatic Control, vol. 66, no. 2, pp. 538-549, Feb. 2021. 

A. Sultangazin, S. Diggavi and P. Tabuada, " Symmetries and Privacy in Control Over the Cloud: Uncertainty Sets and Side Knowledge," 2019 IEEE Conference on Decision and Control (CDC), Nice, France

A. Sultangazin, S. Diggavi and P. Tabuada, "Protecting the Privacy of Networked Multi-Agent Systems Controlled over the Cloud," 2018 27th International Conference on Computer Communication and Networks (ICCCN), Hangzhou, China, 2018, pp. 1-7. doi: 10.1109/ICCCN.2018.8487355

A. Sultangazin and P. Tabuada, "Towards the use of Symmetries to Ensure Privacy in Control Over the Cloud," 2018 IEEE Conference on Decision and Control (CDC), Miami Beach, FL, 2018, pp. 5008-5013. doi: 10.1109/CDC.2018.8619510

A. Sultangazin, J. Kusmangaliyev, A. Aitkulov, D. Akilbekova, M. Olivero and D. Tosi, "Design of a Smartphone Plastic Optical Fiber Chemical Sensor for Hydrogen Sulfide Detection." IEEE Sensors Journal, 17(21): 6935-6940, 2017. doi: 10.1109/JSEN.2017.2752717

## Selection of previous projects

{% include feature_row type="left" id="alphapilot" %}
{% include feature_row type="left" id="reinforcement" %}
{% include feature_row type="left" id="dmpc" %}
{% include feature_row type="left" id="neural_net" %}
{% include feature_row type="left" id="pulse_est" %}

## Professional Service

