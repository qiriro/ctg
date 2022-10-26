---
title: our solution
description: 
background: 
toc: true
permalink: /about/
---

## Background & Rationale 

Maternal and neonatal health care was a key component of the United Nations (UN)’s Millennium
Development Goals (MDGs) with an objective to reduce maternal mortality ratio (MMR) by 75% between 1990 and 2015. Although the World Health Organization (WHO) estimates that the MMR decreased by 38% worldwide between 2000 and 2017, this improvement is unequally distributed. WHO admits that up to 94% of all maternal deaths occurred in lower and middle-income countries—with Sub-Saharan Africa accounting for the largest MMR[^1]. For example, a comprehensive review on maternal mortality in developing countries estimates that around 99% of
all maternal-related death occurs in developing countries and that Sub-Saharan Africa alone accounts for 50% of all these maternal deaths, with 70 to 80% of the maternal deaths due to direct obstetric causes[^2].

The recently introduced Sustainable Development Goals (SDGs) provide a framework for rectifying
this imbalance. SDGs aspire to provide fair access to maternal healthcare for all by reducing the global MMR to less than 70 per 100,000 live births by 2030 [^3]. Nonetheless, attaining this milestone will be challenging to most developing countries. These challenges include, among other things, a severe shortage of proficient healthcare providers and insufficient training, especially for mid and lower-level providers. Africa, for example, has only 3% of the world’s health care workers; yet, bears 25% of the global burden of disease [^4]. Without skilled medical personnel, it is virtually impossible to perform WHO’s recommended interventions for improving maternal health [^5].

WHO recognizes that Artificial Intelligence (AI) has an enormous potential to solve several healthcare challenges [^6]. For example, deep learning (DL) algorithms achieve human-like accuracy in some diagnostic [^7]. Nevertheless, while AI is often utilized to support healthcare in several developed countries, its usage in developing countries remains at the embryonic stage [^9],[^10]. Moreover, because most AI-based health applications are conceived for rich countries, they are not well-suited and too ambitious to serve their purpose in low-income countries [^11]. It is, however, important to note that AI-assisted medical techniques could help improve medical outcomes in resource-poor settings [^12]. For instance, in some cases, AI-assisted systems can serve in place of human experts if they are not available—which is often the case in resource-poor hospitals—and provide evidence-based epidemiological recommendations [^10]. These intelligent systems would, thus, allow
non-specialized healthcare personnel to perform specialized tasks such as diagnosis, prognosis, and treatment of several diseases and only refer to specialists when necessary [^9].

## Current challenge to healthcare

WHO’s recent report on trends in maternal mortality from 2000 to 2017 [^1] praised Rwanda for being one of the few developing countries that achieved the highest average annual rate of reduction (ARR) in global maternal mortality ratio (with ARR > 7%). While Rwanda has achieved a remarkable decline in its maternal mortality, a great deal of work remains to be done to meet the GoR’s target. For example, the GoR’s Vision 2050 [^13] has the ambition to decrease maternal mortality rate by 75% and infant mortality rate by 24% by the year 2035. Unfortunately, as echoed by UNICEF’s recent report on Rwanda’s health budget [^14]⁠—due to a shortage of qualified obstetrics and gynecology doctors [^15]⁠—such ambitious goals are unlikely to materialize unless the GoR introduces new innovations to reduce maternal mortality in the medium and long term [^14].

Moreover, as shown by the GoR’s Health Sector Strategic Plan [^16], this success came at an exorbitant financial burden that is not sustainable in the long run [^14]—especially because the GoR has other pressing needs. For example, in 2018/19 the GoR budgeted FRW 200.8 billion to the health sector [^16] ⁠—a nominal increase of 1.8% compared to the previous fiscal year. On top of that, as of January 2020, Rwanda possesses only 57 obstetrics and gynecology doctors working in the public sector [^15] and its healthcare system heavily relies on foreign aid. For example, in the fiscal year 2021/22, internal budget for healthcare is 43.2% of the total healthcare budget compared to the 51.4% that was previously allocated in 2020/21. At the same time, external funds and foreign aid increased from FRW 137.2 billion in 2020/21 to FRW 214.3 billion in 2021/22 [^14].

Considering that Rwanda’s population is expected to increase by more than 50% by 2035 and double
by the year 2050 [^13], one can assume that Rwanda’s maternal care will deteriorate if nothing is done to tackle this problem. As recommended by the latest Rwanda’s National Surgical, Obstetric, and Anesthesia Plan [^17], there is a need to develop sustainable and homegrown innovative technical solutions for a sustainable, equitable, and efficient health care provision in Rwanda.

## Challenge & Opportunity 

Intrapartum hypoxia (i.e., oxygen deficiency during birth)—commonly known as birth asphyxia—
emerges before, during, or after birth when a baby does not receive an adequate amount of
oxygen. Intrapartum-related disorders are responsible for 25% of the world’s neonatal death and
contribute to almost 50% of the 2.6 million third trimester stillbirths and are a significant burden to healthcare in low-income countries [^18]. In 2010, for example, 1.15 million infants developed neonatal brain damage due to some intrapartum hypoxic events, 90% of these complications taking place in low and middle-income countries [^18].

