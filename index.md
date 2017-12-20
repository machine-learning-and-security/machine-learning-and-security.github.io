---
layout: page
title:  Machine Learning and Computer Security Workshop
---

# Overview

While traditional computer security relies on well-defined
attack models and proofs of security, a science of security
for machine learning systems has proven more elusive. This
is due to a number of obstacles, including (1) the highly
varied angles of attack against ML systems, (2) the lack of
a clearly defined attack surface (because the source of the
data analyzed by ML systems is not easily traced), and (3)
the lack of clear formal definitions of security that are
appropriate for ML systems. At the same time, security of
ML systems is of great import due the recent trend of using
ML systems as a line of defense against malicious behavior
(e.g., network intrusion, malware, and ransomware), as well
as the prevalence of ML systems as parts of sensitive and
valuable software systems (e.g. sentiment analyzers for
predicting stock prices). This workshop will bring together
experts from the computer security and machine learning
communities in an attempt to highlight recent work in this
area, as well as to clarify the foundations of secure ML and
chart out important directions for future work and
cross-community collaborations.

# Room

Shoreline room in Hyatt Regency Long Beach Hotel

# Invited Speakers

<div class="instructors">
     <div class="instructor">
       <a href="https://www.cs.purdue.edu/homes/alanqi/">
         <div class="instructorphoto"><img src="assets/people/Yuan_Qi.jpg"/></div>
         <div>Alan Qi</div>
         <div>Ant Financial</div>
       </a>
     </div>
     <div class="instructor">
       <a href="http://www.allandafoe.com/">
         <div class="instructorphoto"><img src="assets/people/dafoe.jpg"/></div>
         <div>Allan Dafoe</div>
         <div>Yale University</div>
       </a>
     </div>
     <div class="instructor">
       <a href="http://theory.stanford.edu/~barrett/">
         <div class="instructorphoto"><img src="assets/people/ClarkBarrett.jpg"/></div>
         <div>Clark Barrett</div>
         <div>Stanford University</div>
       </a>
     </div>
</div>

<div class="instructors">
     <div class="instructor">
       <a href="https://www.microsoft.com/en-us/research/people/donaldbr/">
         <div class="instructorphoto"><img src="assets/people/onstage.jpg"/></div>
         <div>Donald Brinkman</div>
         <div>Microsoft Research</div>
       </a>
     </div>
     <div class="instructor">
       <a href="https://research.google.com/pubs/105214.html">
         <div class="instructorphoto"><img src="assets/people/iangoodfellow.jpg"/></div>
         <div>Ian Goodfellow</div>
         <div>Google Brain</div>
       </a>
     </div>
     <div class="instructor">
       <a href="http://mrtz.org/">
         <div class="instructorphoto"><img src="assets/people/mhardt.jpg"/></div>
         <div>Moritz Hardt</div>
         <div>UC Berkeley</div>
       </a>
     </div>
</div>


# Contributing your talks

The [Call for Papers](cfp.md) is available.

# Schedule

9:00 - Opening Remarks

**Session 1: Secure Machine Learning in Practice**

Session Chair: Chang Liu

9:15 - Invited Talk #1: *AI Applications in Security at Ant Financial* by [Alan Qi](https://www.cs.purdue.edu/homes/alanqi/)

9:45 - Contributed Talk #1: *A Word Graph Approach for Dictionary Detection and Extraction in DGA Domain Names* by Mayana Pereira, Shaun Coleman, Martine De Cock, Bin Yu and Anderson Nascimento

10:00 - Contributed Talk #2: *[Practical Machine Learning for Cloud Intrusion Detection](papers/mlsec17_paper_3.pdf)* by Ram Shankar Siva Kumar, Andrew Wicker and Matt Swann

10:15 - Poster Spotlights #1

* *Verifying Properties of Binarized Deep Neural Networks* by Nina Narodytska

* *Cascade Adversarial Machine Learning Regularized with a Unified Embedding* by Taesik Na

* *ZOO: Zeroth Order Optimization Based Black-box Attacks to Deep Neural Networks without Training Substitute Models* by Huan Zhang

