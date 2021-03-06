---
layout: page
title: Setup
permalink: /setup/
---
In order to follow this lesson, you will need to make sure the following software is installed on your computer.

## Part one: Manually scrape data using browser extensions

For the first half of the lesson, we will use a Chrome browser extension to get started with web scraping. Follow the steps below to install Scraper:

1. Make sure to have the Chrome browser installed in your computer. Follow the steps on [this website](https://chromeenterprise.google/browser/download/?utm_source=adwords&utm_medium=cpc&utm_campaign=2022-H1-chromebrowser-paidmed-paiddisplay-other-chromebrowserent&utm_term=downloadnow-chrome-browser-download&utm_content=GCEJ&brand=GCEJ&gclid=CjwKCAjw9qiTBhBbEiwAp-GE0U3sZqNSBoMSkTrxi2fMdK3Xajoq7KFOuEsMfa9o2KnE5vXBnzLovBoCP1IQAvD_BwE&gclsrc=aw.ds#windows-tab) and choose your OS if you need to install it.

2. Open [Chrome Web Store](https://chrome.google.com/webstore/category/extensions)

3. Search for “Scraper” in extensions and it should be the first one listed. Alternatively, you may or click on this link [Scraper extension](https://chrome.google.com/webstore/detail/scraper/mbigbapnjcgaffohmbkdlecaccepngjd).

4. Click the "add to" chrome button.


## Part two: Write Python programs to automatically scrape data

### Shell and Python
The second part of the lesson requires the Python programming language and access to a command-line interface (shell) on your computer.
Please refer to [the Software Carpentry setup instructions](http://swcarpentry.github.io/workshop-template/#setup) for
*the Bash shell* and *Python* if you need guidance.

> ## Prerequisites
> This part of the lesson requires some prior knowledge of Python and how to use a shell.
> If you need help getting started on those topics, we suggest going through the following
> lessons first (during a workshop or on your own):
>
> * [The Unix Shell](http://swcarpentry.github.io/shell-novice/)
> * [Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/)
>
{: .prereq}

### Scrapy

Once you have a working installation of Python, the next step is to install [Scrapy](https://scrapy.org/).

If you have installed Python using the Anaconda framework as suggested by the Software Carpentry setup instructions,
you can easilly install Scrapy by doing the following:

1. Open a new shell (e.g. Terminal on Mac, or the Anaconda command-line tool on Windows)
2. Type the following:

> conda install scrapy
>
{: .source}

Alternatively, if you have another distribution of Python, you can try using pip:

> pip install Scrapy
>
{: .source}

If you run into issues while installing Scrapy, refer to the
[official Scrapy install guide](https://doc.scrapy.org/en/latest/intro/install.html#intro-install)
or get in touch with your lesson instructor.
