# Volunteer   computing   with   BOINC

**Joaquim Picó & Ian Palacín**

## Introduction to Volunteer Computing:

Volunteer computing is a type of distributed computing in wich people donate their computers' unused resources
to a research oriented project. This provides substantial processing power to researchers at minimal cost, 
wich makes research more affordable and efficient. This type of computing is made mostly using cloud 
distributed systems. In these systems a program is running on a volunteer's computer and periodically contacts 
the research application to request jobs and report results. The one in charge of the communication between
the volunteer program and the researchers' application is the Middleware.    

## Volunteer Computing Architecture
![image](architecture.png)


This picture shows the basic structure of a volunteer computing 
distributed system. We can see that on the top of the diagram we 
have the publishers/reserchers, that are the one's that need the 
computational power to perform some task. They send a fragment of 
the problem to a middle of the way server, and then the server sends 
it to a volunteer worker. When the volunteer finishes the work, it 
returns to the middle of the way server the results and then the 
server replicates this results to the publishers/researchers.

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

* **PrimeGrid**: A Volunteer Cloud Computing Network dedicated to find new prime numbers.
* **Minecraft@Home**: A Volunteer Cloud Computing Network dedicated to understand the fundamental laws of
Minecraft to answer unanswered questions regarding the features and true limits of the game.
* **NumberFields@home**: is a research project that uses Internet-connected computers to do research in number
theory. 
* **GPUGrid.net**: is a distributed computing infrastructure devoted to biomedical research. Thanks to the 
contribution of volunteers, GPUGRID scientists can perform molecular simulations to understand the function
of proteins in health and disease.
* **Einstein@Home**: uses your computer's idle time to search for weak astrophysical signals from spinning 
neutron stars (often called pulsars) using data from the LIGO gravitational-wave detectors, the Arecibo 
radio telescope, and the Fermi gamma-ray satellite.
* **Rosseta@Home**: By running Rosetta@home on your computer you will speed up and extend our efforts to design 
new proteins and to predict their 3-dimensional shapes. Proteins are the molecular machines and building 
blocks of life. 

## Going deeper into an example

Here we will go deep on the Minecraft example, in this case study the purpose was to find a game seed of
a random generated world in the search of it starting from an image. We will focus on this project, called 
the PackPNG project, that tries to find the world seed 
starting from a photo of a place in the random world. This project is really a huge one, not only with 
computing complexity, also about mathematics. But we will go straight to the computing part, and where 
distributed computing is applied. They ended having 2^48 seeds to check, so they thought that running this 
part in a single computer would be impossible. In order to accelerate the computation they 
used BOINC to make a distributed volunteer computing system in wich 3500 people ended contributing. After 
some months and the 95% of the 2^48 seeds checked, they found the seed of the world that they were 
searching. This part will be further commented as it is the most interesting for us.

## Advantages and Disadvantages
#### Advantages:
* It makes big computation problems a lot more easy to solve that by a
unic computer.
* It helps research teams that don't have the money and resources to 
get a supercomputer to make big computations.
* It's descentralized, so we don't have problems with space or 
location of big computers to make the work.
* It's so easy to help and contrivute to one of these projects, 
it can be done from our home computers.
* It has unlimited power, while more volunteers, faster is the computation.

#### Disadvantages:
* As it is computed by different volunteer computers, those 
will have a different power and performance, depending on the 
specifications of the computer and also if the volunteers are 
using it while doing the computations. This means that the 
computation work needs to have a lot of redundancy in orther 
to be able for all volunteers to help in some way. 
* Also, it can happen that in the middle of a computation work beeing
done in a volnuteer computer, the volunteer closes the conection 
with the server or turns off the 
computer. Halting or even loosing all the computation made. 
* Also it can happen that no volunteers are added to the network. 
Without volunteers, thers no computational power so it's a big 
handicap when starting a new or less known project.

## Conclusions
We ended concluding that this kind of distributed systems are
a big solution to make big computations with a very low cost.
If we talk about big networks like Roseta@home, that is based
in BOINC and it has the amount of 2,918,435 processing units, we can 
see the amount of power this kind of network can provide. And almost
with no cost, only the cost handled by every volunteer and de mantainment
of the system made by the publishers/researchers.
Even this system has his years, it still works really well, 
and with the increse of the technology in our lives comes 
implicitly comes the increase of possible processing units on a 
distributed network. 


