---
layout: post
title: "Tilted Transverse Isotropy: An Early Thought"
date: 2020-04-14
---

For 4 years in the university (2015-2019), I only learned geophysics from the perspective of an **isotropic earth**.  However, I never learned, or even touched anything about **anisotropy**. This term 'anisotropy' has rung to my ears for long time, but I thought at that time I was not quite interested in it. Although I found out there has been tremendous researches on seismic anisotropy that were impactful to oil and gas exploration, anisotropy still seemed pretty abstract to me. 

In March 2020, I came across a colleague posting something interesting about anisotropy in LinkedIn. He posted about his research about wellbore stability in anisotropic formation using **Lekhnitskii-Amadei (1983)** modeling. So surprised to know he worked under **R. W. Zimmerman**, Professor of Rock Mechanics from Imperial College of London, whom I cited his epic [1986 PhD dissertation](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/JB091iB12p12765) in my Bachelor thesis. Wellbore stability! This was a topic (an important topic in drilling) that at that time I was very interested in, when I still took **Reservoir Geomechanics** course by **Prof. Mark Zoback** from Stanford University. In the course, I learnt about wellbore stability modeling in **isotropic formation**, using **Kirsch (1898) modelling**. In his research, he discovered that Kirsch was not valid in anisotropic rock. This discovery was a blow to me. This is why I started to think I need to learn **anisotropy**, because it's nearer to my field now (which is geomechanics)! 

<div>
<img src="https://user-images.githubusercontent.com/51282928/79143678-dc96a900-7de7-11ea-8d8c-20d64d8d803d.jpeg" width="600"/>
</div>

<sub>These 10-page notes on brown papers were my first encounter in anisotropy</sub><br>

At first, I read at least 5 references about anisotropy, the most influential one is from Gary Mavko's epic **The Rock Physics Handbook** that appeared to me just like an encyclopedia of rock physics, because it is so complete. I began to write down formulations on brown papers and tried to find out connections from one concept to another. I started to be interested! 

There are several types of anisotropy. The first class is **transverse isotropy**, which is classified into three types depending on the orientation of anisotropy, namely **vertical transverse isotropy** (VTI), **horizontal transverse isotropy** (HTI), and **tilted transverse isotropy** (TTI). The anisotropy orientation in VTI is perpendicular to X axis (horizontally-oriented), in HTI is perpendicular to X axis (vertically-oriented), and in TTI, the orientation makes an angle or tilt to X axis. This angle is commonly familiar to us as the **dip** of bedding plane. 

<div>
<img src="https://user-images.githubusercontent.com/51282928/79189010-cd951280-7e4a-11ea-9f1a-066d16349045.jpeg" width="400"/>
</div>

<sub>2-inch core I took from university about 3 years earlier</sub>

Suddenly I remembered that I had a core sample at home. The picture that I showed you above is the core that I obtained from my university 3 years earlier. This core has a laminated coal (the black masseral) and shale (the brown mineral) sequence. I thought this were going to be a perfect representation of a TTI-type anisotropy! 

Back to rock physics. To me, rock physics is a **study** of **simplifying a rock into a certain rock model** that treats a rock as composed of the grain/mineral and inclusion (can be either cracks, mineral inclusion, or fluid). It is a simple as that. I have read from Mavko's book about 2 anisotropy models. The first model, **crack model** has two proposed model, by Eshelby (1957) and Hudson (1980), then perfected by Cheng (1993). The second model, **Backus model**, caught my intention!

In 1962, **George Backus** published a [paper](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/JZ067i011p04427) *Long‐wave elastic anisotropy produced by horizontal layering*. In his paper, he proposed that a rock composed of intercalating lamination of different lithologies (such as sand-shale, coal-shale, etc) is anisotropic, therefore **the anisotropy parameters can be computed by averaging the individual isotropic layers**. Because the core sample that I had at home was in fact also intercalation of two different lithologies (coal-shale), therefore I thought I could compute **its anisotropy parameters** using this method. Then, I decided to do so.

I can write a stiffness of any rock given in 6x6 matrix (actually a fourth-order tensor) given as follows.

<img src="https://bit.ly/3ejUTWL" align="center" border="0" alt="C_{ij}=\begin{bmatrix} C_{11} & C_{12} & C_{13} & C_{14} & C_{15} & C_{16} \\ C_{21} & C_{22} & C_{23} & C_{24} & C_{25} & C_{26} \\ C_{31} & C_{32} & C_{33} & C_{34} & C_{35} & C_{36} \\ C_{41} & C_{42} & C_{43} & C_{44} & C_{45} & C_{46} \\ C_{51} & C_{52} & C_{53} & C_{54} & C_{55} & C_{56} \\ C_{61} & C_{62} & C_{63} & C_{64} & C_{65} & C_{66} \end{bmatrix}" width="314" height="118">

What is amazing of this matrix is that when we invert the matrix, we will get **the moduli of the rock**, namely the **Young's modulus**, **Shear modulus**, and **Poisson's ratio**! During the 4 years in the university back then, I only acknowledged that these 3 moduli is similar to all directions.

Young's modulus: <img src="https://bit.ly/34FkWmT" align="center" border="0" alt="E_x = E_y = E_z" width="104" height="21" />

Shear modulus: <img src="https://bit.ly/34ARBtR" align="center" border="0" alt="G_x = G_y = G_z" width="111" height="21" />

Poisson's ratio: <img src="https://bit.ly/2Xy4rYj" align="center" border="0" alt="\nu_x = \nu_y = \nu_z" width="106" height="18" />
