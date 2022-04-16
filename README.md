<div id="top"></div>

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



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/michaelradu/python-cli-chat">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Python CLI Chat</h3>

  <p align="center">
    This is a CLI app that allows 2 or more people to connect to a chatroom and talk.
    <br />
    <a href="https://github.com/michaelradu/python-cli-chat">View Demo</a>
    ·
    <a href="https://github.com/michaelradu/python-cli-chat/issues">Report Bug</a>
    ·
    <a href="https://github.com/michaelradu/python-cli-chat/issues">Request Feature</a>
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
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/michaelradu/python-cli-chat)

This is a CLI app that allows 2 or more people to connect to a chatroom and talk. I built this in an afternoon for fun and learning purposes. Currently it only works with people on the same network as you, which is what I had in mind when I made it.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Assuming you have python3 and pip installed (if not get them [here](https://www.python.org/downloads/) or from your package manager), install the colorama package, it is used for changing text color.
* colorama
  ```sh
  pip3 install colorama
  ```

### Installation & Usage

1. Clone the repo
   ```sh
   git clone https://github.com/michaelradu/python-cli-chat.git
   ```
2. Start the server
   ```sh
   python server.py
   ```
3. Start the client
   ```sh
   python client.py 
   ```
4. Enter a username of your choice
4. Start chatting

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [*] Basic Chat
- [ ] E2E encryption
- [ ] Internet chat
    - [ ] Multiple chat rooms

See the [open issues](https://github.com/michaelradu/python-cli-chat/issues) for a full list of proposed features (and known issues).

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



<!-- LICENSE -->
## License

Distributed under the GNU GENERAL PUBLIC License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/michaelradu/python-cli-chat.svg?style=for-the-badge
[contributors-url]: https://github.com/michaelradu/python-cli-chat/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/michaelradu/python-cli-chat.svg?style=for-the-badge
[forks-url]: https://github.com/michaelradu/python-cli-chat/network/members
[stars-shield]: https://img.shields.io/github/stars/michaelradu/python-cli-chat.svg?style=for-the-badge
[stars-url]: https://github.com/michaelradu/python-cli-chat/stargazers
[issues-shield]: https://img.shields.io/github/issues/michaelradu/python-cli-chat.svg?style=for-the-badge
[issues-url]: https://github.com/michaelradu/python-cli-chat/issues
[license-shield]: https://img.shields.io/github/license/michaelradu/python-cli-chat.svg?style=for-the-badge
[license-url]: https://github.com/michaelradu/python-cli-chat/blob/master/LICENSE.txt
