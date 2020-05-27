---
layout: post
type: blog
title:  "The big themes in Pokémon openings"
date:   2020-05-27 12:25:00 +0200
categories: fun
summary: "If you've listened to the Pokémon openings, you must have noticed that they have a lot of similarity in their content, so I decided to try and do some Data Science with it"
preview: https://cdn.bulbagarden.net/upload/d/d9/OPJ01.png
author: nick
--- 

## Preamble
If you're a fan of Pokémon, and you've watched the anime, no matter your age, there is very few chances you've started with subbed anime, 
and since it was kind of the norm in the 90s when Pokémon appeared, the opening songs had an english version
(which were not even a translation of the japanese one in english but a full-on new melody and new lyrics and a new editing of the opening credits).
Other countries either had the english version, or the same music but with the lyrics translated to their language (my case in France).

So no matter where you come from, except if you're from Japan or have always watched it subbed, 
you should have heard the same things as me and come to the same realization : 
there are pretty recurrent themes in those openings.

I don't even know how it came to my mind when I haven't watched it in years but I challenged myself to verify it with visualization.
The lyrics were taken from [Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Pok%C3%A9mon_Theme) and the timings were recorded by myself.
Here we go

## The Analysis

### Season 1
{% include figure.html url="/pokemon-openings/season1.png" caption="Pokémon season 1 opening : Pokémon Theme" %}

#### Graph explanation
I'll take this first season to clarify the graph for you, for the next openings we will focus on the content.
So as you can see, I have divided the graph in four lines, which are the four big themes already laid out by this first opening. 

The first one, in blue, is reserved for the **Pokémon** word itself, since it is the most used word in the whole database : 60 occurences out of the 22 openings.

The second one, which ranges from Yellow to Red, is dedicated to everything that appeals to strength, as well as the terms used to designate "the best trainer".

The third one, in shades of green, is dedicated to the other themes of the Pokémon franchise (and important to the nekketsu genre in general) : friendship, courage, adventure, etc.

The Fourth one, in a range of pink to purple, denotates aspirations, destiny, and all big concepts like that.

The x-axis represents the seconds in the music where the words appear.

Note : You will probably notice in the legend some terms that are not used later, that is because I already show all the words I'll be using in the future.

#### A good start

So as I've mentioned, season 1 already lays out the big themes that we will find throughout the series and its openings, 
we can note that those lyrics start by "being the best" and mentions **Pokémon** quite late comparing to the ones that will follow; 
and they only add the two other big themes in the second half.

### Season 2
{% include figure.html url="/pokemon-openings/season2.png" caption="Pokémon season 2 opening : Pokémon world" %}

As you can see, the second season's opening is heavily focused on "being the master",
funny when you know that for 20 years it will be the only one where Ash actually becomes the champion.
And since the title is *Pokémon world* those words are repeated a lot,
 in fact it is the opening that has the highest count of **Pokémon**, with 11 occurences.

### Season 3
{% include figure.html url="/pokemon-openings/season3.png" caption="Pokémon season 3 opening : Pokémon Johto" %}

The third's season's opening was supposed to introduce a new Pokémon region, 
so it is more focused on its theme of "A whole new world", as it repeats it quite often, 
but it also repeats *Pokémon Johto* instead of just "Pokémon" like its predecessors.

It's the first opening to set a tendency that we will see a lot of in the future : the occurences of **Pokémon** are located at the beginning and the end, with few ones in the middle.

###  Season 4
{% include figure.html url="/pokemon-openings/season4.png" caption="Pokémon season 4 opening : Born to be a Winner" %}
Note : from here on the openings are 45s long instead of 60s

This opening starts with samples of the first one, but as you would expect from *Born to be a Winner*, 
it is even more focused on this theme than the other openings, 
so much so that it doesn't really let room for the rest.

### Season 5
{% include figure.html url="/pokemon-openings/season5.png" caption="Pokémon season 5 opening : Believe in Me" %}

Not much to say about this one : it is mostly about "The **path** to **victory**" and of course it hase the theme of its season *The **Master Quest***

### Season 6
{% include figure.html url="/pokemon-openings/season6.png" caption="Pokémon season 6 opening : I Wanna be a Hero" %}

Again, we have an opening that is supposed to introduce a new region, so of course the first line has "brand new **world**" in it.
But then it takes a very different approach from the third season : finding your way and becoming hero.

Note that it doesn't say **Pokémon** At the beginning, but it does mention Pallet Town.

### Season 7
{% include figure.html url="/pokemon-openings/season7.png" caption="Pokémon season 7 opening : This Dream" %}

This one I find very interesting, because we can see the second theme shift to a softer approach, 
it's not about being the best or winning anymore, it's more about the battles and the challenges themselves, 
and of course it's about *This Dream*

### Season 8
{% include figure.html url="/pokemon-openings/season8.png" caption="Pokémon season 8 opening : Unbeatable" %}

This graph is another one where the title (well not the title exactly, but the name of the season) has a great presence, 
but it's even more noticeable since the other themes almost have nothing, even if I wanted to put more points, 
they would be red to represent all the "unbeatable" and "undefeatable".

### Season 9
{% include figure.html url="/pokemon-openings/season9.png" caption="Pokémon season 9 opening : Battle Frontier" %}
Note : from here on the openings are 30s long instead of 45s, I changed the scale to be increase readability.

