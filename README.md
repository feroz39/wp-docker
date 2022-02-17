<div id="top"></div>

<h2 align="center">Wordpress Installer</h2>

  <p align="center">
    Clean WordPress installation from scratch.
    <br />
    <br />
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## 🚧 About The Project

This is a useful project that integrates all tools to get a clean and easy-to-use WordPress installation from scratch.

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

<p>
  <a href="https://www.docker.com/" target="_blank"> <img src="https://github.com/cosimoscarcella/cosimoscarcella/raw/main/images/logo-docker.svg" alt="docker" width="64" height="64"/></a>
  <a href="https://docs.docker.com/compose/" target="_blank"> <img src="https://github.com/cosimoscarcella/cosimoscarcella/raw/main/images/logo-docker-compose.svg" alt="docker" width="64" height="64"/></a>
  <a href="https://wordpress.com/" target="_blank"> <img src="https://github.com/cosimoscarcella/cosimoscarcella/raw/main/images/logo-wordpress.svg" alt="docker" width="64" height="64"/></a>
  <a href="https://wp-cli.org/" target="_blank"> <img src="https://github.com/cosimoscarcella/cosimoscarcella/raw/main/images/logo-wp-cli.svg" alt="docker" width="64" height="64"/></a>
  <a href="https://www.mysql.com/" target="_blank"> <img src="https://github.com/cosimoscarcella/cosimoscarcella/raw/main/images/logo-mysql.svg" alt="mysql" width="64" height="64"/></a>
  <a href="https://www.phpmyadmin.net/" target="_blank"> <img src="https://github.com/cosimoscarcella/cosimoscarcella/raw/main/images/logo-phpmyadmin.svg" alt="mysql" width="64" height="64"/></a>
</p>

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## 🏃 Getting Started

To get your WordPress installation running follow these simple steps.

### Prerequisites

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)


<!-- USAGE EXAMPLES -->
## 🚀 Usage

### Install

1. Modify passwords and variables inside ```.env``` file as you wish
3. Run shell command
   ```sh
   sh wp-install.sh
   ```
4. Your WordPress installation is now available at [http://localhost:8080]( http://localhost:8080)
5. PhpMyAdmin installation is now available at [http://localhost:3000]( http://localhost:3000)


### Uninstall

1. Run shell command
   ```sh
   sh wp-uninstall.sh
   ```
2. Use ```-h | --help``` option for further information

### Init Wordpress Installation

1. Run shell command
   ```sh
   sh wp-init.sh
   ```
2. Your Wordpress installation in now initialized using **wp-cli** according to  ```./bin/install-wp.sh``` file

### Execute wp-cli command
1. Run shell command
   ```sh
   sh wp-cli.sh "<command>"
   ```
   to execute your custom wp-cli commands. For example ```./wp-cli.sh "wp db export -" > dump.sql``` to export wordpress database

<p align="right">(<a href="#top">back to top</a>)</p>