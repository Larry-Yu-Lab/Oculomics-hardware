Oculomics Hardware Assembly 

Cardiovascular diseases (CVDs) are the leading cause of death globally. An estimated 19.8 million people died from CVDs in 2022, representing approximately 32% of all global deaths. Of these deaths, 85% were due to heart attack and stroke. Over three quarters of CVD deaths take place in low- and middle-income countries.
Out of the 18 million premature deaths (under the age of 70) due to noncommunicable diseases in 2021, at least 38% were caused by CVDs. Most cardiovascular diseases can be prevented by addressing behavioural and environmental risk factors such as tobacco use, unhealthy diet (including excess salt, sugar, and fats) and obesity, physical inactivity, harmful use of alcohol and air pollution. It is important to detect cardiovascular disease as early as possible so that management with counselling and medicines can begin.

Oculomics is an emerging interdisciplinary field that uses computer vision, artificial intelligence, and non-invasive ocular imaging (such as retinal photography and Optical Coherence Tomography) to identify systemic health conditions and biomarkers.

Because the retina is the only place in the human body where vascular structures and neural tissue can be directly observed non-invasively, analysis of retinal features can reveal early indicators for a wide variety of systemic conditions.

This Oculomics project is a low-cost, smartphone-based retinal imaging and AI diagnostic platform designed to make non-invasive systemic health screening accessible at the point of care.

By capturing retinal images via portable hardware and processing them with deep learning models, the system aims to identify early systemic disease biomarkers—particularly for cardiovascular and renal conditions—without requiring expensive, stationary clinic equipment.

The purpose of this project is to develop a low-cost device that can early detect signs of stroke and cardiovascular disease by scanning for biomarkers within the eye.

Core Components & Implementation

Hardware Assembly & Optical Setup: Uses an indirect ophthalmoscopy setup featuring a 20D condensing lens paired with coaxial illumination, housed in custom 3D-printed attachment adapters (including oDocs visoScope designs) to convert standard smartphone camera modules into functional fundus cameras.

Image Pre-processing Pipeline: Applies image quality filters, Contrast Limited Adaptive Histogram Equalization (CLAHE), and specialized vessel enhancement algorithms to normalize smartphone-captured fundus frames and highlight microvascular structures.

Software Integration: This Oculomics hardware is paired with Oculomics software, which integrates a trained machine learning model with a mobile app.


This Oculomics hardware is paired with Oculomics software, which integrates a trained machine learning model with a mobile app. 

Design Purpose/ Ideas:
                            
The reason for the design was to current a simple, low cost device that anyone could build and could be used straight from the packaging or from the 3D printer. The device is also a single, non-medical professional to be able to detect early signs of stroke or CVD. The device is paired with the mobile app and can be done with 1 hand.