This high number of keywords is very surprising when you consider that it's the first opening to be that short, 
and moreover it is very diverse.

It might be worth noticing that it is the first opening that doesn't say **world**, 
which is funny when you know that it has been used in english by many countries that had had localized versions before .

### Season 10
{% include figure.html url="/pokemon-openings/season10.png" caption="Pokémon season 10 opening : Diamond and Pearl" %}

This one could not be more obvious : the first lines state "it's a brand new game, a brand new world" as its introduction to a new region.

There is a nice progression from "it's all about the **challenges**" &rarr; **battle** &rarr; **win** &rarr; **master**

### Season 11
{% include figure.html url="/pokemon-openings/season11.png" caption="Pokémon season 11 opening : We will be Heroes" %}

I don't have much to say about this one, it's very classical and diverse.


### Season 12
{% include figure.html url="/pokemon-openings/season12.png" caption="Pokémon season 12 opening : Battle Cry - (Stand Up!)" %}

Like n°10, there is kind of an escalation in the fighting, except there is no mention of the best anymore.

### Season 13
{% include figure.html url="/pokemon-openings/season13.png" caption="Pokémon season 13 opening : We Will Carry On!" %}

This one is super interesting because there is almost no mention of fight or power, 
(the only point in that category is from the season's name : Sinnoh League Victors, which I've made count as **Victory**)
This is a real shift in focus and the whole Unova arc (seasons 14, 15 & 16) will follow that new tendency 

### Season 14
{% include figure.html url="/pokemon-openings/season14.png" caption="Pokémon season 14 opening : Black and White" %}

As the season introducing the new region of Unova, this opening doesn't use the word **world** but it is mostly about choosing a **path**

### Season 15 & 16
{% include figure.html url="/pokemon-openings/season15.png" caption="Pokémon season 15 opening : Rival Destinies" %}
{% include figure.html url="/pokemon-openings/season16.png" caption="Pokémon season 16 opening : It's Always You and Me" %}

Nothing to add beyond the fact that those two follow the new tendency of focusing more on paths and friends than battle and masters

### Season 17
{% include figure.html url="/pokemon-openings/season17.png" caption="Pokémon season 17 opening : Pokémon Theme (XY Version)" %}
{% include figure.html url="/pokemon-openings/season1.png" caption="Pokémon season 1 opening : Pokémon Theme" %}

This one is very particular as it is a remix of the first one, so I'm putting the first one beside it to compare, 
and it is interesting to see that while its length has been divided by two, there is not a lot that is missing.

### Season 18
{% include figure.html url="/pokemon-openings/season18.png" caption="Pokémon season 18 opening : Be a Hero" %}

While this opening doesn't directly refer to season 6, 
it does start with "you're just a kid on a quest" when *I Wanna be a Hero* started with "A kid from Pallet Town", but it might just be me making strange correlation at this point.

Apart from that, we can notice that the lyrics have shifted back to a state closer to the first seasons, with more battle and fights.

### Season 19
{% include figure.html url="/pokemon-openings/season19.png" caption="Pokémon season 19 opening : Stand Tall" %}

Strange to see that this one doesn't seem to have anything in it, but really, it's very empty even with the full text, it has three sentences :

*I stand tall 'cause I know I'm a Winner
Knock me down, I'll just get up again
You've met your match, yeah, I'm no beginner*

And the rest is just ***Pokémon*** and *Gotta catch'em all*;
however, a very big thing to notice is the fact that ***Pokémon*** it doesn't end with are not the last words.

### Season 20 & 21
{% include figure.html url="/pokemon-openings/season20.png" caption="Pokémon season 20 opening : Under th Alolan Sun" %}
{% include figure.html url="/pokemon-openings/season21.png" caption="Pokémon season 21 opening : Under th Alolan Moon" %}

I'm putting these two side by side because... otherwise there's nothing much to say.
This emptyness is kinda interesting in itself though, 
it's not much about the battles anymore but it's not a lot about friendship either.

And I think it actually speaks about why people have criticized the Sun & Moon arc a lot 
(apart from its new art style which is a subjective preference).

In those lyrics, just like the anime itself, the theme is discovery,
it is made for people who don't know Pokémon and need to learn about it, just like the protagonists go to a Pokémon school.
And it shows that Game Freak knows that their old public have aged and don't watch the anime anymore, 
and now they have to renew their audience.

### Season 22
{% include figure.html url="/pokemon-openings/season22.png" caption="Pokémon season 22 opening : The challenge of Life" %}

And to follow what I just said, now that the audience is familiarized with the franchise, 
we can go back on track with the battles (or more precisely here the **challenge**)

## Conclusion
Well it was fun, and it certainly made me think about the evolution of the series.
I hope it was entertaining for you too. 

PS : I'll make a note (though a bit late) that I personally discovered Pokémon with the season 8 in French and I started to watch fansubs of the Japanese versions from season 12, stopped at 14, started back at 17.
If you felt in any way that I was biased towards those openings, that might be why.    
PPS : I'm sorry for all my colorblind friends, but I had to use a lot of colors so sometimes the shades are really close to each other

Thank you for reading this to the end, see you next time.