* *DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning* by Min Du

* *Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks* by Yanjun Qi

* *A Rotation and a Translation Suffice: Fooling CNNs with Simple Transformations* by Dimitris Tsipras

* *A Neural-Symbolic Approach to Design of CAPTCHA* by Qiuyuan Huang

10:30 - Coffee Break

**Session 2: Machine Learning, Cybersecurity, and Society**

Session Chair: Jacob Steinhardt

11:00 - Invited Talk #2: *International Security and the AI Revolution by* by [Allan Dafoe](http://www.allandafoe.com)  [[Slides]](Allan-Dafoe-NIPS-s.pdf)

11:30 - Contributed Talk #3 (<span style="color:red">Best Attack Paper</span>): *[BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](papers/mlsec17_paper_51.pdf)* by Tianyu Gu, Brendan Dolan-Gavitt and Siddharth Garg 

11:45 - Poster Spotlights #2

* *Interpretation of Neural Networks is Fragile* by Amirata Ghorbani 

* *Thermometer Encoding: One Hot way to resist Adversarial Examples* by Aurko Roy 

* *Adversarial Patch* by Justin Gilmer

* *Distributionally Robust Deep Learning as a Generalization of Adversarial Training* by Matthew Staib

* *Certifiable Distributional Robustness with Principled Adversarial Training* by Aman Sinha

* *Formal Guarantees on the Robustness of a Classifier against Adversarial Manipulation* by Matthias Hein

* *Query-limited Black-box Attacks to Classifiers* by Suya FNU

* *JPEG-resistant Adversarial Images* by Richard Shin

12:00 - Lunch

**Session 3: Security Vulnerabilities of Machine Learning Systems**

Session Chair: Nicolas Papernot

1:30 - Invited Talk #4: *Defending Against Adversarial Examples* by [Ian Goodfellow](https://research.google.com/pubs/105214.html)

2:00 - Contributed Talk #4 (<span style="color:red">Best Defense Paper</span>): *[Provable defenses against adversarial examples via the convex outer adversarial polytope](papers/mlsec17_paper_42.pdf)* by	J. Zico Kolter and Eric Wong

2:15 - Invited Talk #5: *Games People Play (With Bots)* by [Donald Brinkman](https://www.microsoft.com/en-us/research/people/donaldbr/)

2:45 - Contributed Demo: *[Synthesizing Robust Adversarial Examples](papers/mlsec17_paper_50.pdf)* by	Anish Athalye, Logan Engstrom, Andrew Ilyas and Kevin Kwok

3:00 - Poster Session/Break

**Session 4: Formal Definitions and Formal Verification**

Session Chair: Bo Li

