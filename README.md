# Scraping real estate data in Belgium

Scraping project that collects information about properties for sale in Belgium and saves it to a `.csv` file.

## Description

This program visits Belgian real estate website ImmoWeb and scrapes information from over 10,000 houses and apartments for sale from all over Belgium. Details include price, surface area, bedroom number, and so on.

A `.csv` file wil be generated with all the information collected.

It uses Python, Selenium and BeautifulSoup to fetch and parse the information.

The concurrent.futures module is used to improve speed.

## Installation

Just download the source code and run `python3 main.py` from the terminal.

## Usage

The data collected can be used for exploratory analysis and model training to predict real estate pricing.

## Contributors

This a project for the Brussels Becode AI training.

Contributors are:
- [zowette](https://github.com/zowette)
- [tanialemos](https://github.com/tanialemos)
- [AhmetSmlCicek](https://github.com/AhmetSmlCicek)

## Timing

4-day project (from 28 Sept 2022 to 3 Oct 2022)