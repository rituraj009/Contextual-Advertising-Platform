# Contextual-Advertising-Platform
Django Project 2

## Description
1) Contextual advertising is a technology that finds our relevant ads from a given blog article to maximise a blog or websites revenue.
2) Contextual advertising is the reason why you see an ad for nike shoes on a fitness related article.
3) In this project I have build a contextual advertising platform which reads data from any blog who's URL we pass in, find relevant keywords on that blog and find ads which are relevant to them and all of this is done automatically.
3) First we create a basic Django app that could accept a blog URL, then read all the data on that blog page using the requests library and parse the data using BeautifulSoup.
4) We then feed the parsed data to the rake library which then finds the most relevant and prominent keywords in that blog article and save them.
5) These relevant keywords are then matched with the ads present in our database and gives us back the ads which are most relevant to the blog post.

## Technologies Used
1) Python : Programming language.
2) Django : For web app.
3) Requests: For making HTTP request to blog pages.
4) BeautifulSoup: To parse webpages
5) RakeNLTK : To find relevant keywords

## Installation
1) Python x.x < 3.9
2) Django 

```bash
  pip install django==3.2
```
3) requests 

```bash
  pip install requests
```
4) BeautifulSoup (beautifulsoup 4 is the lastest version)

```bash
  pip install beautifulsoup4
```
5) 
