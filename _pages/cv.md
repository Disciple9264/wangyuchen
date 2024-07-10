---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

CURRICULUM VITAE
======
  Name: Yuchen Wang (Ph.D.)
  
  Affiliation: Department of Electronic & Electrical Engineering, University of Bath
  
  E-mail: disciple9264@hotmail.com

I. Brief Introduction
======
Yuchen Wang received the B.Sc. degree and Ph.D. degree from the School of Electrical Engineering, Southeast University, Nanjing, China, in 2017 and 2023, respectively, supervised by Prof. Wei Hua.

His research interest is design and integration of embedded magnetic encoder (EME) and PMSM, including design of EME, design of electric motor drive system, multi-objective optimization for integration system, and conditioning monitoring of PMSM.

He is the main participant of several national and provincial projects, including the National Key Research and Development Program, the National Science Fund for Distinguished Young Fund, the National Natural Science Fund, and the Aviation Industry Pre-research Project. By 	Jul. 2024, he has published 7 journal papers (JCR Q1) as principle author, 4 journal papers (JCR Q1) as main contributor and got 4 authorized patents. He is also the reviewer of many journals, including IEEE Transactions on Industrial Informatics, IEEE Transactions on Industrial Electronics, IEEE Transactions on Power Electronics.


II. Education
======
* Ph.D in Electrical Engineering, Southeast University, 2020-2023
* M.S. in Electrical Engineering, Southeast University, 2017-2020
* B.S. in Electrical Engineering, Southeast University, 2013-2017

Work experience
======
* Research Associate in Electrical Engineering, University of Bath, Apr. 2024-Now
  
III. Research Interests
======
The research interests of Dr. Wang are the design and application of embedded magnetic encoder. The embedded magnetic encoder (EME) is a novel sensor which achieves highly compact detection of rotor position by inserting several linear Hall sensors in PMSM’s cavity. Given that the EME locates inside the PMSM and provides rotor information for controller, the EME is actually complicated and coupled system including magnetic design, control algorithm, electromagnetic interference, thermal effect, rotor eccentricity, demagnetization, and so on. With the help of EME, the PMSM can save the volume for installing conventional mechanical rotary device and release the complexity of structure design. Invoked by EME system, the design of overall motor drive system should comprehensive consider electric machine, rotary device, and controller, which is also the trend of both academic research and industrial applications. The future research covers the area of:
* Application of EME in novel machine topologies and ultra-high speed machine
* Advanced control based on in EME system
* Health monitoring and diagnostics of electric machine based on EME
* The crucial problem in integration electrical machine drive system (EMI/Thermal problems)


IV. Skill
======
* Magnetic analysis and optimization:
1. Analyzing the magnetic characteristics of electric machine in ANSYS/Maxwell;
2. Kriging surrogate model assisted multi-objective optimization based on Python.
* Design of drive controller:
1. Design the high/Low voltage PMSM drive system in Altium Designer;
2. Design the low-cost BLDC controller for electric forklift.
* Electrical machine control:
1. Algorithm developing in STM8, STM32, and DSP (Texas Instruments) platform;
2. FOC for PMSM, Six step control for BLDC.

V. Publications
======

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
VI. Academic Work
======
* Reviewer - IEEE Transactions on Industrial Informatics
* Reviewer - IEEE Transactions on Industrial Electronics
* Reviewer - IEEE Transactions on Power Electronics
* Reviewer - IEEE Sensors Letters
* Reviewer - Sensors and Actuators: A. Physical 
* Reviewer - Alexandria Engineering Journal
  
VII. Participated Grants
======
**The National Key Research and Development Program (2021.12~2024.11)**

"Key technologies and applications of high-performance in-wheel motor and modular assembly integration"
1. Write the application materials;
2. Design and produce the EME system for in-wheel motor, which are tested in Xiamen Kinglong Company;
3. There is no available space for the installation of resolver in this in-wheel motor. The 600V in-wheel motor produce the power of 100kW power and the torque1265N·m with the help of EME;
4. The four-wheel independent e-vehicle equipped with above system realizes various operating modes such as in-situ turning and lateral driving.

**National Science Fund for Distinguished Young Scholars (2019.01~2023.12)**

"Research on basic theory of novel flux switching motor system for electric vehicle"
1. Design the EME system for stator-PM electric machine, of which the design principle is totally different with traditional rotor PM electric machine.
2. Propose a uniform analytical model of flux-density in eccentric machine based on the theory of magnetic field modulation.
 
**The Aviation Industry Pre-research Project (2017.01~2020.12)**

"Development of highly compact turntable electrical machine system"
1. Design and produce controller for PMSM;
2. Design and produce EME system as backup for encoder;
3. Propose the eccentricity detection method based on EME.

VIII. Oral Presentation
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

IX. Honors and Awards
======
* 2024  Outstanding graduate student of Southeast University
* 2023	National Scholarship
* 2023	NARI Scholarship
* 2023	First-class academic scholarship of Southeast University
* 2023	Silver Medal at the 48th International Exhibition of Inventions of Geneva
* 2022	Outstanding graduate cadres of Southeast University
* 2017	The second prize at National Post-Graduate Mathematic Contest in Modeling
