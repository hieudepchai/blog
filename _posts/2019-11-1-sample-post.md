---
layout: post
categories: posts
title: Zing Mp3 MusicCrawler - Last Modified Nov 1 2019
subtitle: In this project, I used Selenium (python) + Multithreadprocessing to build a crawler on Zing Mp3 Top 100 pages,then export data to json/csv files.
featured-image: /images/2019-11-1/selenium-with-python.png
tags: [python, cralwer, selenium, multithread]
date-string: NOVEMBER 1, 2019
---
# Source code
[Music Cralwer](https://github.com/hieudepchai/hieudepchai.github.io){:target="_blank"}
# Details
1. Before start crawling, you need to install packages (python3, pip, selenium and multithreadprocessing) and Chronium (Ubuntu)

1. Explaination on files:
<ul>
  <li>multithread_crawler.py: crawler file. To start crawling, run this. Note that you need to <b>adjust chromepath</b> depending on Ubuntu/Windows and add urls to <b>list_top100_urls</b>. The output file ( songs.json) is in
  folder <b>result</b>.</li>
  <li>chromedriver.exe: Chrome driver file used for Windows</li>
  <li>generate_metadata.py: export lists of genres and singers to json/csv files in folder <b>result</b> </li>
  <li>other files: samples I collected as materials. Don't mind about them.</li>
</ul>
