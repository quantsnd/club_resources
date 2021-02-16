# QCND
Official resource page for the **Quant Club of Notre Dame**!

<img align="right" width="200" height="180" src="https://github.com/kyduff/qcnd/blob/readme_updates/nd_logo.png">

## Table of contents

:one: [About the club](#about-the-club)

:two: [Club communication](#club-communication)

:three: [Upcoming events and ways to get involved](#upcoming-events-and-ways-to-get-involved)

:four: [GitHub and git](#github-and-git)

:five: [Interacting with the code](#interacting-with-the-code)

:six: [Reference materials](#reference-materials)

:seven: [Leadership](#leadership)

## About the club

**Our mission** is to prepare club members for success in careers and competitions related to quantitative trading by providing workshops, projects and exposure to industry-leading firms.

We'll chat regularly on Slack (see [Club communication](#club-communication) to join) and meet every week with interactive presentations and time to practice new skills. Towards the end of the semester we'll start working on projects with guidance from one of our corporate sponsors, [Belvedere Trading](http://www.belvederetrading.com/). Starting next year, we'll also be putting together teams to send to international trading competitions at the University of Chicago and MIT.

## Club communication

:speech_balloon: Join our [Slack workspace](https://join.slack.com/t/quantclubnd/signup)

:speech_balloon: Join our [Google Group](https://groups.google.com/a/nd.edu/g/quant-club-2020-21-list)

:speech_balloon: Subscribe to our [Google Calendar](https://calendar.google.com/calendar/u/0?cid=cXVhbnRzQG5kLmVkdQ)

## Upcoming events and ways to get involved

We will be meeting **every week** starting soon. To stay in the loop, join our Slack workspace and Google Group, and subscribe to our public calendar. The links to those resources are all under [Club communication](#club-communication). We'll regularly post updates about meeting times/places in there, and everyone in leadership is regularly available via Slack or email if you have questions.

If you attend a meeting, make sure to fill out the [attendance form](https://docs.google.com/forms/d/e/1FAIpQLSeQvcllWy4vFp2ioBMzArI2ouFOukV_Kx9PTUcSuPcUqH4HJw/viewform?usp=sf_link) with the meeting's code!

## GitHub and git

:star: What is GitHub?

* GitHub is a web server meant for managing *git clients*
* The *git client* is where the magic happens

:star: And what is the *git client*?

* `git` is a version control system
* Developed by Linus Torvalds (inventor of Linux)
* It tracks changes in a series of *commits* and tracks different phases of development in *branches* which eventually get merged into the deployed version

:star: Why do we use `git`?

* `git` allows people to collaborate on code and monitor the evolution of their projects
* It is the leading system *by far*

:star: Resources:

* [Pro Git book](https://git-scm.com/book/en/v2)
* [Git documentation (manual pages)](https://git-scm.com/docs)
* [Codecademy course](https://www.codecademy.com/learn/learn-git)

## Interacting with the code

Practically all of our code is written in *Python 3* and assumes you have some packages installed before using it.

### Package installation instructions
We *highly* recommend managing all of your packages in a virtual environment. If you already have a virtual environment set up and activated, feel free to jump straight to the "Installation Step".

:white_check_mark: Create a virtual environment.  In Quant Club we use the [Anaconda Software Distribution](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) to manage our virtual environments. To create one, call (in the Terminal on MacOS and in Anaconda Prompt on Windows)
```
conda create -n <environment name> python=3.8 -y
```
and replace `<environment name>` with whatever you want the environment to be named.

:white_check_mark: Enter your virtual environment.  To enter a previously created virtual environment, call
```
conda activate <environment name>
```
and notice the environment name appear in parentheses at the beginning of your prompt.

:white_check_mark: Installation Step.  To install the required packages, call
```
conda install --file requirements.txt -y
```
in the repository's main directory. You may see some warning messages - this is OK.

You're now ready to start interacting with the code!

## Reference materials

* [Max Dama on Automated Trading](http://isomorphisms.sdf.org/maxdama.pdf)
* [Interview with a quant portfolio manager about building trading strategies](https://blog.quandl.com/interview-with-a-quant-part-one)
* [Intro to Linux command line](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview)
* [HackerRank](https://www.hackerrank.com/)
* [Intro to Python 3 from Codecademy](https://www.codecademy.com/learn/learn-python-3)
* [Comprehensive Python tutorial](https://docs.python.org/3/tutorial/)
* [Python course by Google](https://developers.google.com/edu/python/introduction)
* [Numpy tutorial](https://cs231n.github.io/python-numpy-tutorial/)

## Leadership

:small_orange_diamond: **Kyle Duffy - Chairperson**

Senior, Mathematics and Computer Science

Working at Belvedere Trading

kduffy5@nd.edu

I started my career in trading when I read *The Intelligent Investor* by Benjamin Graham. Now I primarily focus on merging statistics and computing to create systematic options trading strategies. I love what I do and always like to learn more about math and computing!

:small_orange_diamond: **Sam Gruenler - Managing Director**

Junior, Economics and ACMS

Working at Group One Trading

sgruenle@nd.edu

I’ve been interested in problems involving math and markets since high school, and when I discovered the quant trading field, it seemed like a great combination of these interests. Since then, I’ve focused particularly on applying statistics to commodity derivatives, and I’ll be working at Group One Trading next summer.

:small_orange_diamond: **Ben Gluckow - Managing Director**

Junior, ACMS and Economics

Working at SIG

bgluckow@nd.edu

I came into Notre Dame thinking that I would be more interested in working in data science or technology. I stumbled across quant trading in my career search, and it seemed like a great fit for applying technical skills to interesting financial problems. I have worked at Analysis Group, an economic consulting firm, and will be with SIG’s ETF desk next summer. 

:small_orange_diamond: **Matteo Cosentino - Operating Officer**

Junior, Physics and Economics

Working at Bank of America

mcosenti@nd.edu

I began investing many years before college, but once I discovered the power of computational physics, I saw the opportunity to apply this to my investing strategies. Since then I have worked at Wolfe Research, a quantitative research firm, and will be working for Bank of America’s quant group next summer.

:small_orange_diamond: **Hanna Ferdynus - Operating Officer**
 
Sophomore, Finance and ACMS

hferdynu@nd.edu

I have always liked math and I would like to use it in my professional career. I'm hoping to connect my future with financial services and quantitative finance is one of the fields I find particularly attractive.

:small_orange_diamond: **Luke Distefano - Treasurer**

Junior, Economics and ACMS

ldistefa@nd.edu

Coming to Notre Dame, I was drawn to the application of mathematical methods to learn more about the economy. Previously, I worked in the Offices of Sustainability and Business Systems in South Dining Hall in order to find more efficient and sustainable initiatives for on-campus dining locations. Once I heard about the application of statistical analysis to investment strategies, I have been deeply engaged in becoming an expert as well as professional in the field.

:small_orange_diamond: **Peter Christie - Logistics Manager**

Sophomore, Business Analytics and ACMS

pchrist1@nd.edu

I have always been interested in the intersection math and statistics have with economics and markets, particularly as it has to do with data science. I hope to combine these passions into a career which allows for the opportunity to use data to drive performance.
