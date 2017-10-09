+++
# Date this page was created.
date = "2017-12-29"

# Project title.
title = "RECfusion"

# Project summary to display on homepage.
summary = "Automatic video curation driven by the popularity of scenes."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "P-Recfusion.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["recfusion"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/H-Recfusion.png"
caption = "Results of Cluster Tracking, the third and last kind of analysis used by RECfusion to track scenes in a video set with 4 devices, 3 main scenes, and more than 2000 frames."

+++

**Abstract:** RECfusion is a framework designed for automatic video curation driven by the popularity of the scenes acquired by multiple devices. Given a set of video streams as input, the framework can group these video streams by means of similarity and popularity, then it automatically suggests a video stream to be used as output acting like a virtual director.

**Related Publications:**

- [*RECfusion: Automatic video curation driven by visual content popularity*. In Proceedings of the 23rd ACM international conference on Multimedia (pp. 1179-1182). ACM.](http://www.recfusionproject.altervista.org/)
- {{% staticref "publication/milotta2016recfusion/" %}}*RECfusion: Automatic Scene Clustering and Tracking in Videos from Multiple Sources*. In Electronic Imaging, 2016(7), 1-6.{{% /staticref %}}
- {{% staticref "publication/battiato2017organizing/" %}}*Organizing Videos Streams for Clustering and Estimation of Popular Scense*. In Proceedings of 19th International Conference on Image Analysis and Processing (ICIAP 2017).{{% /staticref %}}

During a social event, the audience typically uses its personal devices to record video clips related to the most interesting moments of the event. As a result, several videos will be related to the same visual contents, and this redundancy can be exploited to infer the most interesting moments of the event over time, according to the people interests on the observed scenes.

Acquired scenes directly reflect the audience's response to the event. In this context the estimation of the *most popular scene* is of interest. The issue of **crowd-popularity estimation** through automatic video processing is not trivial due to the variability of the visual contents observed by multiple devices: different points of view, pose and scale of the objects, lighting conditions and occlusions. The differences between device models should be also taken into account, since they imply different characteristics of the lens, color filter arrays, resolution and so on. For instance, even using two devices with similar (or equal) sensors the colors recorded will not necessarily be the same because devices responses are processed with different non-linear transformations
	
RECfusion is thought to estimate the popularity of scenes related to **multiple video streams**. Streams are analyzed with the aim to create a continuous video flow, obtained by mixing several input channels, taking into account the most popular scenes over time to reflect the interests of the crowd. Then, clusters of different scenes are tracked over time. This allows to have not only the most popular scene at each time, but also other scenes of interest and give the possibility to introduce a scenes story log that allows the user to select the scene of interest among all the detected ones. Firstly, the system automatically processes multiple video flows from different devices to understand the most popular scenes for a group of end-users. Then, the extracted information is used to cluster devices according to observed scenes over time. In {{% staticref "publication/milotta2016recfusion/" %}}our previous work{{% /staticref %}} a thresholding method was used for the cluster tracking procedure. Then, we employed {{% staticref "publication/battiato2017organizing/" %}}a better algorithm{{% /staticref %}}, based on a voting procedure, in order to be able to generalise over different sets of video.