# Automated Detection and Classification of Gastrointestinal Bleeding in Wireless Capsule Endoscopy                    

## AIM: 

#### The aim of this project involved testing and evaluation of Artificial Intelligence (AI) models for automatic detection and classification of bleeding and non-bleeding frames extracted from **Wireless Capsule Endoscopy (WCE)** videos. 

#### The training dataset consists of 2618 bleeding and non-bleeding WCE frames collected from multiple internet resources, datasets with a vast variety and types of gastrointestinal (GI) bleeding throughout the GI tract along with medically validated binary masks and bounding boxes in three formats (txt, XML and YOLO txt).

#### The training dataset is passed through a deep learning architecture based **Convolutional neural network(CNN)** for feature extraction and then the feature map is passed to the **Rectified Linear Unit (ReLU)** activation function to get the resulting classification into two classes - **GI bleeding** and **No GI bleeding**.

#### The test dataset is an independently collected WCE data containing bleeding and non-bleeding frames of more than 30 patients suffering from acute, chronic and occult GI bleeding referred at **Department of Gastroenterology and HNU, All India Institute of Medical Sciences**, New Delhi, India.

## OVERVIEW:

#### GI bleeding is a medical condition characterized by bleeding in the digestive tract, which circumscribes esophagus, stomach, small intestine, large intestine (colon), rectum, and anus. Since blood flows into the GI tract, a cascade of risks emerge, ranging from immediate dangers to potential long-term consequences. Excessive blood loss from GI bleeding may lead to a drop in blood pressure, reduced oxygen delivery to organs and tissues, and potentially life-threatening organ dysfunction. According to World Health Organization (WHO), gastrointestinal bleeding is responsible for approximately 300,000 deaths every year globally. These statistics serve as a catalyst for research, propelling innovative treatment modalities and diagnostic advancements aimed at mitigating the dangers posed by GI bleeding. Therapeutic Endoscopy Guidelines and Recommendations 2018-19 released by Indian Association of Gastrointestinal Endo Surgeons have recommended the use of WCE as an initial test for stable patients with overt or occult bleeding. 
#### The disposable capsule-shaped device travels inside the GI tract via peristalsis and comprises of an optical dome, a battery, an illuminator, an imaging sensor, and a RF transmitter. During 6-8 hours of WCE procedure, a video of the GI tract trajectory is recorded on a device attached to the patient’s belt which produces about 57,000-1,00,000 frames; analyzed posterior by experienced health experts. Presently, an experienced gastroenterologist takes approximately 2−3 hours to inspect the captured video of one-patient through a frame-by-frame analysis which is not only time-consuming but also susceptible to human error. In view of the poor ratio of patient-to-doctor across developing countries like India, there arises a need for investigation and state-of-the-art (SOTA) development of robust, interpretable and generalized AI models that can aid in reducing the burden on gastroenterologists and save their valuable time by computer-aided classification between bleeding and non-bleeding frames and further detection of bleeding region in that frame.

## FRAMES:

* **BLEEDING FRAME**
![A0509](https://github.com/twishackaul/Gastrointestinal-Bleeding-Classifier/assets/107127632/bd473890-8f6f-4d3c-9bf9-c5651dbdcda1)

* **NON-BLEEDING FRAME**
![A0511](https://github.com/twishackaul/Gastrointestinal-Bleeding-Classifier/assets/107127632/65ec2d07-d9c6-4043-ba4f-fd4bf3e53a52)




  