In most hospital in Rwanda, intrapartum cardiotocography (CTG) is often used during childbirth
to monitor the heart rate of the baby and the mother’s uterine contractions. A CTG graph can help to evaluate the baby’s well-being and identify babies at risk of hypoxia during labor and to decide whether the baby will be delivered by instrumental vaginal birth or by cesarean section [^19], [^20].

<figure class="figure">
  <img src="{{site.url}}{{ site.baseurl}}/static_files/images/ctg-output.jpeg" class="figure-img img-fluid rounded" alt="A generic square placeholder image with rounded corners in a figure.">
  <figcaption class="figure-caption">A typical output of a CTG machine <br> A CTG trace calculate heart rate from fetal heart motion determined by ultrasound, and uterine contractions are measured by a tocodynamometer. In this figure, (A) represents the fetal heartbeat,  the (B) indicator shows the movements felt by mother (triggered by pressing a button), (C) shows the fetal movement and (D) show the uterine contractions </figcaption>
</figure>

During childbirth, obstetricians visually examine the morphological variations in CTG traces to identify the health status of a fetus. This approach, however, is unreliable and has poor reproducibility because the interpretation is often subjective and varies from one obstetrician to another [^21], [^22]. When there is a misinterpretations, out of an abundance of caution, obstetricians often perform unnecessary operative deliveries [^19]. Moreover, the fetus’s heart rate variability is influenced by the brain’s parasympathetic and sympathetic activities [^23], [^24] and its patterns are affected by several other stimuli such as the uterine contractions [^22]. Consequently, intrapartum fetal monitoring must also consider a physiological viewpoint instead of just focusing on the morphological appearance of the fetal heart rate [^24]. CTG traces contain complex information about the baby’s condition and identification of the baby’s hypoxemia (e.g., low blood oxygen). Thus, proper CTG interpretation would require the medical personnel to have a good understanding of the physiology of the fetus during childbirth and other compensatory mechanisms of the fetus [^25]. Visually analyzing CTG
traces cannot reveal such important diagnostic information and its appropriate interpretation[^24].

Finally, several human factors [^21] such as distraction, tiredness, pressure, and stress [26] complicate CTG interpretation and may lead to fatal outcomes. For example, the Royal College of Obstetricians and Gynecologists’ report on perinatal mortality in the UK [^27] shows that 66% of stillbirths, neonatal deaths, and brain injuries of term babies in labor in 2017 are due to errors of interpretation of CTG and failure to act upon suspicious or pathological CTG. In several cases, when there is an ambiguity in CTG interpretation, obstetricians often resort to unnecessary emergency cesarean sections [^28],[^19] instead of waiting for a natural vaginal birth.

## Our solution

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

The device uses advanced signal processing and segmentation of the fetal heart rate feature and assesses their correlation with the uterine contradiction in order to help the medical personnel quickly assess and diagnose issues due to fetal distress. The CDS will analyze the raw CTG traces and compute several parameters (e.g., acceleration and deceleration due to the uterine contraction or movements). These characteristics allow to perform common human CTG analysis (e.g., FHR baseline recognition, FHR variability, and acceleration rate). These features will be integrated into an Artificial Intelligence (AI) model to replicate existing guidelines (e.g., the International Federation of Gynecology and Obstetrics) on CTG interpretation. Moreover, the CDS system also uses advanced machine learning logarithms to detect subtle physiological changes in a baby’s heartbeat that a visual inspection cannot detect. Finally, it will alert and provide evidence-based recommendations when abnormal cases are detected.


## Bibliography 

- [^1]: World Health Organization. Trends in maternal mortality 2000 to 2017⁠— estimates by WHO UNICEF, UNFPA, World Bank Group and the United Nations Population Division: executive
summary. World Health Organization, 2019 

- [^2]: Ndola Prata, Paige Passano, Amita Sreenivas, et al. “Maternal mortality in developing countries: Challenges in scaling-up priority interventions”. In:Women’s Health 6.2 (2010), pp. 311–327. issn: 17455057. 

- [^3]: United Nations. Work of the Statistical Commission pertaining to the 2030 Agenda for
Sustainable Development. Global indicator framework for the Sustainable Development
Goals and targets of the 2030 Agenda for Sustainable Development, 11371, pp. 4–25 

- [^4]: Robert Mash, Amanda Howe, Osa Olayemi, et al. Reflections on family medicine and primary
healthcare in sub-Saharan Africa. BMJ Global Health 3.Suppl 3 (May 2018), pp. 1–3. issn: 2059-7908. 

- [^5]: WHO. WHO recommended interventions for improving maternal and newborn health: integrated
management of pregnancy and childbirth. World Health Organization, 2009 

- [^6]: World Health Organization. Ethics and governance of artificial intelligence for health. World Health Organization, June 2021 

- [^7]: Eric J. Topol. High-performance medicine: the convergence of human and artificial intelligence.In: Nature Medicine 25.1 (Jan. 2019), pp. 44–56. 

