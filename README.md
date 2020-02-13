## What makes stand-up comedians stand-out from one another ?

### Introduction

What do the most famous stand-up comedians of recent time talk about the most ? What are their favorite topics in their routines ? Do they swear too much ?
In this project, we have used natural language processing to answer some of these questions. Here, I have started off by scraping the transcripts of some of the most highly rated routines of the comedians to doing topic modeling to identify what are the latent topics these comedians discuss in their most famous routines. The comedians that we are looking at here are listed below.

### List of comedians

1. Anthony Jeselnik	
2. Louis C.K.	
3. Jim Jefferies	
4. Bo Burnham	
5. John Mulaney	
6. Dave Chappelle	
7. Ali Wong	
8. Joe Rogan	
9. Mike Birbiglia	
10. Hasan Minhaj	
11. Bill Burr	
12. Ricky Gervais	

In order to find the most famous routines of these comedians, we looked at the LMDB ratings of their routines and picked the one that had the highest rating that were voted by atleast 2000 viewers.

![Capture](https://user-images.githubusercontent.com/54930611/74466989-e5a5e100-4e5d-11ea-8574-e7bb4f9a0235.PNG)

The next thing was to scrape the transcript for these routines and to do so, I did web scraping from https://scrapsfromtheloft.com/. 
