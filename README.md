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

<img src="https://raw.githubusercontent.com/lucasclerissepAro/filemeta/main/.github/logo.png#gh-dark-mode-only" alt="Logo" width="250" height="80">
<img src="https://raw.githubusercontent.com/lucasclerissepro/filemeta/main/.github/logo_white.png#gh-light-mode-only" alt="Logo" width="250" height="80">
<br />
<br />

<p align="center">
Filemeta is a program allowing you to recover information about any files.
Extensible by nature Filemeta can support almost any filetype.
<br>
<br />
<a href="https://github.com/lucasclerissepro/filemeta"><strong>Explore the docs »</strong></a>
<br />
<br />
<a href="https://github.com/lucasclerissepro/filemeta">View Demo</a>
·
<a href="https://github.com/lucasclerissepro/filemeta/issues">Report Bug</a>
·
<a href="https://github.com/lucasclerissepro/filemeta/issues">Request Feature</a>
</p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
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

Filemeta is at the core of [Filegraph](https://filegraph.io) and is used to discover as much as possible of informations
of files. Multiple plugins are available for each filetype, including some plugins relying on machine learning.

## Getting Started

You can download prebuilt binaries on the [release]() page or follow the section below to build from source.

## How it works

TBD

### Prerequisites

To run filemeta you will need to have Rust installed on your machine, you can then run:

    cargo build

To build the various libraries and binaries.

## Usage

When you have the binary just run:

    filemeta start

And finally:

    filemeta submit file hello.png

Filemeta works best when running as a daemon on your machine because some plugins are requiring a bit of startup time.

_For more examples, please refer to the [Documentation](https://docs.filegraph.io/meta)_

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

I currently develop Filemeta on my free time so the roadmap is simple and something I can execute in a limited amount of
time.

See the [open issues](https://github.com/lucasclerissepro/filemeta/issues) for a full list of proposed features (and
known issues) and [milestones]() for the roadmap.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any
contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also
simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Author - [@lucasclerisse](https://twitter.com/lucasclerisse) - lucasclerisse@protonmail.com

Project Link: [https://github.com/lucasclerissepro/filemeta](https://github.com/lucasclerissepro/filemeta)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/lucasclerissepro/filemeta.svg?style=for-the-badge

[contributors-url]: https://github.com/lucasclerissepro/filemeta/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/lucasclerissepro/filemeta.svg?style=for-the-badge

[forks-url]: https://github.com/lucasclerissepro/filemeta/network/members

[stars-shield]: https://img.shields.io/github/stars/lucasclerissepro/filemeta.svg?style=for-the-badge

[stars-url]: https://github.com/lucasclerissepro/filemeta/stargazers

[issues-shield]: https://img.shields.io/github/issues/lucasclerissepro/filemeta.svg?style=for-the-badge

[issues-url]: https://github.com/lucasclerissepro/filemeta/issues

[license-shield]: https://img.shields.io/github/license/lucasclerissepro/filemeta.svg?style=for-the-badge

[license-url]: https://github.com/lucasclerissepro/filemeta/blob/master/LICENSE.txt

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

[linkedin-url]: https://linkedin.com/in/lucasclerisse

[product-screenshot]: images/screenshot.png
