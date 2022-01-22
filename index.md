---
layout: default
title:  Paul Rigor's Theses
---

## Algorithm Selection for Subgraph Isomorphism Problems: A Reinforcement Learning Approach

#### Paul Rigor (2018). _Thesis, M.S. Computer Science_. Universiti Teknologi Malaysia.

A set of hard computational problems can be solved more efficiently when using multiple algorithms instead of a single algorithm. This technique is called algorithm selection. An algorithm selection model captures the relationship between problem features and algorithm performance, using this knowledge to assign the best-performing algorithms to problems. Most approaches in literature use supervised learning techniques to learn the problem feature–algorithm performance relationship. This study presents a different perspective by training algorithm selection models using reinforcement learning---an experience-driven learning approach inspired by how humans and animals naturally learn from their environment. REINFORCE, the proposed reinforcement learning algorithm, is compared with pairwise random forest regression, a supervised learning algorithm from a previously related study. Experiment results show that an algorithm selection model trained using REINFORCE performs poorly as compared to one trained using pairwise random forest regression. However, zooming into the results reveal that REINFORCE did better than pairwise random forest regression on solving the easier problems, which constitutes the majority of the dataset. Still, REINFORCE fails because it is not able to perform well on solving the much harder problems on the dataset, which have a huge impact on the final calculation of algorithm selection performance scores. Nevertheless, this study maintains hope on the potential of reinforcement learning in producing algorithm selection models with better performance than models trained using supervised learning techniques.

[project page][project_algosel] \| [full text][paper_algosel]

---

## Artificial Neural Network Controller for Single Digit Pattern Recognition using FPGA

#### Paul Rigor, D. Soriano, & M.K. Velayo (2011). _Thesis, B.S. Computer Engineering_. Mapua Institute of Technology.

The purpose of this study is to design an artificial neural network for single digit pattern recognition, making use of a field programmable gate array (FPGA) as the main component in implementing its architecture. The study aims to determine which of the two neural network models, single layer perceptron model (SLP) with perceptron learning rule and multilayer perceptron (MLP) model with backpropagation learning, will be used in the implementation of the architecture of the artificial neural network controller. The software simulation shows that the SLP results to 94.13% mean accuracy while the MLP results to 94.96% mean accuracy. With only 0.8779% difference between the mean accuracies of both model, the complexity of each model is considered as the main criterion in selecting the model to be implemented in hardware. With a total number of 25 neurons in its structure, the SLP is chosen for the hardware implementation. The hardware implementation gives 95.60% mean accuracy. The percentage difference between the results in software simulation and hardware simulation is 1.5496%. The result of the hardware implementation is consistent with the result of the software simulation. The outcome of both simulations suggests that the neural network model implemented in hardware is accurate and effective in recognizing patterns presented to it. The system is able to learn and recognize perfect and corrupted single digit patterns accurately.

[full text][paper_ann]

---

## Design of Laboratory Experiments and Trainer Boards for Arduino Using Gizduino Microcontroller Kit

#### Paul Rigor, M.J. Baldon, K.L. De Leon, K.R. Oballo, & M.K. Velayo (2011). _Technical Report, B.S. Computer Engineering_. Mapua Institute of Technology.

Knowing to program microcontrollers is necessary for engineering students since it helps in building design prototypes, which are normally required in Thesis, Engineering Design, and other related subjects. Our aim is to develop a microcontroller laboratory course based on the Arduino microcontroller. The laboratory course covers 6 experiments: Basic I/O, Advanced I/O, Analog-to-Digital Conversion, Motor Control, Serial LCD Display, and Wireless Communication. Each experiment consists of ojectives, discussion of the topic, trainer board schematic diagram, experiment procedures, and activities. To evaluate the effectiveness of the laboratory course, we asked volunteer EECE students to try it out. The evaluation results showed that the laboratory course helped the students in gaining practical knowledge in programming microcontrollers. We were able to meet our objective in creating an effective microcontroller laboratory course beneficial to our fellow engineering students. 

[full text][paper_arduino]

[project_algosel]: https://github.com/kvrigor/algosel-rl
[paper_algosel]: files/thesis_algosel.pdf
[paper_ann]: files/thesis_ann.pdf
[paper_arduino]: files/design_arduino.pdf
