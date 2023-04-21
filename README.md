[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
<!--   <a href="https://geods.geography.wisc.edu/"> -->
<!--     <img src="images/geods_safegraph_nsf_logo.jpg" alt="Logo" width="400"> -->

  <h2 align="center">The Ethics of AI-generated Maps: A Study of DALL·E 2 and Implications for Cartography</h2>

  <p align="center">
      GISense Lab, Department of Geography, University of South Carolina.  
      GeoDS Lab, Department of Geography, University of Wisconsin-Madison.  
      HGIS Lab, Department of Geography, University of Washington.  
      Cartography Lab, Department of Geography, University of Wisconsin-Madison.  
    <br />
    <!--<a href="https://geods.geography.wisc.edu/covid-19-physical-distancing">Website</a>
    ·
    <a href="http://geods.geography.wisc.edu/covid19/King_WA.html">View Demo</a>-->
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Citation](#citation)
* [About the Project](#about-the-project)
* [Dataset Structure](#dataset-structure)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


<!-- Citation -->
## Citation
If you use this dataset in your research or applications, please cite this source:


Kang, Y., Zhang, Q., Roth, R. The Ethics of AI-generated Maps: A Study of DALL·E 2 and Implications for Cartography. arxiv (2023). <!--[https://www.nature.com/articles/s41597-020-00734-5](https://rdcu.be/cd2Fd)-->
    

```
@article{kang2023ethics,
  title     = {The Ethics of AI-generated Maps: A Study of DALL·E 2 and Implications for Cartography},
  author    = {Kang, Yuhao and Zhang, Qianheng and Roth, Robert},
  year = {2023}
}
```

## About The Project
The rapid advancement of artificial intelligence (AI) such as the emergence of large language models including ChatGPT and DALL·E 2 has brought both opportunities for improving productivity and raised ethical concerns. This paper investigates the ethics of using artificial intelligence (AI) in cartography, with a particular focus on the generation of maps using DALL·E 2. To accomplish this, we first create an open-sourced dataset that includes synthetic (AI-generated) and real-world (human-designed) maps at multiple scales with a variety settings. We subsequently examine four potential ethical concerns that may arise from the characteristics of DALL·E 2 generated maps, namely inaccuracies, misleading information, unanticipated features, and irreproducibility. We then develop a deep learning-based ethical examination system that identifies those AI-generated maps. Our research emphasizes the importance of ethical considerations in the development and use of AI techniques in cartography, contributing to the growing body of work on trustworthy maps. We aim to raise public awareness of the potential risks associated with AI-generated maps and support the development of ethical guidelines for their future use.

##Dataset-Structure

```
/data
├── continent/
│   ├── Africa_1.jpg
│   ├── Africa_1.jpg
│   └── ...
├── country/
│   ├── Afghanistan_1.jpg
│   ├── Afghanistan_2.jpg
│   └── ...
└── state/
    ├── Alabama_1.jpg
    ├── Alabama_2.jpg
    └── ...
metadata.csv
```
<!-- CONTACT -->
## Contact

Yuhao Kang - [@YuhaoKang](https://twitter.com/YuhaoKang) - yuhaokang at sc.edu  
Qianheng Zhang - [@YuhaoKang](https://twitter.com/YuhaoKang) - yuhaokang at sc.edu  

Project Link: [https://github.com/GISense/DALL-E2-Cartography-Ethics](https://github.com/GISense/DALL-E2-Cartography-Ethics) 


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GeoDS Lab](https://geods.geography.wisc.edu/)


<!-- MARKDOWN LINKS & IMAGES -->
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/GeoDS/COVID19USFlows/blob/master/LICENSE.txt
