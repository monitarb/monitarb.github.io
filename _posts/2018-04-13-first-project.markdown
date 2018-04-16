---
layout: post
title:  "My First Project"
img: heatmap.png
date:   2018-04-13 00:00:00 +0200
description: So first week’s gone.  Like I said, this is an assisted information injection.  Project #1 is in groups of 4 people (The only one, other projects will be independent) and it was about analyzing real MTA data to get the optimal positions to distribute invitations for a fundraising event for a made-up Women Tech organization.
---

So first week’s gone and like I said, this is an **assisted information injection**.

Project #1 is in groups of 4 people (The only one, other projects will be **independent**) and it was about analyzing **real** MTA data to get the optimal locations to distribute invitations for a fundraising event for a made-up Women Tech organization.
So it was **pretty cool** to clean and analyze, not only the **real** available turnstile data from MTA (Read again: **REAL!!!**), but play with demographics (Women, Working in tech, Willing to contribute, …), locations (Near MTA, near Universities or Tech Hubs, …), and **anything you could come up to** with the tools you were learning in the mornings.

Just in one week we covered:
- Git: 

The repository tool for developers.  I had already worked with it during my last job, so I had the **basics** covered. 
The bootcamp was based on [Atom](https://atom.io), a GUI for Git, but personally I like **command line** better.  Here's a very useful [cheatsheet](http://www.ndpsoftware.com/git-cheatsheet.html) 
These are the basics:
```bash
git status  # Will show you the current files you’ve modified compared to the ones in the master branch
git add <filename>  # Or git add . Will add ALL files listed in red
git commit -m ‘this is my comment’
git push my_branch master # Or just git push if you have the defaults configured
```
- Python/Pandas: 

I had also worked with Python before, so I got the algorithmic and code syntax’s covered.  The new thing for me was the mix with Pandas.  I found these two pages really useful as a starting point:

> - [Things in Pandas I Wish I'd known sooner](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb?utm_source=Python+Weekly+Newsletter&utm_campaign=8416b188e6-Python_Weekly_Issue_176_January_29_2015&utm_medium=email&utm_term=0_9e26887fc5-8416b188e6-312716773#Selecting-NaN-Rows)

> - [10 Minutes to Pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)

Long story short, it's an easy way to read files, treat them as "tables" (called **DataFrames**).  If you are familiar with tables and SQL, you'll get the hang of it very fast

- Matplotlib/Seaborn: These are two basic graphic libraries on Python that can be very useful.  You can make bar charts, histograms, heatmaps, Scatterplots.  Here I learned that I love **heatmaps**.  In here we discovered different **cool tips** like function [cut](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.cut.html) to split your data into given bins (In our case, by time of day), or how to play with **pretty** color palettes on [seaborn](http://jose-coto.com/styling-with-seaborn)

- Folium: When we finally got the analysis done, which stations to aim, on which time frames, we plotted everything in a cool map showing: Recommended stations and traffic ratio along with each location's census data and income per-capita information.  All this was able using the [Folium](http://folium.readthedocs.io/en/latest/) library, You should give it a look!

## Issues
- Bootcamp was recommended in **Mac or Linux OS** and I'm more comfortable, or should I say **less incomfortable**, with Linux.  So I got my new computer, got Linux installed, did all my prework on it... and on **Day 1**: Something happened with the WiFi.  **You can't do this bootcamp without Internet**.  We are doing research and git requests daily.  I think it was something physical with my network driver, so I had to go and get a Mac book on Day 1.

> **This doesn't mean that Linux is a "no"**.  actually, two people from this Bootcamp are using it without issues.  One of them tried to help me, but again, it was something of **my computer**, not the OS.

- Working this first project in groups can be **tricky**, you have so little time (**4 days**) to get to know and work with people you don't know, from different backgrounds and different ideas, so you'll be **brainstorming and discussing** continuously.

## Lessons Learned
- I definitely love **heatmaps!***  There's so much you can do with them, even plot real location maps, play with the colors...  You get a very pretty **3 variable** analysis

- **Collaborating**.  The thing about Bootcamps it's there's not much people and not much time, so we all have to help each other.  Some of the functions and problems in our proyect were easily solved by other classmates or TAs.  **Everyone's willing to help!**

- **Writting this blog!**  Thinking on collaborating, not only my classmates but everyone out there, I will be making continuous updates to it.  Adding posts on Data Science tips, things I learned and the whole **Bootcamp experience**.  I have used several blogs in **just one week** that are very useful and am **very grateful** to the people writting them, so I think I'll follow their steps!
