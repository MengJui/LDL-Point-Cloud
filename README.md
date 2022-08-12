# LDL Point Cloud
![logo](https://user-images.githubusercontent.com/82630423/158313826-f1db3e85-b836-4aa8-a909-75112c4bf65f.jpg)

Lidar (light detection and ranging) is an optical remote-sensing technique that uses laser light to densely sample the surface of the object, producing highly accurate x,y,z measurements. 

In our point cloud database, the data format is PCD file. Each point cloud contains a total of 10,000 points, including x, y and z coordinate data, and all contain corresponding label data.

### [3D Object (rabbit & dog)](https://github.com/MengJui/LDL-Point-Cloud/blob/main/Point%20cloud%20database%20-%203D%20Object.md)

### [Gesture](https://github.com/MengJui/LDL-Point-Cloud/blob/main/Point%20cloud%20database%20-%20Gesture.md)


## About Chaos Lidar 

  Conventional lidars emit repetitive pulses to measure the distance of the target based on the time-of-flight [1]. However, using pulses without any specific patterns makes these lidars vulnerable to interference and malicious jamming [2]. To mitigate these issues, chaos lidars have been proposed and studied which emit non-repetitive chaos-modulated pulses generated by laser intrinsic dynamics [3]. With their noise-like waveforms, the chaos lidars have no range ambiguity and are intrinsically resistant to interference and jamming. The proof-of-concept of chaos lidar was first studied in 2004 [3]. More recently, by utilizing a master oscillation power amplifier scheme to boost its signal-to-noise ratio and using a MEMS mirror for fast beam scanning [4,5], 3D pulsed chaos lidar system that is capable of acquiring point clouds and 3D images of the targets has been demonstrated [6,7]. Benefitted by the broad bandwidths of the chaos waveforms, it has a sub-cm precision in depth that can provide more details of the target for applications of object recognition and detection.

[1.	M. C. Amann, T. M. Bosch, M. Lescure, R. A. Myllylae, and M. Rioux, “Laser ranging: a critical review of unusual techniques for distance measurement,” Opt. Engineering, vol. 40, no. 1, pp. 10–19, 2001.](https://www.spiedigitallibrary.org/journals/optical-engineering/volume-40/issue-01/0000/Laser-ranging--a-critical-review-of-unusual-techniques-for/10.1117/1.1330700.full)

[2.	G. Kim, J. Eom, and Y. Park, “Investigation on the occurrence of mutual interference between pulsed terrestrial LIDAR scanners,” in 2015 IEEE Intelligent Vehicles Symposium (IV), 2015, pp. 437–442.](https://ieeexplore.ieee.org/abstract/document/7225724)

[3.	F. Y. Lin and J. M. Liu, “Chaotic lidar,” IEEE J. of Sel. Top. Quantum Electron., vol. 10, no. 5, pp. 991-997, 2004.](https://ieeexplore.ieee.org/abstract/document/6205601/authors#authors)

[4.	Chih-Hao Cheng, Chih-Ying Chen, Jun-Da Chen, Da-Kung Pan, Kai-Ting Ting, and F. Y. Lin, “3D pulsed chaos lidar system,” Opt. Express, vol. 26, no. 9, pp. 12230-12241, 2018.](https://opg.optica.org/oe/fulltext.cfm?uri=oe-26-9-12230&id=385964)

[5.	Jun-Da Chen, Hsin-Lin Ho, Han-Ling Tsay, You-Lin Lee, Ching-An Yang, Kuan-Wei Wu, Jia-Long Sun, Da-Jie Tsai, and F. Y. Lin, “3D chaos lidar system with a pulsed master oscillator power amplifier scheme,” Opt. Express, vol. 29, no. 17, pp. 27871-27881, 2021.](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-17-27871&id=456970)

[6.	Hsin-Lin Ho, Jun-Da Chen, Ching-An Yang, Chia-Chi Liu, Cheng-Ting Lee, Yu-Hsiang Lai, and F. Y. Lin, “High-speed 3D imaging using a chaos lidar system,” Eur. Phys. J.: Spec. Top., pp. 1-7, 2022.](https://link.springer.com/article/10.1140/epjs/s11734-021-00410-8)

[7.	Jun-Da Chen, Kuan-Wei Wu, Hsin-Lin Ho, Cheng-Ting Lee, and F. Y. Lin, “3D multi-input multi-output (MIMO) pulsed chaos lidar based on time-division multiplexing,” IEEE J. of Sel. Top. Quantum Electron., 2022. ](https://ieeexplore.ieee.org/abstract/document/9712361)





