---
title: Web Scraper for Farmworker Justice
date: 2019-02-28T22:53:12.436Z
repo: wsf-scrape
tags:
  - python
  - requests
  - selenium
  - regex
---
This is a collection of a few web scraping scripts I made with Python in late 2018. This project has a special place in my heart because it marked the first time that I used my coding skills to contribute to a social justice movement.

My friend Kim runs a local political action group called Washtenaw Solidarity with Farmworkers which aims to promote the fair treatment of the farmworkers in America. Her biggest project at the time was keeping Wendy's off of the Universiy of Michigan's campus because of Wendy's refusal to join the Fair Food Program which provides a framework for corporations to ethically source their tomatoes ensuring that they are from farms that do not abuse their workers. She made a petition and needed to send it out to as many student organizations as possible to gain support.

When I went over to her house and saw her manually copying all 1500 student org contact information, I was mortified. She was going to get carpal tunnel! I decided to volunteer my skills and I wrote a few scripts to gather the contact info from University of Michigan, Eastern Michigan, and Washtensaw Community College.

I used the amazing Selenium library to click through these websites to find the links to all the contact pages. Then I used the requests library to get the HTML and I parsed it using regex if a simple DOM query didn't suffice.
