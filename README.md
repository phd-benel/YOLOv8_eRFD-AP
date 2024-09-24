# YOLOv8_eRFD-AP

Hy, Peace be upon you,

This repository contains the source code for the paper, **"Enhanced YOLOv8 for Robust Insulator Power Line Inspection: A Novel Approach to Weather-Resilient Anomaly Detection"**, submitted to **IEEE Access** on September 22, 2024. 

### Paper Abstract

The integration of drones equipped with artificial intelligence (AI) and computer vision for inspecting high-voltage power lines has garnered significant attention for its ability to detect critical anomalies, such as broken insulators, which are crucial for maintaining the reliability of electrical transmission systems. YOLO models, known for their speed and accuracy, are typically used for this task due to their effective real-time object detection capabilities. However, these models often struggle with generalization when exposed to diverse environmental conditions. To address this issue, we introduce YOLOv8-eRFD-AP, a novel model designed to improve performance across varying weather scenarios. Our approach involves training YOLOv8_eRFD-AP on standard weather conditions and subsequently testing it under adversarial conditions, including rain, fog, and snow, using the IDID_Weather dataset. This model incorporates Robust Feature Downsampling (RFD), Convolutional Block Attention Module (CBAM), and Normalization Perturbation (NP) to enhance its robustness. Experimental results demonstrate that YOLOv8_eRFD-AP significantly outperforms state-of-the-art models, including YOLOv9, YOLOv10, and RTDETR, particularly in terms of generalization and resilience in non-uniform domains such as rain and snow. Futhermore, it not only achieves superior accuracy but also maintains computational efficiency, making it a practical solution for real-time anomaly detection in challenging environments. This work underscores the potential of YOLOv8-eRFD-AP to advance inspection processes and reduce operational costs, with future research aiming to optimize NP for handling both uniform and non-uniform distributions more effectively. 

### Data
The dataset used in this study consists of weather-affected images of insulators and can be accessed at the following link: 


![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/dead223b-3855-401d-9ec4-4194cfe24b55) Original : https://universe.roboflow.com/search?q=idid_original&t=metadata

![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/181fec43-d13c-4af8-9aca-9d034e5d7cad)Original + Rain : https://universe.roboflow.com/search?q=idid_rain&t=metadata


![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/02c09780-c3e1-4844-b3c5-ccf72acbf797)Original + Snow : https://universe.roboflow.com/search?q=idid_snow&t=metadata


![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/79de1b4d-7873-44b6-b845-81fca2e6377c)
Original + Fog : https://universe.roboflow.com/search?q=idid_fog&t=metadata

### Model Architecture

The architecture of the enhanced YOLOv8 model will be upload soon. This is to protect the integrity of the contributions made in this research.

### Experimental settings
The experimental settings can be found at the following link from the ClearML MLOPS platform : 
https://app.clear.ml/projects/3e329ae202b44751b59e719885763bef/compare-experiments;ids=01c45d6172d94914861e5b7e22109b91,fa243612b16542a283cc981d8e51959f,937da49598ce4913b11a404ee7db48a4,4d7d8915247e4cbfa80ee5c8df7eb946,1abdcb6b50734da9be7263a4a4865b57,6ae6d3368dc048b49faf4237da6689e4,e3d71319f244482b97073575797c34e2,a94b5129ffa944128e4c6dbde4ac7b95,e732ec649d6941038357fb428011356a,a5cdd1782be14d02a75d8e86c09526b9/scalars/graph

### Code
The source code for the enhanced YOLOv8 model will be made publicly available upon acceptance of the paper to **IEEE Access**. This is to protect the integrity of the contributions made in this research.

### Citation
The paper is currently under review for publication in **IEEE Access**. Once accepted, please cite the paper using the following format (to be updated).

### License
This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. Please refer to the `LICENSE.md` file for detailed information.

### Acknowledgments
We would like to extend our gratitude to the **Ultralytics YOLOv8** community for their invaluable contributions and resources, which significantly aided in the development of this research.

### Contact
For further information or inquiries, please feel free to report an issue on this repository. I am happy to provide assistance and clarification as needed.