-[^8]: Andre Esteva, Brett Kuprel, Roberto A. Novoa, et al. Dermatologist-level classification of skin cancer with deep neural networks. In: Nature 542.7639, pp. 115–118. issn: 0028-0836. doi: 10.1038/nature21056 

- [^9]: Ahmed Hosny and Hugo J. W. L. Aerts. Artificial intelligence for global health. In: Science 366.6468, pp. 955–956. 
aay5189 

- [^10]: Brian Wahl, Aline Cossy-Gantner, Stefan Germann, et al. Artificial intelligence (AI) and global health: how can AI contribute to health in resource-poor settings? In: BMJ Global
Health 3.4, e000798. issn: 2059-7908. 

- [^11]: Julie S. Weber and Kentaro Toyama. Remembering the past for meaningful AI-D. In: AAAI
Spring Symposium - Technical Report. Vol. SS-10-01. Palo Alto, California: Association for
the Advancement of Artificial Intelligence, 2010, pp. 97–102

- [^12]: Jonathan Guo and Bin Li. The Application of Medical Artificial Intelligence Technology
in Rural Areas of Developing Countries. In: Health Equity 2.1 (2018), pp. 174–181.

- [^13]: The Government of Rwanda. Vision 2050. Kigali: The Government of Rwanda, 2020 

- [^14]: UNICEF. Rwanda Health Budget Brief: Investing in Children’s Health in Rwanda 2021/2022. UNICEF, Nov. 2021 

- [^15]: Ministry of Health. National Strategy for Health for Health Professions Development 2020 2030.
- [^16]: Rwanda Ministry of Health. Rwanda Fourth Health Sector Strategic Plan (July 2018-June 2024). Kigali: Rwanda Ministry of Health, 2018 
- [^17]: Rwanda Ministry of Health. National Surgical, Obstetrics, and Anesthesia Plan 20182024 Rwanda Ministry of Health, 2018 
- [^18]: Anne C.C. Lee, Naoko Kozuki, Hannah Blencowe, et al. Intrapartum-related neonatal encephalopathy incidence and impairment at regional and global levels for 2010 with trends
from 1990. In: Pediatric Research 74.S1 (Dec. 2013), pp. 50–72. 
- [^19]: Zarko Alfirevic, Declan Devane, Gillian M.L. Gyte, et al. Continuous cardiotocography
(CTG) as a form of electronic fetal monitoring (EFM) for fetal assessment during labour. In:
Cochrane Database of Systematic Reviews 2017.2 (2017). 
- [^20]: Diogo Ayres-de-Campos, Catherine Y Spong, Edwin Chandraharan, et al. FIGO consensus
guidelines on intrapartum fetal monitoring: Cardiotocography. In: International Journal of
Gynecology & Obstetrics 131.1 (2015), pp. 13–24.
- [^21]: Susana Santo and Diogo Ayres-de-Campos. Human factors affecting the interpretation of
fetal heart rate tracings: an update. In: Current Opinion in Obstetrics & Gynecology 24.2
(Mar. 2012), pp. 84–88. 
- [^22]: Declan Devane and Joan Lalor. Midwives’ visual interpretation of intrapartum cardiotocographs: intra- and inter-observer agreement. In: Journal of Advanced Nursing 52.2
(Oct. 2005), pp. 133–141. 
03575.x 
- [^23]: Christopher A. Lear, Jenny A. Westgate, Michi Kasai, et al. Parasympathetic activity is the key regulator of heart rate variability between decelerations during brief repeated umbilical cord occlusions in fetal sheep. In: American Journal of Physiology-Regulatory, Integrative and Comparative Physiology 319.5 (Nov. 2020), R541–R550. 
- [^24]: C. Garabedian, J. De Jonckheere, L. Butruille, et al. Understanding fetal physiology and
second line monitoring during labor. In: Journal of Gynecology Obstetrics and Human
Reproduction 46.2 (Feb. 2017), pp. 113–117. 
- [^25]: A. Ugwumadu. Are we (mis)guided by current guidelines on intrapartum fetal heart rate
monitoring? Case for a more physiological approach to interpretation. BJOG: An International Journal of Obstetrics and Gynaecology 121.9 (2014), pp. 1063–1070. 
- [^26]: Obianuju Nzelu. Human Factors: The Dirty Dozen in CTG misinterpretation. In: Global
Journal of Reproductive Medicine 6.2 (2018). 
- [^27]: Royal College of Obstetricians and Gynaecologists. Each Baby Counts: 2020 Final Progress
Report. March. London,UK: Royal College of Obstetricians and Gynaecologists, 2021 
- [^28]: Emma R. Allanson, Robert C. Pattinson, Elizabeth A. Nathan, et al. “A before and after
study of the impact on obstetric and perinatal outcomes following the introduction of an educational package of fetal heart rate monitoring education coupled with umbilical artery
lactate sampling in a low resource setting labor ward in”. In: BMC Pregnancy and Childbirth
19.1 (2019), pp. 1–8. 