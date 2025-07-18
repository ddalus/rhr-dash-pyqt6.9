<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->




[![Contributors](https://img.shields.io/github/contributors/ddalus/rhr-dash-pyqt6.9.svg?style=for-the-badge)](https://github.com/ddalus/rhr-dash-pyqt6.9/commits?author=ddalus&since=2025-07-01&until=2025-07-07)
[![Forks](https://img.shields.io/github/forks/ddalus/rhr-dash-pyqt6.9.svg?style=for-the-badge)](https://github.com/ddalus/rhr-dash-pyqt6.9/forks)
[![Stargazers](https://img.shields.io/github/stars/ddalus/rhr-dash-pyqt6.9.svg?style=for-the-badge)](https://github.com/ddalus/rhr-dash-pyqt6.9/stargazers)
[![Issues](https://img.shields.io/github/issues/ddalus/rhr-dash-pyqt6.9.svg?style=for-the-badge)](https://github.com/ddalus/rhr-dash-pyqt6.9/issues)
[![License](https://img.shields.io/github/license/ddalus/rhr-dash-pyqt6.9.svg?style=for-the-badge)](https://github.com/danamon2002/RHR25-Dash/blob/main/LICENSE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/nicholas-mankoski-37039328a/)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://cdn.d1baseball.com/uploads/2023/12/21144147/umasslowell.png" alt="Logo" width="400" height="400">
  </a>

<h3 align="center">Riverhawk Racing Dashboard</h3>

  <p align="center">
    Current dashboard for RHR car for the 2025-2026 year and beyond!
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    &middot;
    <a href="https://github.com/github_username/repo_name/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/github_username/repo_name/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>
 


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Dashboard</a>
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
## About The Dashboard



The dashboard is an essentail part of the car that updates the driver in real time for nessarsy values on the car such as, current gear, speed, and ECU information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![PyQt](https://img.shields.io/badge/PyQt-GUI-blue)](https://riverbankcomputing.com/software/pyqt/intro)
* [![QML](https://img.shields.io/badge/QML-UI-red)](https://doc.qt.io/qt-6/qmlapplications.html)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

The two prerequisited languages are PyQt6 and QML6.9, just pip install for the python libary in command prompt and install qml directly from their website.

### Prerequisites

Instalation prerequisites:
* ## PyQt6
  ```sh
  -pip install pyqt6
  ```



* ## QML
  ```sh
  https://doc.qt.io/qt-6/qtquick-deployment.html (in the top right there is a download buttom)
  ```


  
* ## Change WIfi on RasberryPi

  ### Step 1:
  Turn on Pi and in the command line

  
  ```sh
  sudo raspi-config
  ```

  ### Step 2:

  Scroll to System Options using arrow keys and press enter

  ### Step 3:

  Scroll to Wireless LAN

  ### Step 4:

  Enter the SSID and password of the wifi that the laptop is using that you plan on sshing from




* ## How to SSH into RasberryPi

  ### Step 1:

  Open CMD on the computer you are trying to connect the pi to and enter the command
  ```sh
  SSH [username]@[ip address]
  ```

  ### Step 1.5:

  If RasberryPi IP is unknown on the Pi comand line type:
  ```sh
  ifconfig
  ```
  
  Look for inet and use that as IP address

  ### Step 2:

  When prompted type:
  ```sh
  yes
  ```

* ## Dashboard Start
  ```sh
  startx
  ```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/github_username/repo_name/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=github_username/repo_name" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the project_license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - Nicholas Mankoski - nicholasmankoski@gmail.com - discord: d4edalus

Project Link: [https://github.com/ddalus/rhr-dash-pyqt6.9](https://github.com/ddalus/rhr-dash-pyqt6.9)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
