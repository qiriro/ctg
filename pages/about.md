---
title: About
description: 
background: 
permalink: /about/
---

## BACKGROUND

Intrapartum-related disorders are responsible for 25% of the world's neonatal death and contribute to almost 50% of the 2.6 million third trimester stillbirths and are a significant burden to healthcare in low-income countries.  In 2010, for example, 1.15 million infants developed neonatal brain damage due to some intrapartum hypoxic events, 90% of these complications taking place in low and middle-income countries.

WHO's recent report on trends in maternal mortality from 2000 to 2017 praised Rwanda for being one of the few developing countries that achieved the highest average annual rate of reduction (ARR) in global maternal mortality ratio (with ARR > 7%). While Rwanda has achieved a remarkable decline in its maternal mortality, a great deal of work remains to be done to meet the Government of Rwanda (GoR)'s target. For example, the GoR's Vision 2050 has the ambition to decrease the maternal mortality rate by 75% and infant mortality rate by 24% by the year 2035. Unfortunately, as echoed by UNICEF's recent report on Rwanda's health budget—due to a shortage of qualified obstetrics and gynecology doctors— such ambitious goals are unlikely to materialize unless the GoR introduces innovations to reduce maternal mortality in the medium and long term. For instance, as of January 2020, Rwanda has a population of around 13 million but only 57 obstetrics and gynecology doctors work in the public hospitals in Rwanda.

## OUR SOLUTION

In all public hospitals in Rwanda, intrapartum cardiotocography (CTG) is used during childbirth to monitor the heart rate of the baby and the mother's uterine contractions. A CTG graph can help to evaluate the baby's well-being and identify babies at risk of hypoxia during labor and to decide whether the baby will be delivered by instrumental vaginal birth or by cesarean section.

During childbirth, obstetricians visually examine the morphological variations in CTG traces to identify the health status of a fetus. This approach, however, is unreliable and has poor reproducibility because the interpretation is often subjective and varies from one obstetrician to another. Moreover, the fetus's heart rate variability is influenced by the brain's parasympathetic and sympathetic activities and its patterns are affected by several other stimuli such as uterine contractions. Consequently, intrapartum fetal monitoring must also consider a physiological viewpoint instead of just focusing on the morphological appearance of the fetal heart rate. CTG traces contain complex information about the baby's condition and identification of the baby's hypoxemia (e.g., low blood oxygen). Thus, proper CTG interpretation requires the medical personnel to have a good understanding of the physiology of the fetus during childbirth and other compensatory mechanisms of the fetus. Finally, several human factors such as distraction, tiredness, pressure, and stress complicate CTG interpretation and may lead to fatal outcomes. For example, the Royal College of Obstetricians and Gynecologists' report on perinatal mortality in the UK shows that 66% of stillbirths, neonatal deaths, and brain injuries of term babies in labor in 2017 are due to errors of interpretation of CTG and failure to act upon suspicious or pathological CTG.

In the context of Rwanda, due to a severe lack of qualified obstetricians and the large number of deliveries each obstetrician is expected to perform daily, the available CTG machines are often not put to good use and their outputs are poorly interpreted. When CTG interpretation is ambiguous, out of an abundance of caution, obstetricians often resort to unnecessary and costly emergency cesarean sections instead of waiting for a natural vaginal birth.

## HIGH-LEVEL OVERVIEW OF THE DEVICE

The development of the device and the clinical trial are fully sponsored by Spiker Ltd, a Japanese healthcare company. 

The device continuously monitors a CTG during childbirth and automatically provides suitable diagnoses and alerts to the medical personnel. In particular, it allows e.g., a nurse to monitor several patients at the same time and can give alerts to remote specialized gynecologists.

<figure class="figure">
  <img src="{{site.url}}{{ site.baseurl}}/static_files/images/alert-screenshoot.png" class="figure-img img-fluid rounded" alt="A generic square placeholder image with rounded corners in a figure.">
  <figcaption class="figure-caption">SCREENSHOT OF THE DEVICE IN ACTION <br> A baby’s heartbeats are monitored using a CTG machine. The resulting CTG traces are sent to an AI engine. The AI engine uses the International Federation of Gynecology and Obstetrics (FIGO)’s guidelines on intrapartum fetal monitoring and utilizes large datasets of fetal heart rate (FHR) and uterine contraction (UC) features on cardiotocography classified by expert obstetricians to detect abnormal or suspicious fetus and give evidence-based recommendations on the best course of action. </figcaption>
</figure>

The device is pluggable into an existing CTG and uses the International Federation Of Gynecology And Obstetrics (FIGO)'s consensus guidelines on intrapartum fetal monitoring to provide guidance on CTG interpretation. It continuously monitors a CTG trace, records the fetal heart rate (FHR) variability, and extracts several attributes of the FHR such as the baseline heart rate, acceleration and deceleration, uterine contractions, and their timing. 

The device uses advanced signal processing and segmentation of the fetal heart rate feature and assesses their correlation with the uterine contradiction in order to help the medical personnel quickly assess and diagnose issues due to fetal distress. The CDS will analyze the raw CTG traces and compute several parameters (e.g., acceleration and deceleration due to the uterine contraction or movements). These characteristics allow to perform common human CTG analysis (e.g., FHR baseline recognition, FHR variability, and acceleration rate). These features will be integrated into an Artificial Intelligence (AI) model to replicate existing guidelines (e.g., the International Federation of Gynecology and Obstetrics) on CTG interpretation. Moreover, the CDS system also uses advanced machine learning logarithms to detect subtle physiological changes in a baby’s heartbeat that a visual inspection cannot detect. Finally, it will alert and provide evidence-based recommendations when abnormal cases are detected.