3:45 - Invited Talk #5: *Privacy-preserving Mechanisms for Correlated Data* by 
[Kamalika Chaudhuri](http://cseweb.ucsd.edu/~kamalika/)

4:10 - Invited Talk #6: *Towards Verification of Deep Neural Networks* by [Clark Barrett](http://theory.stanford.edu/~barrett/) [[Slides]](Clark_Barrett_NIPSWorkshop.pptx)

4:40 - Invited Talk #7: *Adversarially Robust Optimization and Generalization* by [Ludwig Schmidt](http://people.csail.mit.edu/ludwigs/) [[Slides]](slides/Ludwig_Schmidt_security.pdf)

# List of contributed posters

* *[DeepXplore: Automated Whitebox Testing of Deep Learning Systems](papers/mlsec17_paper_1.pdf)* by Kexin Pei, Yinzhi Cao, Junfeng Yang and Suman Jana

* *[Verifying Properties of Binarized Deep Neural Networks](papers/mlsec17_paper_9.pdf)* by Nina Narodytska, Shiva Kasiviswanathan, Leonid Ryzhyk, Mooly Sagiv and Toby Walsh

* *[Cascade Adversarial Machine Learning Regularized with a Unified Embedding](papers/mlsec17_paper_12.pdf)* by Taesik Na, Jong Hwan Ko and Saibal Mukhopadhyay

* *[Interpretation of Neural Networks is Fragile](papers/mlsec17_paper_18.pdf)* by Amirata Ghorbani, Abubaka Abid and James Zou

* *[PixelDefend: Leveraging Generative Models to Understand and Defend against Adversarial Examples](papers/mlsec17_paper_20.pdf)* by Yang Song, Taesup Kim, Sebastian Nowozin, Stefano Ermon and Nate Kushman

* *[Thermometer Encoding: One Hot way to resist Adversarial Examples](papers/mlsec17_paper_26.pdf)* by Jacob Buckman, Aurko Roy, Colin Raffel and Ian Goodfellow

* *[Adversarial Patch](papers/mlsec17_paper_27.pdf)* by Tom B Brown, Dandelion Mané, Aurko Roy, Martin Abadi and Justin Gilmer

* *[Distributionally Robust Deep Learning as a Generalization of Adversarial Training](papers/mlsec17_paper_30.pdf)* by Matthew Staib and Stefanie Jegelka

* *[Certifiable Distributional Robustness with Principled Adversarial Training](papers/mlsec17_paper_34.pdf)* by Aman Sinha, Hongseok Namkoong and John Duchi

* *[Formal Guarantees on the Robustness of a Classifier against Adversarial Manipulation](papers/mlsec17_paper_40.pdf)* by Matthias Hein and Maksym Andriushchenko

* *[Query-limited Black-box Attacks to Classifiers](papers/mlsec17_paper_46.pdf)* by Fnu Suya, Yuan Tian, David Evans and Paolo Papotti

* *[ZOO: Zeroth Order Optimization Based Black-box Attacks to Deep Neural Networks without Training Substitute Models](papers/mlsec17_paper_47.pdf)* by Pin-Yu Chen, Huan Zhang, Yash Sharma, Jinfeng Yi and Cho-Jui Hsieh

* *[DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](papers/mlsec17_paper_49.pdf)* by Min Du, Feifei Li, Guineng Zheng and Vivek Srikumar

* *[Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks](papers/mlsec17_paper_52.pdf)* by Weilin Xu, David Evans and Yanjun Qi

* *[JPEG-resistant Adversarial Images](papers/mlsec17_paper_54.pdf)* by Richard Shin and Dawn Song

* *[A Rotation and a Translation Suffice: Fooling CNNs with Simple Transformations](papers/mlsec17_paper_55.pdf)* by Logan Engstrom, Ludwig Schmidt, Dimitris Tsipras and Aleksander Madry

* *[A Neural-Symbolic Approach to Design of CAPTCHA](papers/mlsec17_paper_56.pdf)* by Qiuyuan Huang, Paul Smolensky, Xiaodong He, Li Deng and Dapeng Wu

# Organizer


<div class="instructors">
     <div class="organizer">
       <a href="mailto:jacob.steinhardt@gmail.com">
         <div class="organizerphoto"><img src="assets/people/jacob.png"/></div>
         <div>Jacob Steinhardt</div>
       </a>
     </div>
     <div class="organizer">
       <a href="mailto:crystalboli@berkeley.edu">
         <div class="organizerphoto"><img src="assets/people/boli.jpg"/></div>
         <div>Bo Li</div>
       </a>
     </div>
     <div class="organizer">
       <a href="mailto:liuchang@eecs.berkeley.edu">
         <div class="organizerphoto1"><img src="assets/people/chang.jpg"/></div>
         <div>Chang Liu</div>
       </a>
     </div>
     <div class="organizer">
       <a href="mailto:ngp5056@cse.psu.edu">
         <div class="organizerphoto"><img src="assets/people/ngp.png"/></div>
         <div>Nicolas Papernot</div>
       </a>
     </div>
     <div class="organizer">
       <a href="mailto:pliang@stanford.edu">
         <div class="organizerphoto"><img src="assets/people/percy.jpeg"/></div>
         <div>Percy Liang</div>
       </a>
     </div>
     <div class="organizer">
       <a href="mailto:dawnsong@cs.berkeley.edu">
         <div class="organizerphoto"><img src="assets/people/dawnsong.jpg"/></div>
         <div>Dawn Song</div>
       </a>
     </div>
</div>
