
<!-- PROJECT LOGO -->
<br />
<p align="center">

<h3 align="center">Port Scanner</h3>

  <p align="center">
    An active reconnaissance tool using banner grabbing techniques to gather target system information
    <br />
    <a href="https://github.com/KyReid/port-scanner"><strong>Explore the docs</strong></a>
    <br />
    <br />
    <a href="https://github.com/KyReid/port-scanner">View Demo</a>
    ·
    <a href="https://github.com/KyReid/port-scanner/issues">Report Bug</a>
    ·
    <a href="https://github.com/KyReid/port-scanner/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->

## About The Project

### Built With

* [python 3.8](https://www.python.org/)
* [pycharm community edition IDE](https://www.jetbrains.com/pycharm/)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* python
  ```sh
  sudo apt install python3
  ```
* pip
  ```sh
  sudo apt install pip3
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/KyReid/Port Scanner.git
   ```

<!-- USAGE EXAMPLES -->

## Usage

* Program help menu
```shell
python3 main.py -h
usage: main.py [-h] [-i INTERNET_PROTOCOL] [-p PORT_MODE]

Port Scanner with Banner Grabbing functionality

optional arguments:
  -h, --help            show this help message and exit
  -i INTERNET_PROTOCOL  IP address, use /x for range in
                        255.255.255.x network
  -p PORT_MODE          s: single port | m: multiple ports |
                        r: range of ports
```

* Executing single scan on port 80
```shell
python3 main.py -i 10.0.2.15 -p s

Enter port number: 80

PORT		STATUS
-------------------------
80		OPEN

[+] port Scanning is complete.
[+] port service processing complete.

Port service details displayed below:
----------------------------------------
PORT 80 service information
HTTP/1.1 400 Bad Request
Date: Mon, 07 Dec 2020 18:24:59 GMT
Server: Apache/2.4.46 (Ubuntu)
Content-Length: 301
Connection: close
Content-Type: text/html; charset=iso-8859-1

<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>400 Bad Request</title>
</head><body>
<h1>Bad Request</h1>
<p>Your browser sent a request that this server could not understand.<br />
</p>
<hr>
<address>Apache/2.4.46 (Ubuntu) Server at 127.0.1.1 Port 80</address>
</body></html>

```

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any
contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- CONTACT -->

## Contact

Project Link: [https://github.com/KyReid/port-scanner](https://github.com/KyReid/port-scanner)

