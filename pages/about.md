---
title: our solution
description: 
background: 
toc: true
permalink: /about/
---

# BACKGROUND & RATIONALE

In all public hospitals in Rwanda, intrapartum cardiotocography (CTG) is used during childbirth to monitor the heart rate of the baby and the mother's uterine contractions. A CTG graph can help to evaluate the baby's well-being and identify babies at risk of hypoxia during labor and to decide whether the baby will be delivered by instrumental vaginal birth or by cesarean section.

During childbirth, obstetricians visually examine the morphological variations in CTG traces to identify the health status of a fetus. This approach, however, is unreliable and has poor reproducibility because the interpretation is often subjective and varies from one obstetrician to another. Moreover, the fetus's heart rate variability is influenced by the brain's parasympathetic and sympathetic activities and its patterns are affected by several other stimuli such as uterine contractions. Consequently, intrapartum fetal monitoring must also consider a physiological viewpoint instead of just focusing on the morphological appearance of the fetal heart rate. CTG traces contain complex information about the baby's condition and identification of the baby's hypoxemia (e.g., low blood oxygen). Thus, proper CTG interpretation requires the medical personnel to have a good understanding of the physiology of the fetus during childbirth and other compensatory mechanisms of the fetus. Finally, several human factors such as distraction, tiredness, pressure, and stress complicate CTG interpretation and may lead to fatal outcomes. For example, the Royal College of Obstetricians and Gynecologists' report on perinatal mortality in the UK shows that 66% of stillbirths, neonatal deaths, and brain injuries of term babies in labor in 2017 are due to errors of interpretation of CTG and failure to act upon suspicious or pathological CTG.

In the context of Rwanda, due to a severe lack of qualified obstetricians and the large number of deliveries each obstetrician is expected to perform daily, the available CTG machines are often not put to good use and their outputs are poorly interpreted. When CTG interpretation is ambiguous, out of an abundance of caution, obstetricians often resort to unnecessary and costly emergency cesarean sections instead of waiting for a natural vaginal birth.

## HIGH-LEVEL OVERVIEW OF THE DEVICE

The development of the device and the clinical trial are fully sponsored by Spiker Ltd, a Japanese healthcare company. 

The device continuously monitors a CTG during childbirth and automatically provides suitable diagnoses and alerts to the medical personnel. In particular, it allows e.g., a nurse to monitor several patients at the same time and can give alerts to remote specialized gynecologists.

<figure class="figure">
  <img src="{{site.url}}{{ site.baseurl}}/static_files/images/alert-screenshoot.png" class="figure-img img-fluid rounded" alt="A generic square placeholder image with rounded corners in a figure.">
  <figcaption class="figure-caption"><b> Screenshot of the device in action</b> : A baby’s heartbeats are monitored using a CTG machine. The resulting CTG traces are sent to an AI engine. The AI engine uses the International Federation of Gynecology and Obstetrics (FIGO)’s guidelines on intrapartum fetal monitoring and utilizes large datasets of fetal heart rate (FHR) and uterine contraction (UC) features on cardiotocography classified by expert obstetricians to detect abnormal or suspicious fetus and give evidence-based recommendations on the best course of action. </figcaption>
</figure>

The device is pluggable into an existing CTG and uses the International Federation Of Gynecology And Obstetrics (FIGO)'s consensus guidelines on intrapartum fetal monitoring to provide guidance on CTG interpretation. It continuously monitors a CTG trace, records the fetal heart rate (FHR) variability, and extracts several attributes of the FHR such as the baseline heart rate, acceleration and deceleration, uterine contractions, and their timing. 

<figure class="figure">
  <img src="{{site.url}}{{ site.baseurl}}/static_files/images/system-architecture.png" 
  class="figure-img img-fluid rounded">
  <figcaption class="figure-caption">`High-level architecture of the new medical device`: The device is pluggable into an existing CTG, uses a cheap WIFI router for intranet communication (thus, no internet is required), and provides a centralized monitoring mechanism that allows a single obstetrician to monitor several mothers at the same time on a single large screen..</figcaption>
</figure>

The device uses advanced signal processing and segmentation of the fetal heart rate feature and assesses their correlation with the uterine contradiction in order to help the medical personnel quickly assess and diagnose issues due to fetal distress. The CDS will analyze the raw CTG traces and compute several parameters (e.g., acceleration and deceleration due to the uterine contraction or movements). These characteristics allow to perform common human CTG analysis (e.g., FHR baseline recognition, FHR variability, and acceleration rate). These features will be integrated into an Artificial Intelligence (AI) model to replicate existing guidelines (e.g., the International Federation of Gynecology and Obstetrics) on CTG interpretation. Moreover, the CDS system also uses advanced machine learning logarithms to detect subtle physiological changes in a baby’s heartbeat that a visual inspection cannot detect. Finally, it will alert and provide evidence-based recommendations when abnormal cases are detected.
