<div id="top"></div>
<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/saharsh-agrawal/Minesweeper">
    <!--<img src="https://raw.githubusercontent.com/saharsh-agrawal/Minesweeper/main/logo.png" alt="Logo" width="140">-->
  </a>

<h3 align="center">Minesweeper (with Autoplay)</h3>

  <p align="center">
    <i>The classic Minesweeper game with an AI-powered Autoplay feature</i>
    <br />
    <!--<a href="#getting-started"><strong>Explore the docs »</strong></a>
    <br />-->
    <a href="https://github.com/saharsh-agrawal/Minesweeper/issues">Report Bug</a>
    ·
    <a href="https://github.com/saharsh-agrawal/Minesweeper/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Minesweeper (with Autoplay) is a Java-based implementation of the classic Minesweeper game, planned to be enhanced with an AI-powered Autoplay feature that helps to automatically open or mark the obvious boxes based on basic AI logic. The game presents users with three difficulty levels and maintains high scores for each level in a local `highScore.txt` file.

### Features
- Classic Minesweeper gameplay
- Three difficulty levels to choose from
- AI-powered Autoplay feature (In development)
- Local high score tracking

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- INSTALLATION -->
## Installation

To set up Minesweeper (with Autoplay) locally, follow these steps:

### Prerequisites
- Ensure you have at least JDK 22 installed. You can download it from [here](https://www.oracle.com/java/technologies/javase/jdk22-archive-downloads.html).
- Any Java IDE - (Install IntelliJ IDEA from [here](https://www.jetbrains.com/idea/)).

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/saharsh-agrawal/Minesweeper.git
   cd Minesweeper
2. Open the project in IntelliJ IDEA.

3. Run the application:
    - Navigate to `src` folder.
    - Locate `Minesweeper.java`.
    - Right-click on `Minesweeper.java` and select `Run 'Minesweeper.main()'`.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE -->
## Usage

Upon running the application, a main window will appear, asking the user to choose a level of difficulty (Easy, Medium, Hard). The game board is then presented according to the chosen difficulty. High scores are saved locally in `highScore.txt`.

### Autoplay Feature
- The Autoplay feature is currently under development.
- When enabled, it will use AI logic to help play the game.
- A button exists to toggle this feature.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### Steps to Contribute
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Setup
- Ensure your development environment is set up with JDK 22 and IntelliJ IDEA.
- Refer to the [Installation](#installation) section for initial setup instructions.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Fix high score storage issue for packed JAR files.
- [ ] Implement Autoplay feature with basic AI logic.
- [ ] Add more advanced AI features for improved gameplay.

See the [open issues](https://github.com/saharsh-agrawal/Minesweeper/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Maintainer - [Saharsh Agrawal](https://github.com/saharsh-agrawal)

<p align="right">(<a href="#top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/saharsh-agrawal/Minesweeper.svg?style=for-the-badge
[contributors-url]: https://github.com/saharsh-agrawal/Minesweeper/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/saharsh-agrawal/Minesweeper.svg?style=for-the-badge
[forks-url]: https://github.com/saharsh-agrawal/Minesweeper/network/members
[stars-shield]: https://img.shields.io/github/stars/saharsh-agrawal/Minesweeper.svg?style=for-the-badge
[stars-url]: https://github.com/saharsh-agrawal/Minesweeper/stargazers
[issues-shield]: https://img.shields.io/github/issues/saharsh-agrawal/Minesweeper.svg?style=for-the-badge
[issues-url]: https://github.com/saharsh-agrawal/Minesweeper/issues
