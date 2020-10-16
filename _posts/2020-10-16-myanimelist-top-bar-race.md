---
layout: post
type: blog
title:  "MyAnimeList Top Anime the last ~14 years"
date:   2020-10-16 23:55:00 +0300
categories: fun
summary: "Animated race bar charts to visualize MyAnimeList's Top Anime over time"
preview: https://myanimelist.net/images/mal-logo-xsmall@2x.png?v=180226001
author: nick
--- 

## Introduction
Boy this work was a lot of fun, I've been seeing a lot of "Race charts", and have been wanting to get a go at it myself but couldn't find the right subject.

Recently I was talking with a friend about how the same Animes have held the top spaces of MyAnimeList's chart for years, and the iea came to me that it would be the perfect occasion to try one of those race charts

## Data Retrieval
Of course, MyAnimeList doesn't keep every anime's score over time in its API, 
so I thought of using [The Wayback Machine](https://web.archive.org/), at first I was gonna navigate in it and do some live web scraping but thankfully, 
[hartator](https://github.com/hartator/) had already developed [a downloading tool](https://github.com/hartator/wayback-machine-downloader) to help me do that, as parsing the source code of the pages would be faster.

Did you know that MyAnimeList's top page has changed a lot over the years ? 
There were 2 or 3 major style changes, but a total of 10 changes that impacted the data I was trying to extract.

## The Animations
To create the charts, I used Flourish, the most accessible platform to do this currently (and only one I could find actually).   
I divided the animation in three, because the Wayback Machine had two major points where it increased significantly the frequency of its MyAnimeList snapshots, 
meaning more data towards the end, and since Flourish's animations have a set speed, it glossed over the first years to fast or was too slow at the end.

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/4040403" data-url="https://flo.uri.sh/visualisation/4040403/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/4040536" data-url="https://flo.uri.sh/visualisation/4040536/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/4040543" data-url="https://flo.uri.sh/visualisation/4040543/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Thank you for reading, hope you enjoyed your time with these kinda hypnotic visualisations.