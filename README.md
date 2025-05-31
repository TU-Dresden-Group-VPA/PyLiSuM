# LiSuM Python Version

This tool has been used to establish the digital twin of a real-world urban intersection in Germany, as described in our paper. If you use this tool in your research paper or project, please cite us as follows:
```bibtex
@article{yourpaper2024,
  author    = {Runhao Zhou, },
  title     = {Your Paper Title},
  journal   = {Journal Name},
  year      = {2024},
  volume    = {1},
  number    = {1},
  pages     = {1--10},
  publisher = {Publisher}
}
```
The original [LiSuM](https://sumo.dlr.de/docs/Tools/LiSuM.html) was written in Java. We have reproduced it in Python, based on the following software and papers:
1. [LemgoRL](https://github.com/RL-INA/LemgoRL)
2. Barthauer, M., & Friedrich, B. (2017). Connecting microscopic traffic simulation and LISA+ external signal control. Transportation Research Procedia, 27, 420-427.
3. Barthauer, M., & Friedrich, B. (2017). External signal control: Integrating LISA+ into SUMO. SUMO 2017–Towards Simulation for Autonomous Mobility, 143.
4. Bottazzi, M., Touko Tcheumadjeu, L. C., Trumpold, J., Erdmann, J., & Oertel, R. (2017). LiSuM: design and development of a middleware to couple virtual LISA+ TLS controller and SUMO simulation. SUMO 2017–Towards Simulation for Autonomous Mobility, 31, 179-192.

## ⚠️ Important Notice: Restrictions on LISA+ Provisioning Files and OmlFgServer

Due to infrastructure security concerns, we **cannot use real intersection LISA+ provisioning files** (German: *LISA+ Versorgungsdateien*) for demonstrations.

To **protect intellectual property rights**, we are also unable to provide the OmlFgServer. However, please note that the LISA+ `OmlFgServer.jar` is required. The LISA+ `OmlFgServer.jar` is a proprietary virtual controller server for traffic signals, available for purchase from [**Schlothauer & Wauer** GmbH](https://www.schlothauer.de/en/software-lisa).

If you have difficulties configuring LISA+ SUMO configuration files, or if you are interested in how to interact with LiSuM_Python and your own signal control algorithm in SUMO simulation, we can offer limited but voluntary consulting support. **Please contact:** [secr_vpa@tu-dresden.de](mailto:secr_vpa@tu-dresden.de).

## Acknowledgement
This work is part of the [ABSOLUT II](https://absolut-project.com/) project (*Autonomous On-Demand Shuttles Providing Individual Public Transport Services for the Suburban Areasof Leipzig*), which is supported by the Federal Minitry for Economic Affairs and Energy of Germany (German: *Bundesministerium für Wirtschaft und Energie der Bundesrepublik Deutschland*).
We appreciate the consultation from Dr. Arthur Müller at Fraunhofer IOSB-INA.



