# YOLOv8_eRFD-AP

Hy, Peace be upon you,

This repository contains the source code for the paper, **"Enhanced YOLOv8 for Robust Insulator Power Line Inspection: A Novel Approach to Weather-Resilient Anomaly Detection"**, accepted in **IEEE Access** on September 22, 2024. 

### Paper Abstract

The deployment of artificial intelligence (AI)-powered uncrewed aerial vehicles (UAVs) for high-voltage power line inspection has become a crucial advancement in ensuring the stability and reliability of electrical transmission networks. Among various deep learning architectures, You Only Look Once (YOLO)-based models are widely used due to their real-time object detection efficiency. However, these models frequently struggle to generalize when exposed to diverse environmental conditions. To address this, we present YOLOv8-eRFD-AP, an enhanced YOLOv8 variant designed to improve generalization ability across varied weather scenarios for insulator anomaly detection. The model is trained under clear-weather conditions and evaluated on the IDID_Weather dataset, which includes rain, fog, and snow, to assess its performance under real-world challenges. Our model introduces a novel version of Robust Feature Downsampling (RFD) method, enhanced with Convolutional Block Attention Modules (CBAM) and Normalization Perturbation (NP) to preserve key spatial information and improve feature discrimination across different weather conditions. Experimental results confirm that YOLOv8-eRFD-AP outperforms state-of-the-art models, including YOLOv11, YOLOv12, and Real-Time Detection Transformer (RT-DETR), in both clear and adverse weather settings. The model achieves a mean average precision at 0.5 intersection over union (mAP@0.5) of 92.0%, exceeding the second-best model by 2.7% under clear weather. Under rain and snow, it attains 85.2% and 73.1%, reflecting improvements of 10.3% and 13.3%, respectively, over prior best-performing models. Despite the improved generalization ability, the proposed model remains real-time capable, achieving an inference speed of 12.5 ms per image (~80 frames per second, FPS) on a Tesla T4 graphics processing unit (GPU). This work demonstrates the potential of YOLOv8-eRFD-AP to enhance UAV-based power line inspections, particularly by improving generalizat...

### Data
The dataset used in this study consists of weather-affected images of insulators and can be accessed at the following link: 

https://github.com/phd-benel/weather_powerline_insulator

### Model Architecture

![benel2-3593201-large](https://github.com/user-attachments/assets/904988cf-8333-4fb9-8e92-b4dc468cfa87)

### Experimental settings
The experimental settings can be found at the following link from the ClearML MLOPS platform : 
https://app.clear.ml/projects/3e329ae202b44751b59e719885763bef/compare-experiments;ids=01c45d6172d94914861e5b7e22109b91,fa243612b16542a283cc981d8e51959f,937da49598ce4913b11a404ee7db48a4,4d7d8915247e4cbfa80ee5c8df7eb946,1abdcb6b50734da9be7263a4a4865b57,6ae6d3368dc048b49faf4237da6689e4,e3d71319f244482b97073575797c34e2,a94b5129ffa944128e4c6dbde4ac7b95,e732ec649d6941038357fb428011356a,a5cdd1782be14d02a75d8e86c09526b9/scalars/graph

### Code

Please, run this Colab notebook to replicate the results obtained : https://colab.research.google.com/drive/1G1WKXi3xQO2uzXxrXsWym00fVp2FBit4?usp=sharing

### Citation

B. -E. Benelmostafa, R. Aitelhaj and H. Medromi, "YOLOv8-eRFD-AP: A Novel Domain Generalization Model for UAV-Based Insulator Inspection Under Adverse Weather Conditions," in IEEE Access, vol. 13, pp. 135336-135358, 2025, doi: 10.1109/ACCESS.2025.3593201.
keywords: {Meteorology;Inspection;YOLO;Autonomous aerial vehicles;Computational modeling;Accuracy;Training;Real-time systems;Drones;Artificial intelligence;Automatic optical inspection;adaptation models;anomaly detection;object detection;deep learning;computer vision},


### License
This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. Please refer to the `LICENSE.md` file for detailed information.

### Acknowledgments
We would like to extend our gratitude to the **Ultralytics YOLOv8** community for their invaluable contributions and resources, which significantly aided in the development of this research.

### Contact
For further information or inquiries, please feel free to report an issue on this repository. I am happy to provide assistance and clarification as needed.

