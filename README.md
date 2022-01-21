<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/lucasclerissepro/northstar">
    <img src=".github/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Northstar</h3>

  <p align="center">
    Northstar is a horizontally scalable and multi-tenant Kubernetes cluster provisioner and orchestrator.
    <br />
    <a href="https://github.com/lucasclerissepro/northstar"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/lucasclerissepro/northstar">View Demo</a>
    ·
    <a href="https://github.com/lucasclerissepro/northstar/issues">Report Bug</a>
    ·
    <a href="https://github.com/lucasclerissepro/northstar/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

With Northstar you define Kubernetes cluster blueprints and create clusters using API calls, Northstar figures out automatically how to create the clusters and maintain them. In a way you can think of Northstar like EKS, AKS or any other managed kubernetes but multi-cloud and entirely self-hosted.

Northstar is entirely extensible trough plugins, if you want your clusters to be provisionned with Nginx preinstalled, that's completely possible.

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

* [Rust](https://nextjs.org/)
* [React.js](https://reactjs.org/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

To run Northstar you will need to have Rust installed on your machine, you can then run:

        cargo build

To build the various libraries and binaries.

## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Cloud Provider
  - [ ] AWS
    - [ ] K3S
    - [ ] Managed
  - [ ] Google Cloud
    - [ ] K3S
    - [ ] Managed
  - [ ] Azure 
    - [ ] K3S
    - [ ] Managed

See the [open issues](https://github.com/lucasclerissepro/northstar/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Author - [@lucasclerisse](https://twitter.com/lucasclerisse) - lucasclerisse@protonmail.com

Project Link: [https://github.com/lucasclerissepro/northstar](https://github.com/lucasclerissepro/northstar)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/lucasclerissepro/northstar.svg?style=for-the-badge
[contributors-url]: https://github.com/lucasclerissepro/northstar/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/lucasclerissepro/northstar.svg?style=for-the-badge
[forks-url]: https://github.com/lucasclerissepro/northstar/network/members
[stars-shield]: https://img.shields.io/github/stars/lucasclerissepro/northstar.svg?style=for-the-badge
[stars-url]: https://github.com/lucasclerissepro/northstar/stargazers
[issues-shield]: https://img.shields.io/github/issues/lucasclerissepro/northstar.svg?style=for-the-badge
[issues-url]: https://github.com/lucasclerissepro/northstar/issues
[license-shield]: https://img.shields.io/github/license/lucasclerissepro/northstar.svg?style=for-the-badge
[license-url]: https://github.com/lucasclerissepro/northstar/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/lucasclerisse
[product-screenshot]: images/screenshot.png
