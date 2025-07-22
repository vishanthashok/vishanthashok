<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/vishanth-ashok/options-volatility-analyzer">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Options Volatility Analyzer</h3>

  <p align="center">
    A Python tool for analyzing SPY options volatility surfaces using vectorized computation.
    <br />
    <a href="https://github.com/vishanth-ashok/options-volatility-analyzer"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/vishanth-ashok/options-volatility-analyzer">View Demo</a>
    ·
    <a href="https://github.com/vishanth-ashok/options-volatility-analyzer/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/vishanth-ashok/options-volatility-analyzer/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

[![Product Screenshot][product-screenshot]](https://example.com)

This Python project extracts and analyzes SPY options volatility surfaces, processes over 1,000 option contracts across 30 expirations, and visualizes implied volatility smiles to uncover skew and convexity patterns. It benchmarks ATM implied volatility against realized volatility to detect short-volatility trade signals.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
* [yfinance](https://pypi.org/project/yfinance/)
* Matplotlib
* NumPy
* pandas

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

### Prerequisites

Make sure Python and `pip` are installed:

```sh
pip install yfinance matplotlib numpy pandas
