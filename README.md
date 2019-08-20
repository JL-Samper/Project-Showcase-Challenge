# Project-Showcase-Challenge: A Federated approach for Degenerative Retinopathy diagnosis 
Udacity and Facebook Private and Secure AI Challenge

# Developers:
- ThienAn.  
      Slack user: ThienAn
      Github: thienan092
- José Luis Samper (jluis.samper@gmail.com)
      Slack user: J. Luis Samper
      Github: JL-Samper

# Abstract
Retinal affections is one of the major causes of blindness in the population. Early detection and appropiate treatment are crucial to stop the progress of the illness. Diagnoses relies on the expertise and visual acuteness of the ophthalmologist to detect retinal symptoms [xx]. The oculist checks the retina of both eyes by using special magnifying glasses and scan images, which alongside the patient's records provide information enough to detect the illness in most of the cases. However, a part of the population is highly exposed to late detection either by inability to afford the medical examination, lack of awareness or retina experts high-occupation. 

Among retinal affections, Diabetic Retinopathy (DR) has a high incidence rate [xxx]. During the last decade, big efforts have been done to obtain machine learning models able to detect the illness and diagnose it, like the population of journal articles and competitions denote. A successfull and useful diagnosis system should not only have a high accuracy, but also deliver scalability, data safety and usability. In this regard, a multiplatform application for retinal imaging diagnoses that applies federated learning methods can have a real impact and migration to real scenearios where medical personnel and patients interact with it.  

In this document we present a federated learning application that serves from state of the art methods for image recognition and classification to diagnose degenerative retinopathy. The system detects five different states of the retina and can be embedded in different devices, from computers to embedded boards. Currently, we are focusing on raspberry pi 4, and pc, but the future prospect also includes migration to mobile devices and other boards.

# Introduction

The last report of the World Health Organization estimate 36 million blind people worldwide, out of which 81% is avoidable and related to retinopathy [1]. A retinopathy occurs when blood leaks from the vessels to the retina creating sight problems which include distorted vision, dark zones in sight and color impairment among others. The retina is a membrane at the back of the eye sensitive to light, which is irrigated by blood vessels and moves over vitreus [2].

Diabetic retinopathy (DR) is among the most-common retinal affections with a 31,2% incidence rate in diabetic people [1].  One of the measures to reduce DR risks consists on regular screening [2]. In these screening images, experts look for signs of fluid entrance (like hollows or dark zones), aneurysms, exudates and excessive capilarity in the retina [3]. The National Eye Institute distinguishes between four stages of diabetic retinopathy: mild nonproliferative, moderate nonproliferative, severe nonproliferative and proliferative. The former two are characterised by retina distortion and the existance of balloon-like shapes, whereas in the latter two a proliferation of blood vessels occurs [4]. 

![alt text](https://media.discordapp.net/attachments/602098962719309856/602109554930614273/nrdp201612-f4.png)

So as to enhance diagnosis and preventive cares, several studies and challenges of machine learning models for DR detection have populated during the last decades. Some authors advocate for preprocessing and manual design of detectors. In these studies, several processing techniques are applied to highligth the retinal symptoms of retinopathy which are then classified by applying different types of functions like the feature candidates proposed by Flemming [5]. Habib et al [6] have recently analysed 70 features of retinal images and their impact on decision candidates performance. The retinal images are preprocessed by applying salt and pepper methods, surf and a vessel removal technique, developed by the authors. Then a decision tree classifies each of the symptoms detected by analysing the response of a series of weak classifiers. 

Attempts to improve performance and diagnosis have eventually led to the usage of deep learning models too [7]. Simple convolutional networks with few layers can stage diabetic retinopathy with an accuracy around 86,9% [8]. It is to expect than an increase on the depth of the model and the training database size can boost performance up. The American Academy of Ophthalmology have reported 93% accuracy for macular degeneration diagnosis using deep convolutiona networks based on VGG16 [9]. The macula is the part of the retina responsible for central vision which focuses on objects and acquires fine details [10]. 

Similar results have already been obtained for glaucoma. Glaucoma is an affection of the optical nerve whose diagnoses can only be done by medical eye experts. Its detection is really complex due to the fundus variance and shape of retina symptoms [10]. In this context, convolutional models with six or less layers reach accuracies around 83% [11], whereas deeper models increase performance to 93% [12]. 



# System Overview

# Results

# Troubleshooting and guides

# References
[1] Venkata SM Gudlavalleti  et al. "Public health system integration of avoidable blindness screening and management, India". Bulletin of the World Health Organization . Aug 2018. [Online] https://www.who.int/bulletin/volumes/96/10/18-212167/en/

[2] Retinopathy. Harvard Health Publishing. Harvard Medical School. [Online] https://www.health.harvard.edu/a_to_z/retinopathy-a-to-z

[3] Christian Nordqvist. "Diabetic retinopathy: Causes, symptoms, and treatments". Medical News Today. August 2017. [Online] 

[4] "Facts About Diabetic Eye Disease". National Eye Institute. [Online] https://nei.nih.gov/health/diabetic/retinopathy

[5]

[6] Habib et al. "Detection of microaneurysms in retinal images using an ensemble classifier". Informatics in Medicine Unlocked. 2017. 

[] Annahita Forghan et al. "Can AI Detect Diabetic Retinopathy More Accurately?". Diabetes in Control. Jan 2019. [Online] http://www.diabetesincontrol.com/can-ai-detect-diabetic-retinopathy-more-accurately/

