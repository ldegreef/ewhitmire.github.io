---
abstract: |-
  Many accessibility features available on mobile platforms require applications (apps) to provide complete and accurate metadata de- scribing user interface (UI) components. Unfortunately, many apps do not provide sufficient metadata for accessibility features to work as expected. In this paper, we explore inferring accessibility meta- data for mobile apps from their pixels, as the visual interfaces often best reflect an app’s full functionality. We trained a robust, fast, memory-efficient, on-device model to detect UI elements using a dataset of 77,637 screens (from 4,068 iPhone apps) that we collected and annotated. To further improve UI detections and add semantic information, we introduced heuristics (e.g., UI grouping and ordering) and additional models (e.g., recognize UI content, state, interactivity). We built Screen Recognition to generate accessibility metadata to augment iOS VoiceOver. In a study with 9 screen reader users, we validated that our approach improves the accessibility of existing mobile apps, enabling even previously inaccessible apps to be used.
authors:
- Xiaoyi Zhang
- Lilian de Greef
- Amanda Swearngin
- Samuel White
- Kyle Murray
- Lisa Yu
- Qi Shan
- Jeffrey Nichols
- Jason Wu
- Chris Fleizach
- Aaron Everitt
- Jeffrey P. Bigham
bibtex: |-
  @inproceedings{10.1145/3411764.3445186,
    author = {Zhang, Xiaoyi and de Greef, Lilian and Swearngin, Amanda and White, Samuel and Murray, Kyle and Yu, Lisa and Shan, Qi and Nichols, Jeffrey and Wu, Jason and Fleizach, Chris and Everitt, Aaron and Bigham, Jeffrey P},
    title = {Screen Recognition: Creating Accessibility Metadata for Mobile Applications from Pixels},
    year = {2021},
    isbn = {9781450380966},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    url = {https://doi.org/10.1145/3411764.3445186},
    doi = {10.1145/3411764.3445186},
    abstract = { Many accessibility features available on mobile platforms require applications (apps) to provide complete and accurate metadata describing user interface (UI) components. Unfortunately, many apps do not provide sufficient metadata for accessibility features to work as expected. In this paper, we explore inferring accessibility metadata for mobile apps from their pixels, as the visual interfaces often best reflect an app’s full functionality. We trained a robust, fast, memory-efficient, on-device model to detect UI elements using a dataset of 77,637 screens (from 4,068 iPhone apps) that we collected and annotated. To further improve UI detections and add semantic information, we introduced heuristics (e.g., UI grouping and ordering) and additional models (e.g., recognize UI content, state, interactivity). We built Screen Recognition to generate accessibility metadata to augment iOS VoiceOver. In a study with 9 screen reader users, we validated that our approach improves the accessibility of existing mobile apps, enabling even previously inaccessible apps to be used. },
    booktitle = {Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems},
    articleno = {275},
    numpages = {15},
    keywords = {mobile accessibility, ui detection, accessibility enhancement},
    location = {Yokohama, Japan},
    series = {CHI '21}
  }
blurb: |-
  Screen Recognition applies computer vision to automatically infer accessibility metadata for mobile apps from their pixels. Work from this project was published at CHI ’21 and released as an accessibility feature in iOS for VoiceOver.
citation: |-
  Xiaoyi Zhang, Lilian de Greef, Amanda Swearngin, Samuel White, Kyle Murray, Lisa Yu, Qi Shan, Jeffrey Nichols, Jason Wu, Chris Fleizach, Aaron Everitt, and Jeffrey P Bigham. 2021. Screen Recognition: Creating Accessibility Metadata for Mobile Applications from Pixels. In <i>Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems</i> (<i>CHI '21</i>). Association for Computing Machinery, New York, NY, USA, Article 275, 1–15. DOI:https://doi.org/10.1145/3411764.3445186
conference: SIGCHI Conference on Human Factors in Computing Systems (CHI), 2021
date: 2021-05-08
image: '/img/pubs/ScreenRecognition_image.png'
location: 'Apple'
paper: /pdfs/ScreenRecognition.pdf
supplement: /pdfs/ScreenRecognition_Supplementary_Material.pdf
thumbnail: '/img/pubs/ScreenRecognition_thumbnail.jpg'
title: 'Screen Recognition: Creating Accessibility Metadata for Mobile Applications from Pixels'
video: 'https://www.youtube.com/watch?v=Z0pv0ZqFnC0'
video_embed: '<iframe width="560" height="315" src="https://www.youtube.com/embed/Z0pv0ZqFnC0" frameborder="0" allowfullscreen></iframe>'
year: 2019-2021
---