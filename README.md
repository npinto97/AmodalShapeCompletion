# Amodal Shape Completion

In this study, we tackle the challenge of **amodal shape completion**, a key computer vision task that involves predicting the full shape of partially occluded objects. This problem has broad applications in robotics, autonomous driving, augmented reality, and object recognition. Traditional recognition and segmentation methods struggle with occluded objects due to their reliance on visible features, highlighting the need for improved shape prediction techniques.  

We introduce **Light 2-Step Amodal Shape Completion**, a two-step approach combining **UNet and CNN architectures**. The first step predicts the **occlusion mask** based on the visible object mask, while the second step reconstructs the **amodal mask**, representing the complete silhouette of the object. Our models are trained and evaluated on the **COCOA dataset**, which provides rich annotations for both modal and amodal masks.  

Experimental results show promising performance, achieving **mIoU = 0.75**, despite computational limitations. Our approach demonstrates robustness even under resource constraints, surpassing initial expectations. Given the lack of reproducible experiments in existing literature, we adapted and innovated upon prior studies to refine our methodology.  
