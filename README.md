# ND-DeeprPPG
Implementation details of ND-DeeprPPG

For face videos in experiments, middle face, lower face, and forehead regiosn are defined with landmarks as follows:
landmark index:
<img width="400" alt="landmark_scheme_68" src="https://user-images.githubusercontent.com/3102772/127600942-0eac28f7-f371-48f2-9b85-520d7ef56b97.png">

Local regions defined by landmarks:

Middle face: [1 2 3 4 30 12 13 14 15, 45 46 47 42 28 39 40 41 36]

Lower face: [3:13 35 31]

Forehead: [18:25]
  The bottom edge (W) of forehead region is the eight landmarks on eyebrow. The height (H) is determined by the distance between landmark 27 and 30

Background regions:[0 2 16 14]
  The size (H=W) of background regions is determined by the distance between landmark 19 and 24
  

