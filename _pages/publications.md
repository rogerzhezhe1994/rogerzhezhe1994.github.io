---
layout: archive
title: "Publications and Talks"
permalink: /publications/
author_profile: true
---

Selected Journal Articles (Peer-Reviewed)
=========================================
* R. Zhang, K. Zou, X. Su, Y. Duan, H. Zhou, H. Song, H. Song, A. Minoofar, N. Hu, K. Pang, R. W. Boyd, M. Tur, and A. E. Willner, “Turbulence-Resilient Differential-Phase-Shift-Keying Free-Space Optical Communications Using Automatic Multi-Mode Optoelectronic Mixing,” [Optics Communications, vol: 534, 129330, 2023](https://www.sciencedirect.com/science/article/abs/pii/S0030401823000767).
* R. Zhang, , “Turbulence-Resilient Pilot-Assisted Self-Coherent Free-Space Optical Communications Using Automatic Optoelectronic Mixing of Many Modes,” [Nature Photonics, vol: 15, no. 10, pp: 743-750, 2021](https://www.nature.com/articles/s41566-021-00877-w).
This work has also been covered by various media, including [Science Daily](https://www.sciencedaily.com/releases/2021/10/211021121055.htm) and [Phys Org](https://phys.org/news/2021-10-optical-pairing-wireless.html).
\item H. Zhou* and \textbf{R. Zhang*} et al., “Demonstration of Turbulence Resiliency in a Mode-, Polarization-, and Wavelength- Multiplexed Free-Space Optical Link Using Pilot-Assisted Optoelectronic Beam Mixing,” \href{https://ieeexplore.ieee.org/abstract/document/9695404}{\textbf{\textit{Invited paper, IEEE/Optica Journal of Lightwave Technology}}}, vol: 40, no. 3, pp: 588-596, 2022. *\textit{Contributed equally}*
\item \textbf{R. Zhang} et al., “Utilizing Adaptive Optics to Mitigate Intra-Modal-Group Power Coupling of Graded-Index Few-Mode Fiber in a 200-Gbit/s Mode-Division-Multiplexed Link,” \href{https://opg.optica.org/ol/abstract.cfm?uri=ol-45-13-3577}{\textbf{\textit{Optics Letters}}}, vol: 45, no. 12, 2020. 
\item \textbf{R. Zhang} et al., “Simultaneous Turbulence Mitigation and Channel Demultiplexing for Two 100-Gbit/s Orbital-Angular-Momentum Multiplexed Beams by Adaptive Wavefront Shaping and Diffusing,” \href{https://opg.optica.org/ol/abstract.cfm?uri=ol-45-3-702}{\textbf{\textit{Optics Letters}}}, vol: 45, pp: 702-705, 2020.
\item \textbf{R. Zhang} et al., “Coherent Optical Wireless Communication Link Employing Orbital Angular Momentum Multiplexing in a Ballistic and Diffusive Scattering Medium,” \href{https://opg.optica.org/abstract.cfm?uri=ol-44-3-691}{\textbf{\textit{Optics Letters}}}, vol: 44, pp: 691-694, 2019.
\item L. Li* and \textbf{R. Zhang*} et al., “High-Capacity Free-Space Optical Communications Between a Ground Transmitter and a Ground Receiver via a UAV Using Multiplexing of Multiple Orbital-Angular-Momentum Beams,” \href{https://www.nature.com/articles/s41598-017-17580-y}{\textbf{\textit{Scientific Reports}}}, vol: 7, no. 1, pp: 17427, 2017. *\textit{Contributed equally}*

Selected Conference Proceedings and Talks (Peer-Reviewed)
==============================================


Book Chapters
==============================================

if author.googlescholar
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
endif

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
