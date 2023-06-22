# Star Trek VS Star Wars: Which Universe Has Better Data?

Data is everywhere, and it can tell us many stories about the world we live in. But data is not always uniform, consistent, or easy to analyze. Sometimes, data reflects the characteristics of its source, and we can learn something about the nature of that source by examining the data. In this project, I will compare two sources of data that are very different from each other: Star Wars and Star Trek. These are two of the most popular and influential science fiction franchises in history, and they have generated a vast amount of data in various media, such as movies, books, TV shows, comics, video games, and online databases. However, these two franchises also have very different styles, themes, and philosophies, which may affect how their data is structured, organized, and presented. By scraping data from Wookieepedia, the online encyclopedia of Star Wars, and STAPI, the Star Trek API, I will compare and contrast the data of these two universes in four categories: characters, species, astronomical objects, and spacecrafts. I will also explore how the data structure for each universe resembles the respective universe itself. For example, Star Trek data is more clean, categorized, and standardized, reflecting its vision of a rational and orderly future; while Star Wars data is more messy, descriptive, and diverse, reflecting its depiction of a chaotic and adventurous galaxy. My main objectives are to demonstrate how data can be used to analyze and compare different fictional worlds, and to show how data can reveal something about the nature and culture of its source.

## Installation

To run this project, you will need STAPI, Docker, Python 3 and the following libraries:

- requests
- BeautifulSoup
- pandas
- motplotlib
- seaborn
- pyarrow
- pickle
- tqdm
- pathlib
- urllib
- numpy

## Data Sources

The data for this project comes from two online databases: Wookieepedia and STAPI.

- Wookieepedia is a fan-made wiki that contains information about the Star Wars universe, such as characters, planets, species, vehicles, and more. The URL for Wookieepedia is https://starwars.fandom.com/wiki/Main_Page.
- STAPI is a RESTful web service that provides data about the Star Trek universe, such as characters, planets, species, starships, and more. It has a simple and consistent interface that allows users to query its data easily. The URL for STAPI is http://stapi.co/.

For the Star Wars data, I used a good portion of the Wookieepedia scrape from this GitHub repository: https://github.com/dennisbakhuis/wookieepediascience. This repository contains scripts and notebooks that scrape and analyze data from Wookieepedia using Python and pandas. I modified some of the scripts to suit my needs and added some additional scraping functions. I would like to thank Dennis Bakhuis for creating and sharing this repository.
