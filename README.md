[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


# QR-Code

Algorithme qui permet de générer le QR Code d'un site. Un image sur fond blanc et une image sur fond transparent sont créées.



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
Une version de Python avec ces librairies est nécessaire.
```
$ pip install qrcode[pil]
$ pip install opencv-python
$ pip install numpy
```

### Installation
1. Il suffit d'executer le notebook *qrcode.ipynb*.



<!-- USAGE EXAMPLES -->
## Usage
Pour créer un QR Code du site [https://galagain.com/cv.pdf](https://galagain.com/cv.pdf), il faut:

1. Lancer la fonction *create_qrcode()* avec l'URL en paramètre:
```create_qrcode("https://galagain.com/cv.pdf")```
2. Récupérer les deux images générées:
- *qr_code_transparent.png*
![Image sur fond transparent][transparent-image]
- *qr_code_white.png*
![Image sur fond blanc][white-image]



<!-- MARKDOWN LINKS -->
[contributors-url]: https://github.com/importFourmi/QR-Code/graphs/contributors
[forks-url]: https://github.com/importFourmi/QR-Code/network/members
[stars-url]: https://github.com/importFourmi/QR-Code/stargazers
[issues-url]: https://github.com/importFourmi/QR-Code/issues
[license-url]: https://github.com/importFourmi/QR-Code/blob/master/LICENSE.txt
[linkedin-url]: https://www.linkedin.com/in/calvin-galagain/



<!-- MARKDOWN IMAGES -->
[white-image]: images/qr_code_white.png
[transparent-image]: images/qr_code_transparent.png
