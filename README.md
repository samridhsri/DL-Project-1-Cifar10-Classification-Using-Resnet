
# Deep Learning Project 1 </br> 
# Cifar-10 Classification Using Resnet

**Team Members:** </br>
Samridh Srivastava (ss18906) </br>
Krittin Nagar (kn2670) </br>
Shikhar Malik (sm12762) </br></br>

This is the first project of Deep Learning (CS 6953 / ECE 7123) </br>
This project focuses on improving **image classification performance on the CIFAR-10 dataset** using an **enhanced ResNet-based architecture**. The model follows a **ResNet (4,4,4,3) configuration**, incorporating **Squeeze-and-Excitation (SE) attention** to refine feature selection and enhance learning. To improve generalization and prevent overfitting, **MixCut augmentations (MixUp + CutMix) were applied**, ensuring diverse feature learning. Additionally, **Cosine Annealing Learning Rate Scheduling** was used to stabilize training, and **mixed precision training (AMP) on an A100 GPU** optimized computational efficiency. The final model achieved a **test accuracy of 96.19%** while maintaining a **parameter count of 4.79 million**, balancing performance and efficiency effectively.