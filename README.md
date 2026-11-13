# FIFA World Cup 2026 – DevOps Group 23

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Apache](https://img.shields.io/badge/Apache_httpd-D22128?logo=apache&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

> A FIFA World Cup 2026 themed web page, containerised with Apache httpd.

## Overview

Static web page containerised with **Apache httpd**. The repository is used in the DevOps training track to practise Git, building Docker images and running them as containers.

## Tech Stack

- **Docker**
- **Apache httpd**
- **HTML/CSS**
- **Git**

## Repository Structure

```text
data.txt
Dockerfile
index.html
README.md
```

## Getting Started

### Run with Docker

```bash
git clone https://github.com/Gamal-Mohammad/test-repo-gr23.git
cd test-repo-gr23
docker build -t test-repo-gr23 .
docker run -d --name test-repo-gr23 -p 8080:80 test-repo-gr23
```

Then open http://localhost:8080.

## Author

**Gamal Mohammad**

[![GitHub](https://img.shields.io/badge/GitHub-Gamal--Mohammad-181717?logo=github)](https://github.com/Gamal-Mohammad)
