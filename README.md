# Contextual-Advertising-Platform
Django Project 2

## Description
1) Contextual advertising is a technology that finds our relevant ads from a given blog article to maximise a blog or websites revenue.
2) Contextual advertising is the reason why you see an ad for nike shoes on a fitness related article.
3) In this project I have build a contextual advertising platform which reads data from any blog who's URL we pass in, find relevant keywords on that blog and find ads which are relevant to them and all of this is done automatically.
3) First we create a basic Django app that could accept a blog URL, then read all the data on that blog page using the requests library and parse the data using BeautifulSoup.
4) We then feed the parsed data to the rake library which then finds the most relevant and prominent keywords in that blog article and save them.
5) These relevant keywords are then matched with the ads present in our database and gives us back the ads which are most relevant to the blog post.
6) Also using Tailwind to style up the web app.

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
3) requests (Python library for making HTTP requests)

```bash
  pip install requests
```
4) BeautifulSoup (Python library for for extracting data from HTML and XML documents. beautifulsoup 4 is the lastest version)

```bash
  pip install beautifulsoup4
```
5) RAKE --Rapid Automatic Keyword Extraction (Its is an NLP tool), RAKE is implemented in the Python Natural Language Toolkit (NLTK) library. 

```bash
  pip install rake-nltk
```
6) Node.js (In order to set-up and install Tailwind), NPM for tailwind
--> a) https://nodejs.org/en/  (download the LTS version), after installsation check if it is installed by running command (node --version)
--> b) tailwind 

```bash
  npm install tailwindcss@2.2.16
```

## SCREENSHOTS

1) Homepage  
![image](https://user-images.githubusercontent.com/102078863/209398280-f8fb4bbf-5784-4476-9b98-50abebaec2e4.png)


2) Providing a link for demo and clicking on sumbit.
![image](https://user-images.githubusercontent.com/102078863/209398332-b82224ca-17e8-4c9b-852f-280a8222cd61.png)


3) Relevant keywords are then matched with the ads present in our database and gives us back the ads which are most relevant to the blog post.  
![screencapture-127-0-0-1-8000-2022-12-24-01_00_40](https://user-images.githubusercontent.com/102078863/209398397-7ff0f61d-6b1d-4599-9aca-f5ba0082ea2a.png)






