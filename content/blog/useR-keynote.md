---
title: "Keynote at the useR! conference — followup Q&A"
author: Julie Lowndes
date: '2019-08-20'
slug: keynote-useR
categories:
  - community
tags:
  - impact
banner: img/blog/keynote/user-keynote-titleslide.png
---

*Last month I gave the opening keynote at the useR! Conference. *

*For more details on Openscapes see [blog by Mozilla](https://medium.com/read-write-participate/open-science-and-star-wars-2577b8081e8f)*.

---

useR! is an annual international conference for innovators around the R programming language, which are called useRs. The conference in Toulouse was the ... Learn more about it here. 

Thank you for the invitation. 

This is a condensed summary of my talk, with [full slides available](), along with a [video]() of the presentation live in Toulouse. 


---

<br>

<center>
  <a><img src="/img/blog/keynote/user-keynote-titleslide.png" width="500px"></a>
  <figcaption>art: [@allison_horst](https://twitter.com/allison_horst)</figcaption>
</center>

<br>


There were great questions from the audience, and I liked the conference's use of Sli.do so that people could write their questions during my talk and vote on other people's so that we could answer the questions that multiple people had. I didn't get a chance to respond to all of these questions during the conference Q&A, and some I feel like I didn't respond to fully in the moment due to the adreneline from having completed the talk. So here I will comment on a few more of the questions that conference attendees had. 

Grouped and organized a bit based on my responses. 


## Mindset and skillset

#### You have a lot of focus on tool choice as a path to open science. Do you think that scientists who struggle are held back mostly by tools or some other factor?

--> mindset and skills. 

#### With every PhD student generation, do you feel that it becomes easier to convince them to engage in Open Science? Or is there recurring resistance?

The new generation of scientists are much more willing to engage in open science. They have grown up sharing (Instagram, Twitter, GoogleDocs), and they help bring the idea of sharing openly to the scientific community. 

There is great opportunity for open practices to not only accelerate and amplify collaboration and scientific discoveries, but be valued, rewarded, and help favor team science. And this is important because individual scientists cannot do it all (research, publications, mentorship, teaching, travel, committees, communication, grant writing, etc., and now open data science?), nor should they be expected to. Moving forward, the workload and credit should be more distributed. If we had a culture where open data science was valued, collaboration was fueled by the open web, credit was transparent, and researchers worked on projects as a team – as we do with the Ocean Health Index –  then we could find environmental solutions we have yet to imagine – and elevate everyone in the process.

#### What are some of the big data challenges for marine data? For example, is comprehensive data collection an issue? Is coordinating data resources from diff gps?

## Incremental improvement

#### It is a big "what if", but still. What if your boss would *not* have been that supportive?

--> I honestly think that the project would no longer exist. A project combining and modeling one hundred datasets cannot could not continue on an annual timeline with folks forwarding hand-crafted excel files to each other. 

bookkeeping. 
and with limited time and resources, we could not afford to hire someone else or waste time 

#### How did u convince ur boss to have believe in something he didn't have knowledge about?

It was a combination of trust, demonstrating value in ways that he cared about, and absolute necessity. In terms of trust, he already gave us independence in our tasks, valued our judgment, and welcomed feedback. This had been established within the team for months to years, so it was a collaborative environment before we even began talking about open data science. We demonstrated value in ways that he cared about: we showed him that R and GitHub would save time. And it would not be immediate; it might take us 2 days to do something that we could produce in Excel in a half a day — but it will take just an hour next week and the week after that. We demonstrated how nimble we were to rerun analyses with small changes to parameters or subsets of data, and that these skills would be valuable not only for the current project but for projects to come. And, it was due to absolute necessity. We needed a better way to work: it was not sustainable to have to waste so much time doing forensics in our emails and files to try to figure out what we had done and why in order to advance our analyses. To be dramatic, it was like accepting that candles and torches were not enough anymore and that we needed to wire our house for electricity. It meant overcoming inertia and the time it takes for changing this infrastructure, but it means that we can be more efficient in the long run. 


#### how can you keep the balance between sharing and open data and protecting the data while working in a private company?

- What about barriers to adoption? E.g. "I worked hard to get this data, why should I share it? I need the publications from it"


#### Do we need open DATA science? Isn't open science enough?

#### How to use twitter effectively to improve our skills and share our experience?

#### As a marine scientist how do we get involved in openscapes?

#### How about Open Data Science to help communicate and to engage with the general public ? Could Open Citizen Science be part of your Open Data Science landscape ?

## Teaching

#### How should data science and statistics be taught at University to students within you field of study?

#### What makes R a good choice to learn for others without a computing background who want to analyze data?

#### In the training you provide, would you rely on R as how it is in its R-base shape or would you prefer a restricted approach such as tidyverse type use of R?

#### Are you noticing positive (measurable) effects of decreasing gender imbalance in Open Source dev? Have the Rladies and similar taken off?

## Original Talk script



I am a marine scientist and R as a language and as a community has been game-changing for my science, and my life. 

So much so that over the past six years I have been moving away from doing my own research so I can pay forward what I've learned and focus on enabling other scientists to better science in less time, together. 

Throughout this I've learned several lessons, and I want to share them up front: 

---
class: inverse
# Lessons learned 
<br>

### Open data science is a mindset
### Teamwork starts with openness 
### Harness the power of welcome

???

The 3 lessons are Open data science is a mindset, Teamwork starts with openness, and Harness the power of welcome.  

I'm going to spend the whole talk building out these lessons.

But first I wanted to tell a bit about me and the main experiences that have driven these lessons. 

I am often asked why a marine scientist would use R, so I want to make sure you leave here knowing that marine scientists, as well as environmental scientist more broadly, work with data every single day to do our science, and it is critical that we are supported to work with data responsibly. 

So let me start off when I was a graduate student in a marine research group, which we also call laboratories in the US. 

---
## @juliesquid
```{r sq-tag2, out.width = '40%', fig.align='center'}
knitr::include_graphics("img/*JulieReleaseAugerIMG_9311-crop.png")
# *JulieReleaseAugerIMG_9397.jpg # release to water
# *IMG_9268.JPG # measure
```

.footnote[
photo: Greg Auger 
]

???

I am actually a squid ecologist, which is why many of you know me as juliesquid. 

That is me on the right, holding a squid that can be nearly as big as I am. 

We caught it and I am releasing it alive back into the ocean with a little electronic tag on it. The tag turns this squid little oceanographer, because it will collect data about it environment as it swims through the ocean. i collected data every second, which means I could actually see the squid breathe, since its breathing and movement are coupled through jet propulsion. 

My whole PhD research group focused on squid. We were interested because squid have huge impact on ecosystems since they eat a lot and grow quickly and they also have huge impact on economies because globally there is such high consumption of calamari. In our lab some focused on ecology like me, others on locomotion, camouflage, or early life development. 

---

<br>

.pull-left[
```{r fieldwork, out.width = '80%', fig.align='center'}
knitr::include_graphics("img/sq-ctd-fieldwork.JPG")  
```
]

.pull-right[
<br>
<br>
```{r fieldwork2, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/DannaJulieAshleyNOAA.JPG") 
```
]

.footnote[
web: [Gilly Lab](https://gillylab.stanford.edu/)
]

???

Our research required a lot of teamwork, both at sea and in the laboratory. 

We were a typical research group because we worked like a team about our scientific questions. 

We were also a typical research group because we didn't act like a team when it came to data. Analyzing data was something that was left to each of us to figure out as individuals.  

In in all my education I had never learned computing or how to work responsibly with data. So for me it was a super demoralizing experience to get the tag back and actually hold data in my hand but not be able to analyze it.

transition: It felt like this. 

---
```{r luke}
```
class: center, middle
background-image: url(img/blog/keynote/horst-starwars-luke.png)
background-size: contain

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst)
]

???

This is Luke Skywalker after he crashed his plane in the swamp on Degobah. 

He cannot solve the the challenge in front of him with the skillsets he has. 

He is demoralized and alone. And if you imagine him attempting to use whatever pulleys and ropes he might have with him, you know it wouldn't be pretty, it wouldn't be reproducible, and it probably wouldn't get him where he needs to be on time. 

transition: but luckily what happens next is that he meets Yoda

---

```{r yoda, out.width = '88%'}
knitr::include_graphics("/img/blog/keynote/horst-starwars-yoda.png") 
```

<br>

<center>
  <a><img src="/img/blog/keynote/horst-starwars-yoda.png" width="500px"></a>
  <figcaption>art: [@allison_horst](https://twitter.com/allison_horst)</figcaption>
</center>

<br>



???

Yoda uses the Force to solve Luke's problem in a way Luke never imagined was possible. 
 
This is going to open up Luke's whole world because he can learn from Yoda and not only solve his current but it will broaden his mind to what is possible in the future. 

transition: But Luke didn't go on to defeat the Empire himself, he had a whole community.

---
```{r hands} 
```
class: center, middle
background-image: url(img/horst-starwars-hands.png)  
background-size: contain


.footnote[
art: [@allison_horst](https://twitter.com/allison_horst)
]

???

And this community is powerful because of the diversity of backgrounds and expertise, and although not everyone is a Jedi, everyone contributes in really critical ways. 

transition: So just to recap, 

---
```{r rey}
```
class: center, middle
background-image: url(img/horst-starwars-rey.png) 
background-size: contain

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst)
]

???

R is the Force that enables us as scientists to do better science in less time. 

It empowers us to get our own data out of the swamp. 

It empowers us and build off of our confidence and experiences and broaden the scope of scientific challenges that we can tackle, which for environmental scientists, includes food security, disease transmission, and climate change. 

For me, I didn't fully feel the power of R until I finished graduate school and joined a research group where I am today, where we learned to work with data as a team. 

---
```{r OHI hex, out.width = '55%', fig.align='center'}
knitr::include_graphics("img/OHI-hex.png")
```

.footnote[
web: [ohi-science.org](http://ohi-science.org); [@OHIscience](https://twitter.com/OHIscience)
]

???

The Ocean Health Index is a scientific endeavor to quantify impacts and benefits of oceans around the world using the best publically available data. 

It is being used by the United Nations and by 20 groups around the world. 

There is a lot to it but what is relevant here is that we combine lots of data, we repeat our analyses every year, and we do it as a team.

But we are marine scientists, and we were never trained to work responsibly with data. 

So we found out the hard way that our default approaches were not reproducible by even ourselves. 

Getting through this involved quite a reckoning, but when we got through it, we knew we had a story to tell. 

---
class: middle, center
```{r nature-bsilt, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/nature-screenshot-title.png")
```

.footnote[
source: [Lowndes *et al.* 2017](https://www.nature.com/articles/s41559-017-0160); web: [ohi-science.org/betterscienceinlesstime](http://ohi-science.org/betterscienceinlesstime/)
]

???

We found our path to better science in less time with open data science tools. 

And by this I mean R and GitHub and friends. 

transition: We shared how these tools enabled us to more reproducible science faster each year, as we illustrated in this figure

---
class: middle, center
```{r fig 1-whiteout, out.width = '80%'}
knitr::include_graphics("img/bsilt-fig1-nature-whiteout.jpg")
# lowndes-nature-figure1-slides2.png
# https://docs.google.com/drawings/d/1d25T1fD9irluhQhPvNHZSt3uUBXebxqV9hFabOLZUz4/edit
```

.footnote[
source: [Lowndes *et al.* 2017](https://www.nature.com/articles/s41559-017-0160)
]

???

Shown here as the circles get smaller and moving up the y axis. It also go easier for us to collaborate each year, along the x axis. 

This let us focus on making improvements either on the data science side or the science side

---
class: middle, center
```{r fig 1, out.width = '80%'}
knitr::include_graphics("img/bsilt-fig1-nature.jpg")
# lowndes-nature-figure1-slides2.png
# https://docs.google.com/drawings/d/1d25T1fD9irluhQhPvNHZSt3uUBXebxqV9hFabOLZUz4/edit
```

.footnote[
source: [Lowndes *et al.* 2017](https://www.nature.com/articles/s41559-017-0160)
]


???

We couldn't overhaul everything all at once, but focused on different pieces incrementally each year. 

We started off focused on R and RStudio, and then on using Git and GitHub, then on tidy data and then documentation and Rmd. And ever since we've focused on leading a training program to teach students how to maintain it. 

Having all of this coding infrastructure in place is what enables those 20 independent groups I mentioned to study ocean health in the places they care about. 

But just like Luke, we were able to do this because of community. 

---
class: center, middle
```{r community-logos, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/ods-community-logos.png")
```

???

These communities in particular have been so transformative for our work. 

So many of you in this room and listening around the world have welcomed us and supported us and enabled us. 

And like I said, I've been paying it forward by teaching with the Carpentries and leading local communities —

---
# Eco-Data-Science & RLadies SB

```{r eds, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/eds-rladies-hex.png")  
```
 
.footnote[
art: [@allison_horst](https://twitter.com/allison_horst); twitter: [@ecodatasci](https://twitter.com/ecodatasci); [@RLadiesSB](https://twitter.com/RLadiesSB)
]

???

leading local study groups like Eco-Data-Science and RLadies chapters, and generally telling everybody how awesome R is. 

This is how I got a fellowship with Mozilla. 

---
class: center, middle

```{r moz, out.width = '100%'}
knitr::include_graphics("img/moz-fellow-announcement.png")
```

.footnote[
blog: [blog.mozilla.org](https://blog.mozilla.org/blog/2018/08/21/mozilla-announces-25-new-fellows-in-openness-science-and-tech-policy/)
]

???

Yes Moz is firefox, but also the internet for good. 

Spent the last year developing a program with Mozilla and NCEAS, the ecology center where I am based. 

---
```{r openscapes hex, out.width = '55%', fig.align='center'}
knitr::include_graphics("img/openscapes-hex.png")
```

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst); 
web: [openscapes.org](https://openscapes.org); [@openscapes](https://twitter.com/openscapes)
]

???

The program is called Openscapes, and it is mentorship program for research groups. 

Openscapes helps them establish and maintain shared practices around data and work as a team. 

It is modeled after our experiences from the Ocean Health Index, which is one of the most visible examples of what open data science can look like in an environmental context. 


---
<br>
```{r openscapes grassland, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/horst_openscapes_grassland_1500px-text.png")
```

<br>

.pull-left[
### Welcome and empower scientists as labs
]

.pull-right[
### Increase visibility and value by amplifying labs
]


.footnote[
art: [@allison_horst](https://twitter.com/allison_horst); 
web: [openscapes.org](https://openscapes.org)
]

???

welcome and empower scientists as research groups

increase visibility and valuee by amplifying labs and creating more examples of how powerful open data science can be for environmental science

---
<br>
```{r openscapes desert, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/horst_openscapes_desert_1500px.png")
```

.pull-left[
### Mentorship program for early career scientists & their labs
]

.pull-right[
### Normalize open data science in the lab & seed change beyond
]

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst);
web: [openscapes.org/champions](https://openscapes.org/champions)
]

???

Centered mentorship program for early career scientists & their labs

Normalize open data science in the lab & seed change beyond

---
```{r env-r4ds}
```
class: center, middle
background-image: url(img/horst-eco-r4ds.png) 
background-size: contain

.footnote[
.left[
art: [@allison_horst](https://twitter.com/allison_horst); 
updated from [Wickham & Grolemund](https://r4ds.had.co.nz/)
]
]

???

This is the vision I see for environmental science. 

Where the elements that environmental scientsts are great at, like theory, and experimental design are streeamlined together by ODS, and help us communicate around environmental solutions. 

I know this graphic looks familiar from R4DS, but notice that all of the data science components here are ringed by communities and support that our OHI team has found so critical to our success. 

So this is the vision I'm working towards with Openscapes, and I am optimistic we can do this because the first cohort of Openscapes participants are well on their way after only 5 months.

---
```{r env-comm}
```
class: center, middle
background-image: url(img/horst-eco-r4ds-env-comm-only.png) 
background-size: contain

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst)
]

???

But right now environmental science looks like this. We rarely have formal training with coding or computing or data and so folks learn in pockets and are unsupported at broader institutional levels. 

And often they are not supported even at level of the research group, which is already poised to work like a team. 

Helping complete this picture drives my work now. I want to figure out how to best introduce open data science and teamwork to this picture.

I've found that scientists are often not aware of what tools are availabe. But that is just the first sliver of the challenge. 

The real challenge is about mindset around open data science, and helping scientists feel included so that it can be part not only of their future, but of their present. 

---
class: inverse
# Lessons learned
<br>

### Open data science is a mindset
### Teamwork starts with openness 
### Harness the power of welcome 

???

<water>

So the first is that open data science is a mindset. 

---
class: inverse, center, middle
# Open data science is a mindset

### expect a better way • build confidence & willingness • reimagine science communication

???

<br>

This involves expecting there is a better way with data science, 

Building confidence & willingness with open science, 

and reimagining what is possible with the available tools. 

---
class: middle, center
# Expect there is a better way

???

It can be really hard to expect that there is a better way to do something when you do not know what is possible and you don't see any examples within your own context. 

It's like how Luke would have never expected the Force to have been a thing if he hadn't run into ObiWan and Yoda. 

When I struggled with my squid data, I couldn't expect there was a better way because I thought my challenges with column renaming was a part of my squid research, not something separate like data wrangling. 

So this mindset drained weeks of my time, because I didn't have the mindset or the vocabulary to articulate my struggles and ask for help. 

transition: so when I talk about data science with Openscapes — 
---
```{r data-science}
```
.whisper[Data science] 

???

I make it clear that it is not just about big data, machine learning, and artifical intelligence, which is basically all you ever hear about in the news. 

I think this narrow definition really excludes scientists, who then feel that data science tools are not meant for them. 

transition: I like this definition: 

---
```{r data-science}
```
.whisper[Data science is the discipline of turning raw data into understanding] 
  
<br>

```{r data-science-r4ds, out.width = '90%', fig.align='center'}
knitr::include_graphics("img/r4ds_data-science.png")
```
  
.footnote[
source: [Wickham & Grolemund](https://r4ds.had.co.nz/)
]  

???

This definition resonates with me because I can see myself included in it — and then with the graphic I can actually walk through the steps. 

This clearly describes what many scientist like me I have been fumbling around trying to every time from scratch. 

The idea of tidying your data first and then being streamlined with the tools you can use for science is amazing. Rather than accommodating around weird data.

transition So expecting there is a better way is a big part of a shifting mindset towards open data science. And along with it comes

---
class: middle, center
# Build confidence & willingness

???

Building confidence & willingness to engage in a completely different way to work. 

Open science is a big part of this confidence and willingness to engage. 

transition: but Open science has many different definitions and even more interpretations. 

---
```{r open-science}
```
.whisper[Open science]

???

For many environmental scientists, open science can be a negative thing. It's seen as extra work and high risk on already overburdened scientists, particularly those who are early career. 

And that is because it often also has a narrow definition of sharing your data and code at the end of your study, at the risk of people stealing your work and misconstuing your science. 

In this narrow mindset it's not considered that open science could ever be a benefit to the scientist who pays such cost in terms of time and risk.

transition: So in Openscapes, we talk about open science with this definition: 

---
```{r open-science}
```
.whisper[Open science is the concept of transparency at all stages of the research process, coupled with free and open access to data, code, and papers]

```{r spectrum, out.width = '90%', fig.align='center'}
knitr::include_graphics("img/spectrum-haha.png")
```

.footnote[
source: [Hampton et al. 2015](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/ES14-00402.1)
]

???

I like this definition of open science

I teach that open science is a spectrum, with many entryways to engage

I like this too because it helps dispell the idea that you're either doing open science or you're not, but that you can always engage more as you are able.

In Openscapes we talk about how entryways can include sharing slides from a talk online. 

We also practice working openly with their own teams, even if it is within a private repository, because it is practicing the tools and taking the first steps. 

transition: and these 2 pieces really trigger you to reimagine what data science and open science can do for communication

---
class: center, middle
# Reimagine science communication

???

In environmental science, communication is something we really value. 

We are very similar to the open source community like R and Moz in that all of our work is for the public good, and thus communication about it is critical

transition: But For a lot of people, science communication still largely occurs at the end of a study, when everything is complete. 

---
.whisper[Communication tools]

???

And I think this mindset is rooted in the fact that for a long time, sharing your work was hard to do. 

It involved a lot of bookkeeping and formatting and physically printing in many cases, and then distribution was also limited to mail, either phyical or electronic. 

But the internet provides amazing channels to share our work not only at the end, but throughout all of the process. This is critical to establish trust and action for environmental solutions. 

---
.whisper[Communication tools]

```{r ods-software, out.width = '65%', fig.align='center'}
knitr::include_graphics("img/screenshot-paur-talk-ods.png") 
```

.footnote[
source: [OHI slides](https://docs.google.com/presentation/d/12m8dUpIOz16x1RlZWLtj9u5E9wMxtYuP0T_HxoDnyKw/edit?usp=sharing)
]

???

So these are the communication tools I use for open data science — it is a small suite, primarily based with R, RStudio, Git, and GitHub. 

And keeping it so simple really streamlines how manageable it is to focus on science communication, because we use the exact same tools for analysis.

I may as well also say that I can be a big curmudgen about introducing extra software into my life and having to create new user accounts. 

I remember in one NSSD episode, Roger Peng said that if he has to create a new user account, he's like 50% out. For me it's like 80%. 

But anyways, these tools have reimagined what communication means, and I'll show you a few examples from the OHI. 

<next go quickly>

---
exclude: TRUE
class: center, middle
```{r global-map, out.width = '100%'}
knitr::include_graphics("img/global_map_Index_2018_mol.png")
```

.footnote[
source: [ohi-science.org/ohi-global](http://ohi-science.org/ohi-global/)
]

???

We create ocean health index maps like these, in R, with scores reflecting how healthy oceans are for every coastal country around the world. and making these every year by modeling almost 100 data sets forces documentation and decision making to be part of science communication. 

---
class: center, middle
```{r ohi-science-github, out.width = '100%'}
knitr::include_graphics("img/github-ohi-science.png") 
```

.footnote[
web: [github.com/ohi-science](https://github.com/ohi-science)
]

???

We put all of our code online, pubically, in a GitHub organization for the OHI. This means that others can discover, access, and run our code, understanding what we've done and doing assessments of their own. 

But GitHub repositories are not a friendly landing page for everyone. So —

---
class: center, middle
```{r ohi-science-homepage, out.width = '100%'}
knitr::include_graphics("img/ohi-science-homepage.png") 
```

.footnote[
web (Jekyll): [ohi-science.org](http://ohi-science.org)
]

???

So we built a website that we can maintain ourselves. And here we can put addition information and tutorials and blogs. 

---
class: center, middle
```{r rmd-global-web, out.width = '80%', fig.align='center'}
knitr::include_graphics("img/web-rmd-global.png")
```

.footnote[
web (simple RMarkdown): [ohi-science.org/ohi-global](http://ohi-science.org/ohi-global)
]

???

We also can spin up lighter-weight websites that will render with the most recent information we have 

This is not only useful for us, but for our colleagues leading their own assessments on their coastlines. 

---
```{r ohi-esw, out.width = '80%', fig.align='center'}
knitr::include_graphics("img/ohi-esw-web.png") 
```

.footnote[
web (simple RMarkdown): [ohi-science.org/esw](http://ohi-science.org/esw)
]

???
Another way science communication has changed is that  

---
class: center, middle
```{r toolbox-training, out.width = '80%'}
knitr::include_graphics("img/ohi-toolbox-training.png")
```

.footnote[
web: [ohi-science.org/toolbox-training](http://ohi-science.org/toolbox-training/)
]

???

We can create really nicely formatted guides and documentation also using these same tools. 

---
<br>
```{r shiny-ne, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/jafflerbach-shiny-ne.png") 
```

.footnote[
dashboard (Shiny): [@jafflerbach](https://twitter.com/jafflerbach), work in progress. 
inspiration: [Imagine Boston](https://analytics.boston.gov/app/imagine-boston) 
]

???

And when we are working closely with partners who are engaged with data analysis decisions, we have been able to create dashboards as well. 

---
<br>
```{r openscapes-web, out.width = '80%', fig.align='center'}
knitr::include_graphics("img/web-blogdown-openscapes.png") 
```

.footnote[
web (blogdown): [openscapes.org](https://openscapes.org)
]

???

Additionally, these tools have been amazing for blogging and sharing Openscapes stories

---
<br>
```{r user-xaringan, out.width = '80%', fig.align='center'}
knitr::include_graphics("img/user-keynote-titleslide.png") 
```

.footnote[
slides (xaringan): [jules32.github.io/useR-2019-keynote](https://jules32.github.io/useR-2019-keynote)
]

???

And for fun, for creating talks at useR

transition: 

---
```{r r4ds-env-reprise}
```
class: center, middle
background-image: url(img/horst-eco-r4ds.png) 
background-size: contain

.footnote[
.left[
<br>
art: [@allison_horst](https://twitter.com/allison_horst);
updated from [Wickham & Grolemund](https://r4ds.had.co.nz/)
]
]

???

So open data science as a mindset is the framing that we start with in Openscapes. 

But the way we actually start acting on all of this is through teamwork, which starts with openness.

---
class: inverse, center, middle
# Teamwork starts with openness
### working openly • vertical & horizontal leadership • community

???

--water

Teams to me mean rings of people you respect, innovate with, and can rely upon. It does not have to be limited to a certain deliverable, location, discipline or anything else really. 

Teamwork is critical in science because no one it can do it all. And for the sake for innovation as well as for emotional well-being we need to shed the expectation that we should be able to. Instead, we need to value teamwork. 

So I've categorized teamwork here but there are definitely a lot of blurred lines. 

But actually one of the coolest things to me throughout everything I've learned is how teamwork and collaboration and leadership and community all intertwine when you work openly. 


---
class: center, middle
# Working openly

???

Open data science streamlines working with data but also working with each other. 

Shared workflows like tidyverse and GitHub mean that even when you aren't working on the same project or interest, you have the same skills and are equipped to help each other out. 

As an OHI team, these tools let us co-develop things, share early drafts, and we can constantly giving feedback and iterating with each other. 

transition: But working openly is something you have to feel safe doing. 

---
# Ocean Health Index team
 
```{r team, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/ohi-team-2018b-crop.jpeg") 
```

???

We as an OHI team have spent years building up trust with each other, and that makes us be able to do our best work. 

This trust really centers on respect for each other and also kindness.

But on an individual level, we all have had to get comfortable with sharing things before they are perfect and being vulnerable to critique, which gets easier when you can assume the best intentions from anyone's feedback. 

But this has resulted in a really positive team culture, where we are comfortable with trying new things & learning from failure, and we are comfortable asking for help. 

---
# Ocean Health Index team
 
```{r team2, out.width = '90%', fig.align='center'}
knitr::include_graphics("img/ohi-team-2019-crop.jpg") 
```

???

Another thing about our team is that we prioritize social time, obviously, since it is impossible to find a picture of our team that is not at happy hour. 

But seriously, getting along well together builds resilience into our team and has helped avoid burnout. And it helps us us manage as people come and go into our group, as is common in science.

transition: one of the ways to start working on this as a team is to create safe spaces where you can deliberately talk about shared stuff.

And in Openscapes, that's what we do in our cohort calls. 

---
# Openscapes Cohorts
```{r zoom, out.width = '70%', fig.align='center'}
knitr::include_graphics("img/Cohort1_zoom.png") 
```

.footnote[
blog: [openscapes.org](https://www.openscapes.org/blog/2019/01/28/introducing-champions-program/)
]

???

This is the first cohort from Openscapes! 

These are scientists from 7 labs, with the faculty or lecturers of each lab participating along with their lab members, who are graduate students, postdocs, technicians, lab managers, visiting faculty. 

We all meet twice each month to discuss open data science concepts and to build community. 

In our calls, I try to model the behavior I want to see, so that they can bring it to their labs. We start off every meeting with a Code of Conduct. 

transition: I said that what I teach in Openscapes is modeled after OHI —

---
class: center, middle
```{r olx, out.width = '90%'}
knitr::include_graphics("img/moz-open-leaders.png") 
```

.footnote[
web: [Mozilla Open Leaders](https://foundation.mozilla.org/en/opportunity/mozilla-open-leaders/) (Apply for OLX by August 1!)
]

???

But the whole program architecture is modeled after Mozilla Open Leaders. 

Mozilla Science Lab and Open Leaders & Events team has run this program 7 times, with up to 6 cohorts concurrently, so they have really dialed in the program architecture, and it is awesome. 

This includes a deliberate focus on creating a safe and welcoming space, and is focused on dicussion rather than lecturing or hands-on coding, so that participants can think through how this is relevant for them and learn from other labs. The program is led remotely, leveraging the power of the internet; it is led through video calls and Google Docs. 

Participants get more comfortable talking about open data science topics, and then their homework is to bring these conversations back to their larger lab groups. 

---
# [Sea]side chats & hackathons
<br>
```{r seaside-chat, out.width = '80%', fig.align='center'}
knitr::include_graphics("img/seaside-chats-wood.png") 
```

.footnote[
blog: [openscapes.org](https://www.openscapes.org/blog/2019/03/10/seaside-chats/); [Wood lab](https://github.com/wood-lab/wood-lab-resources#wood-lab-resources)
]

???

We call these conversations Seaside Chats, or Bayside, Bluffside or Fishbowl chats. They are specific times and places to talk about reproducible research, discuss coding issues, and learn about cool new packages relevant for research. 

This something that our OHI team has been doing for years now in addition to our weekly science lab meetings. This is a dedicated space to discuss and develop shared systems for the lab start weaving open data science into their every day work

We have also coopted the term hackathon, which is when our OHI team we will all drop our own projects and come together for a day or an afternoon to do something that will benefit the whole group, but is no one person's responsibility,like upgrading our filepath strategies with the "here" package. 

Some labs have also done hackathons too, and gotten metadata organized and developed onboarding procedures for the lab, so that new teammembers can get on board with the lab's workflow as soon as possible.

---
# Openscapes lesson series
.pull-left[
<br>
<br>
```{r series, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/openscapes-series.png")
```

.footnote[
lesson series: [openscapes.org/series](https://openscapes.github.io/series)
]
]

.pull-right[
```{r thread, out.width = '95%', fig.align='center'}
knitr::include_graphics("img/tweet-openscapes-series-thread.png")
```

.footnote[
tweet thread: [@openscapes](https://twitter.com/openscapes/status/1131243910200668160)
]
]

???

We covered a lot of other things in our cohort calls, and I'm working on capturing them all in the lesson series that anyone is able to use. 

transition: and in addition to these cohort calls, we focused a lot on leadership, both vertical and horizontal. 

---
class: center, middle
# Vertical & horizontal leadership

???

continue ->

---
# Ocean Health Index team
.pull-left[
```{r halpern0, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/Halpern-UCSB_UCOP-30.jpg")
```

.footnote[
web: [National Center for Ecological Analysis & Synthesis](https://www.nceas.ucsb.edu/); 
]
]

.pull-right[
```{r shiny-laughing0, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/shiny-conf-2016-crop.jpeg")
# knitr::include_graphics("img/tweet-juliesquid-shinydevcon2016.png")
```

.footnote[
tweet: [@juliesquid](https://twitter.com/juliesquid/status/693324555704610816)
]
]

???

On the left here is Ben Halpern, he's the lead of OHI and he has played a huge role in our data science even though he is not a coder himself. 

And this is really critical. 

As a leader he listened to our excitement and he supported us to invest time and resources in open data science, and he trusted us to implement shared practices for our team.

And as the director of NCEAS, the ecology center where we are based, He's making environmental data science a priority at NCEAS, and has also spearheaded a new masters program in environmental science at the University of California.  

Ben's leadership gave us agency and support to become leaders within our lab group, and beyond. 

---
# Ocean Health Index team
.pull-left[
```{r halpern, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/Halpern-UCSB_UCOP-30.jpg")
```

.footnote[
web: [National Center for Ecological Analysis & Synthesis](https://www.nceas.ucsb.edu/); 
]
]

.pull-right[
```{r shiny-laughing, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/shiny-conf-2016-crop.jpeg")
# knitr::include_graphics("img/tweet-juliesquid-shinydevcon2016.png")
```

.footnote[
tweet: [@juliesquid](https://twitter.com/juliesquid/status/693324555704610816)
]
]

???

On the right here are Jamie Afflerbach, Ben Best, and me. They are my teammates but they are also leaders for me. Ben spent countless hours sitting with me and teaching me R and was patient when I deliberately made emails from github go to my spam folder because I thought GitHub was not going to be useful to me. I told you I am really skeptical of new software. 

And Jamie is an amazing leader as well, I'll tell a story about her in a moment. 

And together we are partners in crime. We cofounded the eco-data-science study group together and have taught multiple carpentries workshops together. This is us preparing for the Shiny conference in 2016. 

transition: Enabling this kind of vertical and horizontal leadership around data is what I try to ignite with Openscapes. 

---
# Openscapes Champions

```{r champions-web, out.width = '70%', fig.align='center'}
knitr::include_graphics("img/openscapes-summit-web-champions.png")
```

.footnote[
blog: [openscapes.org](https://www.openscapes.org/blog/2019/03/27/champions-incorporate-open-science/)
]

???

These are the 7 Champions, they are early career science faculty and lecturers, and I mentor them one-on-one each month in addition to the cohort calls. 

I want them to become champions for open data science because they are unbelievably awesome scientsts and can have have an oversized influence like Ben has had. 

The critical thing for them to learn is that they do not have to become experts in open data science in order to support their labs and champion it more broadly. 

And this is important to release them of that expectation and this potential anxiety, because are super busy presenting their research to the US Senate, winning awards and grants, teaching, leading field work abroad, and they do not need to also feel like then need to master pull requests is in order to set their labs on a good track with data. 
<!---broken up so notes don't scroll--->

---
# Openscapes Champions

```{r champions-web-repeat, out.width = '70%', fig.align='center'}
knitr::include_graphics("img/openscapes-summit-web-champions.png")
```

.footnote[
blog: [openscapes.org](https://www.openscapes.org/blog/2019/03/27/champions-incorporate-open-science/)
]

???

Their role in Openscapes is to see what is possible alongside their labs, giving their labs the time and space to learn together, and advocate for all of this with their circles of influence. 

They are like R2D2 and BB8: their role is plugging into the system and opening doors so that Luke and Rey can run through and save the day. 

They do not necessarily need to learn everything about the Force themselves, although they need to see it, value it, and help amplify its importance. 

And they need to set the tone to encourage more horizontal leadership within their labs and beyond. 

transition: I've got a great example of this —

---
```{r zoom-michelle, out.width = '80%', fig.align='center'}
knitr::include_graphics("img/Cohort1_zoom-michelle.png") 
```

.footnote[
twitter: [@stuart620](https://twitter.com/stuart620)
]

???

This is Michelle Stuart. She is actually here at useR, where is she?
 
She is here at her first R conference because she is such a leader in the Pinsky lab, spearheading their seaside chats, helping everyone with GitHub after setting up her account, and she is planning a new course in open data science at the marine sciences department at Rutgers University. 

transition: And she is responsible for the first RLadies chapter in the US state of New Jersey

---
class: center, middle
```{r michelle-rladies, out.width = '82%'}
knitr::include_graphics("img/tweet-stuart620-rladies.png") 
```

.footnote[
tweet: [@RLadiesHPNJ](https://twitter.com/RLadiesHPNJ/status/1139867491822383104)
]

???

transiton: So this is an excellent transition into community.   

---
class: center, middle
# Community

???

I think that the best thing I do for the Openscapes cohort is to introduce and welcome them to our communities. 

When we talk about the awesomeness of R communities in Openscapes, it's not only to encourage them to become a part of them, but also to extend its ethos and kick-start this kind of movement in science. 

I used to have my feet squarely in the marine science community, but now I feel like a bridge across environmental communtities, R communities and Mozilla communities. 

I've learn so much from each and try to help channel those lessons between groups.
 
transition: And engaging in these broader communities for me started on Twitter.
 
---
# \#rstats

```{r jafflerbach, out.width = '45%', fig.align='center'}
knitr::include_graphics("img/tweet-juliesquid-jafflerbachspatial.png") 
```

.footer[
tweet: [@juliesquid](https://twitter.com/juliesquid/status/728326585485402112)
]

???

I joined twitter to learn R because of my teammate Jamie.

And you know me, I was definitely skeptical. I  thought Twitter was a megaphone for angry people. 

But she taught me how to use it to listen and learn from other others. And then to gradually build up the courage to like and retweet things. 

She taught me that liking and retweeting was not only a way to engage with the community yourself, but it was a way to welcome and amplify other people as well.   

So I was amazed that you could have community on Twitter

---
```{r ropensci-unconf, out.width = '70%', fig.align='center'}
knitr::include_graphics("img/tweet-jcheng-leaflet.png") 
```
 
.footer[
tweet: [@jcheng](https://twitter.com/jcheng/status/611260382741577729)
]

???

But you can. 

And I was also amazed that software developers were real people. And not only that, they were super nice people that made me feel welcome and valued.

Prior to conversations like these, I had never stopped to think that there were real people behind software. 

transition: And that might sound crazy, but before twitter, this is the closest I'd ever come to interacting with software:

---
class:middle, inverse, center
```{r clippy}
```

![](https://media.giphy.com/media/13V60VgE2ED7oc/giphy.gif)

<!---![](https://media.giphy.com/media/Law8cmreIvpMQ/giphy.gif) --->
???

I'm not kidding. 

But seriously, realizing that software developers went well beyond Clippy here was really a defining point in my life. 

This is was that turning point when I really became the person I am today — that person who never stops talking about how awesome R is and how it will change your life

transition: Even back in 2016 my 4 year old niece knew about ggplot and dplyr

---
class: center, middle
```{r out.width = '100%'}
knitr::include_graphics("img/tweet-juliesquid-wizard.png")
# https://twitter.com/juliesquid/status/726521325821431808
```

.footnote[
tweet: [@juliesquid](https://twitter.com/juliesquid/status/726521325821431808)
]

???

transition: So in Openscapes, I encourage everyone to engage, and it's cool to see them 

---
class: center, middle

```{r halley-rnoaa, out.width = '60%', fig.align='center'}
knitr::include_graphics("img/tweet-docfroehlich-rnoaa-full.png")  
```
 
.footnote[
tweet: [@DocFroehlich](https://twitter.com/DocFroehlich/status/1085990833571020800)
]

???

Halley has a big science follwing already and now tweets also about open data science, so this is a great example of the influence these champions are already having. 

---
# rOpenSci & RStudio

.pull-left[
```{r ropensci, out.width = '70%', fig.align='center'}
knitr::include_graphics("img/tweet-jafflerbach-runconf15.png") 
```

.footnote[
tweet: [@jafflerbach](https://twitter.com/jafflerbach/status/581578558977368064) 
]
]

.pull-right[
```{r rstudio, out.width = '82%', fig.align='center'}
knitr::include_graphics("img/tweet-juliesquid-shinydevcon-2016.png") 
```

.footnote[
tweet: [@juliesquid](https://twitter.com/juliesquid/status/694237930991161344)
]
]

???

So, rOpenSci and RStudio have just ignited such a change in my life.
I'm deliberately limiting myself by putting them on the same slide here because I otherwise could go on for days. 

They have been so welcoming and supportive of me from well before I knew what was going on. 

They have created communities where developers and new users who are strangers become collabortors and friends and where there is deliberate attention to setting the right space to make that happen. 

It was a big deal to not only connect online, but also in person, with so many other people in these communiies. It really solidified that we were part of this. 

And I wanted Openscapes to have this same opportunity

---
background-image: url(img/openscapes-summit.jpg)  
background-size: contain

.footnote[
blog: [openscapes.org](https://www.openscapes.org/blog/2019/04/08/summit-reflections1/)
]

???

So midway through the Openscapes program, we were able to get the research leads together in person in California. 

And Sean Kross was there too — he helped the Champions experience the awesomeness of the R community, and we had a Mozilla Fellow Christie Bahali join remotely as well to talk about working openly. 

This was such a cool event. I mean I had really high expections about how awesome this would be but they were exceeeded.

The summit not only this give them an opportunity to build trust and become allies science and Openscapes. But I think by meeting Sean and Christie they really felt what I feel here in this community.

---
class: middle
.whisper[This isn’t just about coding and GitHub, this is about changing how we do science <br>— Malin Pinsky]

.footnote[
blog: [openscapes.org](https://www.openscapes.org/blog/2019/04/08/summit-reflections1/)
]

???

So Malin said that this isn’t just about coding and GitHub, this is about changing how we do science. 

I'm just so excited that they feel this way, because mindset change comes from truly feeling it

transition: There are many more communities that I love but I'm going to talk about one more right now, and that's RLadies

---
# RLadies
```{r rladies, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/rladies-rstudioconf19-jdlong.jpg")  
```
 
.footnote[
web: [rladies.org](https://rladies.org/), 
photo: [JD Long](https://twitter.com/CMastication/status/1101568109423542273)
]

???

RLadies is changing the world. Increasing gender diversity in the R community is so impactful. But I think it's the the beginning. 

RLadies has given me confidence in myself, and made me be a better advocate for women in science. And that is something I try to pass on through Openscapes; I encourage them to become a part of RLadies adn extend its ethos to science. 

transition: The Openscapes cohort has engaged with RLadies and existing coding clubs, and also created new opportunities to code. 

---
# #tidytuesday hacky hours
```{r allison-tidytuesday, out.width = '70%', fig.align='center'}
knitr::include_graphics("img/tweet-allison_horst-tidytuesday.png") 
```

.footnote[
tweet: [@allison_horst](https://twitter.com/allison_horst/status/1110242520833769472); blog [openscapes.org](https://www.openscapes.org/blog/2019/05/02/tidy-tuesday-coding-club/)
]

???

Allison Horst and her student Gracie started in an in-person tidytuesday hacky hour. 

You probably recognize her name from all the beautiful artwork in this talk. 

---
```{r welcome-rstats, out.width = '75%', fig.align='center'}
knitr::include_graphics("img/horst-welcome_to_rstats_twitter.png")
```

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst);
blog: [openscapes.org](https://www.openscapes.org/blog/2019/01/15/personify-code/)
]

???

and from her little #rstats monsters 

transition: But she is also a lecturer of data science and statistics in an environmental science and management program, and she is an Openscapes Champion. 

---
class: center, middle
```{r allisonhorst-github-io, out.width = '60%'}
knitr::include_graphics("img/allisonhorst-github-io.png")
knitr::include_graphics("img/allisonhorst-github-io2.png")
```
 
.footnote[
web: [allisonhorst.github.io](https://allisonhorst.github.io/) 
]

???

One of the cool things she did to give back to the community is she created this website for her classes and posted all course materials and homeworks online. 

This is now a resource for Allison's students but also for anyone else wanting to learn on their own, or teach their own course.

I mentioned that Michelle is going to teach a new open data science course; she is going to use Allison's lessons.

transition: Those are just some stories of the teamwork, leadership, and community involvement that the Openscapes champions have been engaged in.

---
```{r openscapes-arctic, out.width = '100%', fig.align='center'}
knitr::include_graphics("img/horst_openscapes_arctic_1500px.png")
```

<br>
<br>

.pull-left[
### Mindset shifts in individuals<br>Increase in skills & practice

]

.pull-right[
### Culture shifts in labs<br>Leadership & championing

]


.footnote[
art: [@allison_horst](https://twitter.com/allison_horst); 
web: [openscapes.org](https://openscapes.org); 
blog: [openscapes.org](https://www.openscapes.org/blog/2019/06/12/wins-cohort1/)
]


???

There are so many more examples of the their awesome accomplishments and momentum. 

They are shifting mindsets and practice when it comes to open data science and teamwork, and they are igniting change in their labs, and in their departments, their campuses, and beyond. 

It's neat to see the interplay of open data science and teamwork. All labs have now created GitHub organizations for their labs, and this provides a digital place for collaboration, that complements the seaside chats, which is a physical space

And the more I reflect on this the more I realized is that —

---
class: middle, center
```{r loop, out.width = '100%'}
knitr::include_graphics("img/horst-lowndes-loop.png")
```

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst)   
]

???

data science and teamwork exist together in a feedback loop that that just keeps getting stronger and stronger.

Learning and using similar software promotes and streamlines teammwork. And also working as a team better equips you to learn open practices data science.

transition: This is a loop that feeds back on itself. For me, and likely for a lot of us in this room, this becomes difficult to differentiate and tease apart. 

---

```{r hex-wall-oz, out.width = '70%', fig.align='center'}
knitr::include_graphics("img/useR-oz-hex-wall.jpg") 
```

.footnote[
tweet: [@dataandme](https://twitter.com/dataandme/status/1017117835821244416)
]

???

I mean, just look at our hex stickers, which are a combination of tools and communities

---
class: middle, center
```{r loop2, out.width = '100%'}
knitr::include_graphics("img/horst-lowndes-loop.png")
```

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst)   
]

??

Tt took our Ocean Health Index team 4 years to learn how to work as a team and use open data science tools. 

That's too long. That's too long for anyone but especially too long when we are already living with impacts of climate change. 

So with Openscapes I'm trying to reduce the time it takes to discover this feedback loop, and the key is to welcome them. 

transition: Because welcome is a powerful thing.

---
class:inverse, center, middle
# Harness the power of welcome

???

Welcome is a powerful thing because it is so simple: it means being nice to people. 

It means being empathetic and friendly, realizing that even though someone might be an expert in their field and doing amazing science, they but might be intimidated by open data science and you welcoming them could be exactly what they need. 

---
<br>
<br>
```{r value-welcome, out.width = '90%', fig.align='center'}
knitr::include_graphics("img/ropensci-butland-welcome.png")
```

.footnote[
blog: [ropensci](https://ropensci.org/blog/2017/07/18/value-of-welcome/)
]

???

I learned this early from the folks at rOpenSci, RStudio and RLadies with their commitment to creating diverse and inclusive spaces. 

And it has been a big part of my experience and education with Mozilla, and a foundational part of Openscapes.

transition: and I'm convinced it's the way to help scientists do better science in less time

---
class: inverse
# Lessons learned 
<br>

### Open data science is a mindset
> expect a better way • build confidence & willingness • reimagine science communication

### Teamwork starts with openness
> working openly • vertical & horizontal & leadership • community

### Harness the power of welcome 

???

So these lessons for me fuel what it means to work responsibly and collaboratively with data but should also fuel what it means to do science. 

transition: I'm so proud of what we've accomplished with Openscapes in this first round of Champions —

---
```{r closing-thoughts}
```
name: environ-comm-r4ds
class: center, middle
background-image: url(img/horst-eco-r4ds.png) 
background-size: contain

.footnote[
.left[
<br>
art: [@allison_horst](https://twitter.com/allison_horst);
updated from [Wickham & Grolemund](https://r4ds.had.co.nz/)
]
]

???

And I am working to continue to develop and grow the program so that I can lead cohorts every year and begin on-demand workshops with teams on the ground. 

We do have a long way to go before this is is truly the reality in science.

But I am optimistic that Openscapes can play a role. I think the more we talk about and see why open data science is important for environmental science, the more it will be valued and the quicker we can change the culture as a whole.

---
```{r hands} 
```
class: center, middle
background-image: url(img/horst-starwars-hands.png)  
background-size: contain

.footnote[
art: [@allison_horst](https://twitter.com/allison_horst)
]

???

And the awesome thing is that we all have our part to play in helping this change.

We can all welcome and amplify these awesome environmental sicnetists as they in engage in R and join our community, so that we all can benefit from better science in less time. 

---
# Thank you all so much

.pull-left[
#### especially for this talk:
###OHI team <br>Mozilla team<br>Openscapes labs<br>Allison Horst<br>RLadies team

<br>

####all artwork: [@allison_horst](https://twitter.com/allison_horst)<br>xaringan theme: [@apreshill](https://github.com/apreshill/talks/blob/master/uo-sad-plot-better/index.Rmd#L7)

]

.pull-right[
<br>
<br>

### Please get involved: [openscapes.org/contact](https://www.openscapes.org/contact/); [@openscapes](https://openscapes.org)


#### Find me for stickers... <img src="img/openscapes-hex.png" alt="" style="float:right;width:80px;"/> <img src="img/ohi-hex.png" alt="" style="float:right;width:80px;"/>
]

???

Thank you.

---
```{r fin}
```
class: title-slide, right, bottom
background-image: url(img/horst-starwars-rey.png)
background-size: contain
background-position: bottom left   


# `r rmarkdown::metadata$title`

### `r rmarkdown::metadata$author`
### `r rmarkdown::metadata$role`
### `r rmarkdown::metadata$institute`

[`r icon::fa("twitter")` @juliesquid](https://twitter.com/juliesquid)  
[`r icon::fa("paper-plane")` lowndes@nceas.ucsb.edu](mailto:lowndes@nceas.ucsb.edu)  
[`r icon::fa("desktop")` jules32.github.io/user-2019-keynote](http://jules32.github.io/user-2019-keynote)  


<img src="img/mozilla.png" alt="mozilla" style="float:right;width:154px;"/>
<img src="img/nceas.png" alt="nceas" style="float:right;width:150px;"/>
