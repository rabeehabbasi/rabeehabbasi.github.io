---
title: "Impact of Feature Selection on Non-technical Loss Detection"
collection: publications
permalink: /publication/2020-03-01-Impact-of-Feature-Selection-on-Non-technical-Loss-Detection
date: 2020-03-01
venue: 'In the proceedings of 6th Conference on Data Science and Machine Learning Applications (CDMA)'
paperurl: 'https://ieeexplore.ieee.org/document/9044241'
citation: ' K. Ghori,  R. Abbasi,  M. Awais,  M. Imran,  A. Ullah,  L. Szathmary, &quot;Impact of Feature Selection on Non-technical Loss Detection.&quot; In the proceedings of 6th Conference on Data Science and Machine Learning Applications (CDMA), 2020.'
---

[Access paper here](https://ieeexplore.ieee.org/document/9044241){:target="_blank"}

Over the years, many countries have faced huge financial deficits due to Non-Technical Loss (NTL) in power sector. There are many ways of attempting to illegal use of electricity like by-passing and reversing meters. There have been many attempts to bring down NTL using manual and automated techniques. Manual NTL detection is not proving fruitful as it incurs heavy costs and has a low hit ratio. Due to the shortcoming of manual NTL detection, automated detection of NTL using machine learning classifiers is gaining attention in the research community. The datasets containing NTL belong to the class imbalance domain where regular consumers (negative class) out weight the representation of irregular consumers (positive class). To identify the right number of representative records, many techniques are proposed but selecting the right features in deciding NTL is equally an important task where not much has been contributed to the literature. In this paper, we propose the Incremental Feature Selection (IFS) algorithm which first uses feature importance to identify the most relevant features for NTL detection and then these features are used to test three classifiers namely CatBoost, Decision Tree (DT) Classifier and K-Nearest Neighbors (KNN) for NTL detection. This way, we have not only identified the most relevant features for NTL detection in a real dataset but also have brought down the overall computation time of the classifiers. Moreover, our proposed framework is tested on three performance evaluation metrics used in imbalance domain. The results show that using the most relevant features identified by the IFS algorithm, the three classifiers have the same or slightly better efficiency as compared to using all features.
