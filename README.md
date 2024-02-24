<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#Data">Data</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#Reference">Reference</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<div align="justify"> 

This repository hosts our paper titled [Automated Detection of Major Depressive Disorder with EEG Signals: A Time Series Classification Using Deep Learning](https://ieeexplore.ieee.org/document/9828387), which was published in [IEEE Access](https://ieeexplore.ieee.org/document/9828387). The research is dedicated to automating the identification of Major Depressive Disorder (MDD) utilizing EEG data and deep neural network architecture. Initially, a customized InceptionTime model is employed to identify MDD individuals based on 19-channel raw EEG signals. Subsequently, a channel-selection strategy consisting of three steps is applied to eliminate redundant channels.

The original paper on InceptionTime is also accessible [here](https://arxiv.org/pdf/1909.04939.pdf). </div>

![comgit](https://user-images.githubusercontent.com/96019816/162617323-416d4fec-b6ad-4a6e-afba-396e6b837392.jpg)

<div align="justify"> MDD is a prevalent and debilitating condition that significantly impacts functional well-being, yet its exact manifestations remain elusive. Manual detection of MDD poses challenges due to its subjective nature. While EEG signals hold promise for aiding diagnosis, there's a need for improved accuracy, clinical utility, and efficiency. This study aims to automate MDD detection using EEG data and deep neural network architecture. A customized InceptionTime model is employed initially to identify MDD individuals using 19-channel raw EEG signals. Subsequently, a channel-selection strategy is applied to eliminate redundant channels. The proposed method achieves 91.67% accuracy with the full set of channels and 87.5% after channel reduction. Findings indicate that only the first minute of EEG recording is sufficient for MDD detection, models based on EEG in eyes-closed resting-state outperform those in eyes-open conditions, and customizing the InceptionTime model can enhance its efficiency for various tasks. This approach serves as an effective, straightforward, and intelligent diagnostic tool for objectively detecting MDD, potentially aiding clinicians in diagnosis and treatment. </div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Data -->
### Data

<div align="justify"> 

The data used in this project comes from the [MDD Patients and Healthy Controls EEG Data](https://figshare.com/articles/dataset/EEG_Data_New/4244171). </div>


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

In order to apply the codes, you may need to follow the steps below:


<!-- PREREQUISITES -->
### Prerequisites

<div align="justify"> 

You will need to install the following packages present in the [requirements.txt](https://github.com/Rasoul_Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/blob/master/requirements.txt) file. </div>



<!-- USAGE EXAMPLES -->
## Usage

<div align="justify"> 

The code is divided as follows: 
* The [Inception classifier](https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/blob/414d89c2e4de0d3b786e55221074ebef585b6863/Inception%20classifier.py) python file contains the Inception module python code using Keras library.
* The [Opening and sorting the files](https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/blob/414d89c2e4de0d3b786e55221074ebef585b6863/Opening%20and%20sorting%20the%20files.py) python folder contains the steps of opening and labeling the files.
* The [Channel selection](https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/blob/414d89c2e4de0d3b786e55221074ebef585b6863/Channel%20selection.py) python file involves general concepts of the channel selections approaches. </div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

<div align="justify"> Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request </div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Rasoul Zahedifar - rasoul.zahedifar75@gmail.com,
Alireza Rafiei - alirezarafieieng@gmail.com

GitHub Link: [https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model](https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model)

Journal Link: [https://ieeexplore.ieee.org/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model](https://ieeexplore.ieee.org/document/9828387)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- REFERENCE -->
## Reference

If you are interested in this work, please cite:

```
@ARTICLE{
  9828387,
  author={Rafiei, Alireza and Zahedifar, Rasoul and Sitaula, Chiranjibi and Marzbanrad, Faezeh},
  journal={IEEE Access}, 
  title={Automated Detection of Major Depressive Disorder With EEG Signals: A Time Series Classification Using Deep Learning}, 
  year={2022},
  volume={10},
  pages={73804-73817},
  doi={10.1109/ACCESS.2022.3190502}
  }
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model.svg?style=for-the-badge
[contributors-url]: https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model.svg?style=for-the-badge
[forks-url]: https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/network/members
[stars-shield]: https://img.shields.io/github/stars/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model.svg?style=for-the-badge
[stars-url]: https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/stargazers
[issues-shield]: https://img.shields.io/github/issues/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model.svg?style=for-the-badge
[issues-url]: https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/issues
[license-shield]: https://img.shields.io/github/license/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model.svg?style=for-the-badge
[license-url]: https://github.com/Rasoul-Zahedifar/Detection-of-MDD-with-EEG-Signals-using-InceptionTime-model/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/rasoul-zahedifar