# Certifying the Robustness of Machine Learning Intrusion Detection Under Adversarial Perturbation

2024-2025 Department of Business and Computing, Ravensbourne University London (RUL), London, United Kingdom

Authors: [Ehsan Nowroozi](https://scholar.google.com/citations?user=C0bNkP8AAAAJ&hl=en) , Email: ehsan.nowroozi65@gmail.com

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.

---
This repository contains the research paper titled "Verifying the Resilience of Machine Learning Intrusion Detection Against Adversarial Attacks". The paper investigates the robustness of AI in Intrusion Detection Systems (IDS) by employing a formal verification method called interval-bound propagation (IBP) on shallow and deep neural networks (DNNs).


#  Introduction:
The abstract of the academic paper emphasizes the prevalent utilization of neural networks (NNs) in security-related endeavors and underscores the hurdles stemming from their inherent opacity and susceptibility to adversarial exploits. It presents a fresh strategy for assessing AI resilience within IDS, employing the IBP technique across both shallow and deep neural networks. Additionally, it investigates the efficacy of various activation functions in bolstering model resilience. The results indicate that ReLU and Leaky-ReLU activation functions demonstrate heightened resilience against adversarial attacks in shallow networks, whereas Tanh activation functions exhibit superior performance in deep networks.

# Usage
The research paper titled "Assuring Machine Learning Intrusion Detection's Strength Against Adversarial Perturbation" offers significant insights into employing formal verification techniques, notably the interval-bound propagation (IBP) method, to bolster the security and resilience of neural networks within Intrusion Detection Systems (IDS). Additionally, it delves into assessing the effectiveness of diverse activation functions in bolstering model robustness.

Scholars and professionals within cybersecurity and machine learning domains can utilize this paper as a resource to delve deeper into the methodologies employed and to contemplate potential applications of formal verification techniques in IDS. The paper introduces a novel approach to verifying AI resilience in IDS and sheds light on the effectiveness of various activation functions in enhancing model robustness.

For a comprehensive understanding of the coding implementation and practical dimensions of the study, it is advisable to refer to the complete research paper and any accompanying codebase (if accessible). Such resources may include implementations of neural network models, the IBP method, and evaluations of different activation functions.

## Activation Functions:

The research paper examines the efficacy of various activation functions in augmenting the model robustness of neural networks within IDS. Particularly, it scrutinizes the performance of the Rectified Linear Unit (ReLU), Leaky-ReLU, and Tanh activation functions.

The research findings suggest that models incorporating ReLU and Leaky-ReLU activation functions demonstrate heightened resilience against adversarial attacks in shallow networks. Conversely, Tanh activation functions yield superior outcomes in deep networks. These results underscore the significance of selecting the appropriate activation function based on network architecture and the specific demands of the IDS application.

The research paper furnishes valuable insights into how activation functions impact model performance and robustness. Scholars and practitioners can further explore the ramifications of different activation functions within their neural network models for IDS applications.

# Understanding the Problem:
Intrusion Detection Systems (IDS) are vital components in safeguarding networks against cyber threats by scrutinizing network traffic and detecting potentially malicious activities. Deep neural networks (DNNs) are extensively employed within IDS frameworks for diverse tasks such as identifying spam, detecting malware, and recognizing anomalies in network behavior. Nevertheless, the inherent complexity and opacity of DNNs raise concerns about their reliability, security, and safety during deployment. A primary challenge confronting IDS implementations is the susceptibility of DNNs to adversarial attacks, where deliberately manipulated inputs lead to misclassifications by the neural network while remaining imperceptible to human observers. These attacks exploit blind spots in high-dimensional ML models, posing significant security risks to IDS systems by potentially enabling attackers to evade detection or introduce vulnerabilities during model training.

To confront these challenges, the research paper introduces an innovative approach to verifying AI resilience in IDS by leveraging the interval-bound propagation (IBP) method across both shallow and deep neural networks. IBP offers a means to quantify neural network resilience against adversarial attacks and provides formal guarantees regarding performance. By integrating IBP, the paper aims to bolster the security and robustness of neural networks within IDS applications. Additionally, the paper investigates the efficacy of various activation functions such as ReLU, Leaky-ReLU, and Tanh in strengthening model robustness, recognizing the critical role activation functions play in the non-linear transformations within neural networks and their potential impact on resistance to adversarial attacks.

# Coding
To enact the proposed strategy of augmenting the security and resilience of neural networks within Intrusion Detection Systems (IDS), coding would be necessary using a language such as Python. Below outlines the general procedure for coding the program:

## Data Preparation: 
Begin by loading and preprocessing the IDS dataset. This typically involves tasks like reading pcap files, extracting pertinent features utilizing tools like NFStream, and formatting the data for training and testing purposes.

## Neural Network Architecture: 
Define the structure of the neural network model. Utilize frameworks like TensorFlow or PyTorch for model creation. Take into account the specific demands of IDS and select suitable layers, activation functions, and optimizers.

## Training Phase: 
Segment the dataset into training and validation subsets. Employ the training set to train the neural network model. Implement methodologies like IBP to validate the model's resilience against adversarial attacks. Keep track of the model's performance metrics, accuracy, and loss throughout the training process.

## Activation Functions: 
Experiment with various activation functions such as ReLU, Leaky-ReLU, and Tanh. Integrate these functions into the appropriate layers of the neural network model. Assess and contrast the model's performance and robustness under different activation functions.

## Assessment: 
Utilize the test set to evaluate the trained model's performance. Gauge metrics like accuracy, precision, recall, and F1-score to gauge the model's effectiveness in intrusion detection and adversarial attack handling.

## Refinement and Optimization: 
Analyze the outcomes and refine the model if needed. Consider adjustments to hyperparameters, exploration of alternative architectures, or application of regularization techniques to further enhance the model's performance and resilience.



# If you utilize this code, kindly cite the following papers in your *.bib file:

 XXXX XXXX XXXX
