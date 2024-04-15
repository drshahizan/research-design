# Exercise 1:  Chapter 1 - Introduction

### Project Title: ENHANCED MULTI-CLASS ENSEMBLE TRANSFORMER BLOCK CONVOLUTIONAL VARIANTS ARCHITECTURE FOR OFFSHORE OIL SPILL DETECTION

### Prepared by: Salihu Abubakar Abba, PEC223001, Abubakar-Salihu

## 1.1 Introduction

Petroleum is still the world's most important source of energy and is essential to human life. Its deep ocean drilling and logistics-related activities pose the possibility of oil and gas spills or leakages that would have immediate effects on society (Negreiros et al., 2022). Consequently, oil and gas account for more than fifty percent of the world's total energy consumption and they serve as the most important energy sources for global economic activity. Likewise, the distribution of oil and gas through the pipeline is the safest and most cost-effective approach, although it is prone to leakage problems (Chen et al., 2021).

An offshore oil spill (OOS) is the accidental release of petroleum by-products into the marine environment during transportation because of leakages from the pipeline, vessels or oil rigs which cause serious damage to the marine invertebrates and the soil itself. Equally, the most hazardous spills are the underwater spills, which are more dangerous than any other spill due to their widespread within a short period, polluting the environment thereby making it unfavorable and could harm the health of people in general and the aquatic animals. Therefore, proper monitoring of oil spills, and oil exploitation activities as well as early response to the top management of the energy resources is vital. 

There exist different methods utilized by researchers in detecting and identifying the exact point of the leakages from underwater pipelines such as statistics methods (Arslan et al., 2023), traditional machine learning methods (Yekeen and Balogun, 2020c), and some conceptual classification of deep learning methods (Blondeau-Patissier et al., 2023). Yet, methodologies have some weaknesses, which are fundamental and vital features to consider. Therefore, it is paramount to employ robust monitoring and detection techniques for early and accurately detecting oil spills thereby cutting down the likelihood of pipeline breaking during its useful life which usually affects the smooth operation of the oil and gas industries (Yuan et al., 2023).

Due to the great advancement in remote sensing (RS) approaches such as complexity and wider coverage coupled with the rapid improvement of deep learning (DL) techniques in object detection and classification, the detection of oil spills has become possible from satellite images. Similarly, RS approaches possess the great benefit of real-time tracking, wireless coverage of the vast area, and constant monitoring by aerial imaging accurately and objectively (Bianchi et al., 2020).

Several improvements have been made recently in DL for oil spill detection (Yang et al., 2022b), even though DL has proven to be an efficient approach in the early identification of oil slicks (Vasconcelos et al., 2023) thereby minimizing the false alarm of differentiating the original oil and gas spill with the other exact likeness features within the given image. Hence the negative impact of the spills on the offshore environment can also be minimized. 

Many studies have utilized the traditional SVM and ANN for satellite-based oil spill detection (OSD) (Singha et al., 2012, Singha et al., 2013, Ma et al., 2014, Wan and Cheng, 2013, Mera et al., 2017). However, the efficacy of classification is constrained by the fact that these techniques are restricted to the feed-forward classification of images and do not enable end-to-end trainable systems (Zeng and Wang, 2020a). In recent times, DL algorithms are being utilized due to their capability of extracting important and relevant features during training and learning processes (Jiao et al., 2019, Zeng and Wang, 2020b, Zhang et al., 2020).

## 1.2 Background of the Problem

Oil and gas spills on the water surface are seen nowadays mainly in major transportation routes. It is caused by a collision of liquefied petroleum gas tankers or leakages from ships or vessels. However, conventional DL models were used by many researchers but were unable to discriminate the oil spill (Dasari et al., 2022). 

Traditional DL models for OSD in offshore environments typically involve using various methods to examine satellite data which is the most widely used tool for monitoring large bodies of water for proper detection and classification of oil spills by DL. Likewise, models find it difficult to manage natural diversity in an offshore environment, which includes the amount of noise in the data and water surface viscosity, leading to a false dissimilarity between real oil spills and the variations found in nature.

The presence of oil spill resemblance is necessarily due to the occurrence of natural phenomena in the ocean with high similarity with oil spills and accurate detection is so challenging when there is an overlap between them (Fan and Liu, 2023). Additionally, extracting prominent information using conventional ML models is quite challenging, and the model’s efficiency solely depends on the relevant and prominent information extracted from the data that precisely captures the distinctive features of oil spills (Al-Ruzouq et al., 2020). 

Wind speed and flow are affecting the reliability of many detection techniques using SAR sentinel-1 SAR data (Marghany, 2019, Naz et al., 2021) and also the issues of incomprehensive and imbalanced training data with well image annotation to avoid boundary errors, particularly in long and narrow features (de Moura et al., 2022, Huang et al., 2022). Hence, handling dynamic changes in oil spills is challenging with many conventional DL models due to the dynamic nature that usually changes over time (Wang et al., 2021a).

