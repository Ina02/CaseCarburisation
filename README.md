## Project Title
Development of Case Carburization Model using Finite Element Analysis


## Introduction
Case hardening is a heat treatment process that produces a surface that is hard and resistant to wear
while maintaining strength and toughness of the core. The significant feature about carburization is
that it increases wear resistance and strength by diffusing carbon into the steel specimens surface
creating a case while retaining hardness in the core which is substantially lesser.The surface carburization followed by
quenching and low-temperature tempering provides the high hardness value on the surface,
excellent ductility and toughness of the core.Parts made from low carbon steel are often carburized to
increase both the hardness and strength of the surface, while maintaining the core in a tough and ductile condition. The
carburization and quenching processes not only aids in enhancing both surface hardness and strength but also tends
to introduce compressive residual stress in the carburized layer.
Case-hardening by carburizing is completed using three separate processes which are as follows:
1) the process of enriching the surface of a steel component with carbon (carburizing)
2) the hardening of the components (by quenching in a liquid)
3) tempering in order to reduce the brittleness.

## Analysis
The carbon potential on the surface (Cs) depends on the temperature and the pressure, it remains constant during the treatment and in the same time the carbon diffuses in the bulk. In this way the concentration profile from the surface to the bulk changes with
the treatment time. Such profile variation depends on two important factors:
(a) The carbon concentration in the austenitic phase.
(b) The percent of alloy elements that influence the carbon diffusion.
The final hardening is due to the temper quenching normally performed in an oil bath. So, the mechanical properties of the surface layers depend on their chemical composition. In particular the carbon concentration can vary the presence of martensite, residual austenite and bainite presence. The residual stresses depend also on the carbon concentration being related to the martensite formation leading to compressive stresses on the surface.


## Problem
The equations to be solved for simulation of these processes are non-linear differential equations and require the use of computationally intensive numerical techniques e.g. 3D Finite Element Modelling.Using these models for solving optimization or inverse problems, compounded by the fact that a large number of evaluations need to be carried out becomes computationally expensive.Microstructure transformation causes variations in the mechanical and physical properties, and affects the behaviour of the metal in processing and operation. Microstructure transformation prediction is one of the main challenges in modelling of heat treatment.

## Our approach
In this project, we explore the use of proven statistical techniques such as Linear Regression and machine learning techniques such as Artificial Neural Networks to create computationally inexpensive surrogate models of the carburization quenching processes to predict surface hardness.We study carburizing and quenching processes and express the surface hardness as a function of temperature, carbon potential and time in a two-stage carburization process followed by quenching process. Carbon diffusion is modeled using Fick’s law of diffusion for mass transfer to predict carbon profile inside the component while the quenching process is modeled using heat transfer and phase transformation models by employing detailed FEA based models. The output of these simulations is used for developing the surrogate models using Machine Techniques. 

With the integration of deep learning techniques, such as artificial neural networks, optimum selection of input parameters such as furnace temperature, carbon percentage of furnace atmosphere for the boost, diffusion stages for different carburizing processes can be
determined to obtain the required case depth for various applications in aerospace, automobile industries. Python libraries such as Keras and tensorflow provide various functionalities to perform such complex tasks and give us better results. The static multi layer feed forward ANN with learning rule based on the error backpropagation algorithm, with momentum and adaptive learning rate, has been applied. 

