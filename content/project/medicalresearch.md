+++
# Date this page was created.
date = "2017-12-27"

# Project title.
title = "Medical Research"

# Project summary to display on homepage.
summary = "Data Processing and Analysis employed in Medical Research."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "P-Medical.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["medicalresearch"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/H-Medical.png"
caption = "3D-Data Processing and Analysis applied to Medical Research."

+++

**Abstract:** 3D scanners have been employed to allow doctors to get a detailed virtual model of a human body. Our main aim is to find a discriminative parametrization of female breast shape (i.e., a small set of parameters to meaningfully describe it). This kind of mathematical representation gives the possibility to easily define accurate metric for breast difference evaluation. This result is very attractive for breast surgeon, since it can be used to develop new tools to assess the symmetry after a breast reconstruction.

**Related Publications:** 

- {{% staticref "publication/gallo2016breast/" %}}*Breast Shape Parametrization Through Planar Projections*. In Proceedings of International Conference on Advanced Concepts for Intelligent Vision Systems (ACIVS 2016).{{% /staticref %}}
- {{% staticref "publication/allegra2017description/" %}}*Description of Breast Morphology through Bag of Normals Representation*. In Proceedings of 19th International Conference on Image Analysis and Processing (ICIAP 2017).{{% /staticref %}}

In the last decade, 3D scanners have been employed in architecture, engineering, biology, cultural heritage as well as diagnostic medicine and reconstruction surgery. These devices allow doctors to get a detailed virtual model of a human body. The opportunity to acquire body parts shape, including soft tissues like the female human breast, has motivated our conjunct study with medical specialists in breast reconstruction.
	
Our main aim is to find a discriminative parametrization of female breast shape (i.e., a small set of parameters to meaningfully describe it). This kind of mathematical representation gives the possibility to easily define accurate metric for breast difference evaluation. This result is very attractive for breast surgeon, since it can be used to develop new tools to assess the symmetry after a breast reconstruction. It could also be an effective strategy to create clear and well-defined breast shape categories.
	
The 3D scanner acquisition of human body parts requires a certain time and skills. Long scanning time tends to increase the patient stress as well as the amount of noise due to breath and involuntary micro-movements. Modern hand-held scanners reduce these problems by allowing low acquisition time. Furthermore they guarantee sufficiently high quality of the data. Actually, extremely high resolution and accuracy are pointless to capture general shape. Moreover, dense points clouds would affect the processing time. For these reasons we propose to perform dataset acquisition with a fast and low-cost hand-held 3D scanner: Structure Sensor.	High portability of hand-held scanners simplifies the operator job, which can easily turn around the patient.
	
Our contribution in the field of **Breast Shape Parameterization** can be summarized in the following points:

- The acquisition of 3D breast models to build a proper dataset and perform significant experiments.
- The idea to exploit 3D normals to create a compact representation of 3D breast models.
- Time and cost optimization by employing a hand-held 3D scanner.
- Gain a compact description of a 3D model, easy to be transfered through the web.