The efficiency and the reliability of DL models can be affected by the quality of satellite data. Although high-quality remote sensing data find it difficult for traditional ML models to process conveniently and accurately while low-quality data usually produce incorrect results (Whang et al., 2023), manual labeling of oil spill areas in the dataset by humans may introduce errors and irregularities which affect the performance and reliability of detection model. 

Despite the success of SAR data in the field of oil spill (OS) identification, there are still key problems of false alarms for the detection of exact resemblance as oil spills due to high similarity because of natural conditions occurring in the marine environment such as the presence of algae blooms, rain cells, and grease ice (Krestenitis et al., 2019, Temitope Yekeen et al., 2020). Therefore, an efficient method to accurately distinguish between oil spills and any other natural phenomena needs to be put in place for smooth operation and ease of decision-making processes in the oil and gas industries. However, utilization of classification with instance segmentation of oil spills is the obvious technique that incorporates the identification of dark spots, feature extraction, and classification. However, due to the interdependencies between the three stages, the model is not reliable as it can produce incorrect results, particularly if the OS is thin (Krestenitis et al., 2019).

SAR image is the most widely used dataset in the field of OS monitoring due to its ability not to be affected by climate changes because of using active sensors. Low wind speed, rain, upwelling, and water body characteristics usually weaken the reflecting of light thereby causing the appearance of oil spills as dark spots which are usually associated with the sea radar brightness. However, when the waves were generated at low wind speeds, it caused the whole image to be dark resulting in the misclassification of real OS using SAR data (Jafarzadeh et al., 2021). Therefore, discerning oil spills from other exact likenesses is quite a difficult task that needs to include a thorough analysis of SAR images that incorporate texture, and shape at any weather conditions, size, color, location, and gradient. 

Identifying OS borders with other exact likenesses in the offshore environment is a challenging task due to the same shape possessed coupled with the low percentage of oil spill pixels about the total pixels in the entire image (Dehghani-Dehcheshmeh et al., 2023). Similarly, considering only SAR images as input data is not enough due to the limitation of going through the pixel level. Therefore, different OS geometries including texture information of oil spills and scales have to be introduced through a variance filter for discriminating between the OS and exact likeness, as a result of local geological and morphological features, such as reef structures that inherently create similar features (Blondeau-Patissier et al., 2023).

To detect OS, many DL models utilized their embedded feature extraction technique. However, it is important to remember that feature extraction in CNNs usually requires a large amount of annotated data to achieve good training results including time and resource consumption. Consequently, CNN may become computationally more complex with multiple feature extraction layers, which would slow down training and impact interference time (Subasi, 2020, Alzubaidi et al., 2021, Alzubaidi et al., 2023). Additionally, excessive feature extraction can lead to overfitting, especially when working with smaller datasets. The model may work well with training data but has difficulty generalizing to new, untested data (Gao et al., 2023)


## 1.3 Statement of the Problem

Satellite imagery is of paramount importance in a multitude of domains, including spill detection using DL approaches. Considering prominent information in SAR data is beneficial for improving OSD and classification by incorporating important features such as texture information and edge features. Recent research articles have directly applied SAR, only considered pixel intensity values, and neglected other important spatial features. This has led to false positives regarding the discrimination of oil spills and other natural phenomena known as “lookalikes,” which closely resemble oil spills in offshore environments. In addition to the discrimination problem, most techniques find it difficult to properly segment the spill areas when there is an overlap between oil spills and similar events within the image. 

Additionally, the class imbalance complication with multiclass oil spill dataset (the ratio of oil spills classes and non-spills within the SAR images are not balanced) problem still exists due to the low percentage of spills compared with other classes within the limited SAR images; This led to excessive data augmentation and feature extraction within the DL models which resulted in model overfitting and poor generalization. Consequently, generating classification results without accounting for imbalanced datasets leads to suboptimal accuracy levels, as well as instances where minority categories can exert undue influence over the classification model. Therefore, it is crucial to choose appropriate methods for enriching the dataset without introducing biases.

Despite the potential demonstrated by DL models in the realm of oil spill detection, it is crucial to acknowledge the presence of various challenges that pose significant obstacles to the effectiveness and efficiency of these models including limited training data which hinder the model’s performance of slick detection, insufficient feature extraction which subsequently affects the accuracy of OSD and effective segmentation models for OS is a difficult task due to the limited availability of data on spill incidents and the complexities involved in accurately defining spill boundaries. Currently, to the best of my knowledge, there is practically no research work that considers edge feature detection in SAR images integrated with under-sampling techniques for imbalance learning to improve the performance of oil spill detection.


