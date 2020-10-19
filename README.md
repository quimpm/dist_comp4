# Volunteer   computing   with   BOINC
## Introduction to Volunteer Computing:
Volunteer computing is a type of distributed computing in wich people donate their computers' unused resources
to a research oriented project. This, provides substantial procesing power to reserchers at minimal cost, 
wich makes research more affordable and efficient. This type of computing is made mostly using cloud 
distributed systems. In this systems a program is runing on a volunteer's computer and periodically contacts 
the research aplication to to request jobs and report results. The one in charge of the comunication between
the volunteer program and the researchers' aplication is the Middleware.    

## What is BOINC

BOINC comes from Berkeley Open Infrastructure for Network Computing and is an open-source software that acts
as a middleware system for volunteer computing and greed computing. It was originally developed to support 
the SETI@home project, which purpose was to analyze radio signals. Later it became generalized as a platform
for other distributed applications. As we will see, now the applications reach from mathematics and medicine to
climatology and astrophysics. 
BOINC has been ranked as the largest computing grid in the world. As a volunteer computing platform, the
interoperability is crucial to be able to reach all the people, it supports various operating systems, 
including Windows, MacOS, Android and Linux.

## Examples of Volunteer Compting with BOINC

* PrimeGrid : A Volunteer Cloud Computing Network dedicated to find new prime numbers.
* Minecraft@Home: A Volunteer Cloud Computing Network dedicated to understand the fundamental laws of
Minecraft to answer unanswered questions regarding the features and true limits of the game.
* NumberFields@home: is a research project that uses Internet-connected computers to do research in number
theory. 
* GPUGrid.net: is a distributed computing infrastructure devoted to biomedical research. Thanks to the 
contribution of volunteers, GPUGRID scientists can perform molecular simulations to understand the function
of proteins in health and disease.
* Einstein@Home: uses your computer's idle time to search for weak astrophysical signals from spinning 
neutron stars (often called pulsars) using data from the LIGO gravitational-wave detectors, the Arecibo 
radio telescope, and the Fermi gamma-ray satellite.
* Rosseta@Home: By running Rosetta@home on your computer you will speed up and extend our efforts to design 
new proteins and to predict their 3-dimensional shapes. Proteins are the molecular machines and building 
blocks of life. 
## Going deeper into an example
We will go deep on the minecraft example, in a case studio of finding a seed of a random generated world 
starting from an image. We will focus on a project called the PackPNG project, that tries to find a seed 
starting from a photo of a place in the random world. This project is really a huge one, not only with 
computing complexity, also about mathematics. But we will go straight to the computing part, and where 
distributed computing is applied. They ended having 2^48 seeds to check, so they thoght that runing this 
computing part in a single personal computer was imposible. In order to accelerate the computation they 
used BOINC to make a distributed volunteer computing system in wich 3500 people ended contribuing. After 
some months and the 95% of the 2^48 seeds checked, they found the seed of the world that they were 
searching.
