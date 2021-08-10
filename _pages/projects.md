---
title: 'Projects'
layout: single
permalink: /projects/
author_profile: true
---

- **SWARNA: Software-based remote network attestation**

	SWARNA remotely verifies the integrity of the firmware running on tiny embedded IoT devices. SWARNA builds a deterministic communication channel using IEEE 802.15.4 TSCH to provide strict time guarantees across a multihop wireless sensor network. Algorithms are proposed to attest a remote IoT network and the evaluation of these algorithms were performed on a real IoT testbed (FIT-LAB IoT testbed). 
	
	Paper: [Click here](https://ieeexplore.ieee.org/document/9425435) Source code: [Click here](https://github.com/seemakumar8/iotlab-contiki-swarna)

- **Program Anomaly Detection**

	In this project a neural network based model was designed to capture the behaviour of an embedded program. The trained lightweight neural network model is loaded on to the embedded device. At runtime, the execution of the program is monitored and checked against the model to detect behaviour anomalies. The project also includes optimizations to minimise the effect of runtime anomaly detection on the application's performance. We were able to successfully detect attacks that affect the control flow of a program. The paper from the project is currently under review. 

- **Data-oriented attack on embedded devices**

	This project uses hardware based approach (uses ARM coreSight debug architecture) to collect the traces during program execution and detect various control and data oriented attacks. The intrumentation overhead is almost neglible compared to related works. The project is currently work in progress. 