## 1.4 Research Questions

To achieve the goal of this research, the following research questions will be considered extensively, and they will serve as the basis on which this research will be formed: 

(a)	How to extract a spatial feature (edge features) in synthetic aperture radar images to improve the performance of the spill detection model?

(b)	How can a hybrid of random under-sampling approaches be effectively utilized in SAR images for achieving optimal class balance without introducing biases towards the majority class?

(c)	How can a combination of edge features with under-sampled data be effectively utilized for enhancing the performance of detection models to segment the real spills and other exact resemblances?


## 1.5 Objectives of the Research

The purpose of this research is to develop an enhanced multiclass ensemble convolutional variant architecture to improve oil spill detection. To this end, it utilizes the DL approach with Vision Transformer based on SAR images and feature extraction for proper detection and discriminating against oil spills with other exact resemblances.

(a)	To construct a weighted feature extraction approach using Scale-Invariant Feature Transform (SIFT) from SAR images for edge detection improvement. 

(b)	To propose a hybrid of Random Under-Sampling (RUS) and Weighted Cross Entropy Loss (WCEL) for imbalance learning.

(c)	To propose an ensemble Faster-RCNN with Vision Transformer (FasterViT) DNN architecture to improve oil spill detection.


## 1.6 Scope of the Study

The scope of this research is limited to the following:

(a)	This research thesis focuses on detecting oil spills in the offshore environment rather than the onshore environment. 

(b)	This research thesis considers edge features from SAR image data using the weighted approach and under-sampling techniques for imbalance learning.

(c)	This research focuses only on satellite data, particularly SAR images, collected from the European Space Agency (ESA) database; the Copernicus Open Access Hub acquired via the Sentinel-1 European Satellite missions. 

(d)	This research is concerned with improving the model performance for detecting salient features of the oil spill images using DL approaches with transformer block.

(e)	In this research, the performance metrics for testing the proposed model are based on accuracy, precision, recall, F-1 score, and intersection over union (IoU), which would be calculated after multiple model executions.


## 1.7 Significance of the Research

The research is expected to contribute to the goal of building healthier communities along the coast when it comes to pollution by providing oil and gas companies and legislators with an innovative strategy to monitor oil pollution, implementing tools to support response and recovery, and ultimately to avoid the dangers and harmful effects on people and the natural environment including the national economy.

The following are expected to be the key contributions to this research:

(a)	Model development: A proficient detection model possessing the ability to differentiate oil spills in SAR images from similar-looking substances. The precise inference of latent feature variables plays a vital role in enhancing the accuracy of oil spill detection. Consequently, unlike traditional detection approaches, the model excels in discerning oil spill SAR images by extracting significant features crucial for distinguishing actual oil spills from deceptive appearances.

(b)	Environmental Safety: Oil and gas spills can cause serious injuries to human life. So, developing a reliable, efficient, and effective detection system that can automatically detect spills early will minimize the risk associated with the leakages and ensure people's safety.

(c)	Operational Performance: Detection of oil and gas spills in real-time will improve the performance of the general operations of the oil and gas industries. It eliminates the time taken to detect and repair it, which disrupts the operation and causes some loss due to delay in identification. 

(d)	Cost: Leakages from pipelines or vessels carrying oil and gas in the marine environment cause serious economic losses due to the market value of the product. Developing an effective monitoring and detection technique can help cut the cost of the losses if identified early.


## 1.8 Structure of the Thesis

Chapter 1 of this thesis provides a general overview of the research area, the problem statement, the goal of the research, the research contribution, and the significance of the research to the community and the government in general. The other sections of this thesis include the following: Chapter 2 highlights the related literature on oil spill detection using traditional machine learning techniques and deep learning approaches based on satellite data and the review of the closely related literature to this study including the DL taxonomy, the fundamental of oil spill detection, the consequences and the characteristics of oil spills, and research gaps. Chapter 3 highlighted the proposed solution based on the problem highlighted in Chapter 1, the research design and the overall operational framework of the thesis, and the evaluation criteria for oil spill detection and classification. In chapter 4 of this thesis, the widely utilized dataset was presented, the computational requirement needed to implement the proposed approaches, and finally the initial results were presented for proposal defense together with the summary and conclusions of the research. 

## 1.9 Summary

This chapter discusses the problem background and challenges faced by oil spills detection based on ML approaches using remote sense datasets. This chapter principally highlights the background of the problem that maps the oil spills data research questions and objectives. The research scope and contribution of the study have also been provided to support the research. Moreover, the thesis’ organization has also been discussed to give an overview of subsequent chapters. Additionally, the next chapter discusses the literature review of recent and related studies that provides the reasons to begin this thesis. 
