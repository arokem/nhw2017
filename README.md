# Neurohackweek 2017

Neurohackweek 2017 is a 5-day hands-on workshop in neuroimaging and data science, held at the University of Washington eScience Institute, September 4th-8th, 2017.

Participants will learn about technologies used to analyze human neuroscience data and develop the skills needed to make their analyses and results shareable, transparent, and reproducible.

## Quick links
* [Overview](#overview)
* [Preparing for the course](#preparing-for-the-course)
  * [Install the course software](#install-the-course-software)
  * [Read the Code of Conduct](#read-the-code-of-conduct)
* [Code of Conduct](#code-of-conduct)
* [What to expect](#what-to-expect)
  * [Interaction and collaboration are not optional](#interaction-and-collaboration-are-not-optional)
  * [A note on programming languages](#a-note-on-programming-languages)
  * [What happens at Neurohackweek...](#what-happens-at-neurohackweek)
* [Schedule](#schedule)
    * [Sunday (9/3)](sunday-9-3)
    * [Monday (9/4)](monday-9-3)
    * [Tuesday (9/5)](tuesday-9-3)
    * [Wednesday (9/6)](wednesday-9-3)
    * [Thursday (9/7)](thursday-9-3)
    * [Friday (9/8)](friday-9-3)
    * [Saturday (9/9)](saturday-9-3)
* [Projects](#projects)


## Overview

[will add this shortly]

## Preparing for the course
We've done our best to streamline the course and ensure that people can hit the ground running on Day 1. However, to ensure that everyone has a good experience both professionally and personally, we'd like everyone to do two things at the outset of Neurohackweek--actually, preferably ahead of the course. The first thing is to install as much of the course software as possible ahead of time, and the second is to read--and take seriously--our [Code of Conduct](#code-of-conduct).

### Install the course software
We strongly recommend that participants spend some time ahead of the course making sure they have most of the software they'll use during NHW installed. Because of our tight schedule, we're not able to set aside much time on Day 1 for installation; aside from a few minutes between tutorials, we're going to assume you already have all of the software discussed by the instructors installed. Unfortunately, we also can't provide laptops or desktop computers to participants--so you'll need to come with your own laptop. If you absolutely cannot find a suitable computer to use for the course, please contact Ariel Rokem, and we'll do our best to find you one you can use.

To maximally benefit from Neurohackweek, participants should install the software packages and tools described (with installation instructions for all major operating systems) on [this page](https://neurohackweek.github.io/nhw2017/setup/). We encourage you to do this ahead of the course, so that you can spend your time on Day 1 following the tutorials rather than reading installation instructions and missing what the instructors are saying.

Though we suggest installing everything on the [provided list](https://neurohackweek.github.io/nhw2017/setup/), the most critical elements--without which you're probably going to have a bad time at Neurohackweek--are the bash shell (which is already built into the operating system if you're on Linux or OS X), git, and a good text editor (or, if you're fancy, a full-blown IDE).. Additionally, because most of the instruction in the course will be conducted in Python, we also strongly encourage everyone to have a working Python environment. To round things out, we suggest installing RStudio and Docker, which will be used for various tutorials and demonstrations.

### Code of Conduct
Neurohackweek is dedicated to providing a harassment-free learning experience for everyone regardless of gender, gender identity and expression, sexual orientation, disability, physical appearance, body size, race, age or religion. We do not tolerate harassment of participants in any form. Sexual language and imagery is not appropriate for any conference venue, including talks. Conference participants violating these rules may be sanctioned or expelled from the conference without a refund at the discretion of the organizers.

Harassment includes, but is not limited to:
- Verbal comments that reinforce social structures of domination related to gender, gender identity and expression, sexual orientation, disability, physical appearance, body size, race, age, religion.
- Sexual images in public spaces
- Deliberate intimidation, stalking, or following
- Harassing photography or recording
- Sustained disruption of talks or other events
- Inappropriate physical contact
- Unwelcome sexual attention
- Advocating for, or encouraging, any of the above behaviour

Participants asked to stop any harassing behavior are expected to comply immediately. If a participant engages in harassing behaviour, the organisers retain the right to take any actions to keep the event a welcoming environment for all participants. This includes warning the offender or expulsion from Neurohackweek with no refund.

Neurohackweek organisers may take action to redress anything designed to, or with the clear impact of, disrupting the event or making the environment hostile for any participants. We expect participants to follow these rules at all the event venues and event-related social activities.

Harassment and other code of conduct violations reduce the value of Neurohackweek for everyone. If someone makes you or anyone else feel unsafe or unwelcome, please report it as soon as possible to one of [the instructors](http://neurohackweek.github.io/#instructors). You can make a report either personally or anonymously. Anonymous reports can be made at [https://neurohackweek.wufoo.com/forms/neurohackweek-code-of-conduct-violation/](https://neurohackweek.wufoo.com/forms/neurohackweek-code-of-conduct-violation/)

--
This anti-harassment policy is based on the example policy from the [Geek Feminism wiki](http://geekfeminism.wikia.com/wiki/Conference_anti-harassment/Policy), created by the [Ada Initiative](http://adainitiative.org/) and other volunteers.

## What to expect
Aside from the nuts and bolts of the course, we've also tried to consolidate in one place (specifically, *this* place!) a few other informal policies and suggestions that we think NHW participants may benefit from keeping in mind.

### Interaction and collaboration are not optional!
First, Neurohackweek is first and foremost about interaction and collaboration. It places much more emphasis than most other training courses on hands-on collaboration and extended interactions between participants (and instructors). This bears emphasizing, because in our experience, no matter how many times we say it, many participants don't take enough advantage of the interactive format of the course. Both the instructors and your fellow participants at NHW are here *for you*. As such, you should feel free to ask anyone else attending NHW any questions that you think might fall within their areas of expertise, to bounce ideas off of them, and to solicit feedback and input on your team projects as they evolve. Or even just ask them what they're working on, out of curiosity. The point of the instructors and other participants being here, and of NHW adopting a hands-on format, is to help you acquire new information and new skills; if you think someone else can help facilitate that, go talk to them!

Concretely, the rule we'll try to adhere to at NHW is that if someone's hanging around in a common area (e.g., the DSS), they're fair game for interaction. This cuts both ways, of course: your fellow participants (as well as the instructors) are also going to feel comfortable asking *you* for your help or input when they need it. Of course, this doesn't mean you have to prioritize others' needs above your own work; if you're concentrating intently on something and don't want to be interrupted for a while, that's totally cool--just duck into a quiet corner somewhere (there will be break-out rooms people can use in the Data Science Studio in the afternoons), or let whoever's asking you for help know that you'll come find them once you're done.

#### People work here
There's one important caveat to the "interactivity" rule above that we need to mention: many of the people who'll be working in the Data Science Studio while Neurohackweek is going on are full-time employees or researchers at the eScience Institute, and aren't there just for the course. This includes the eScience-based NHW instructors (Bernease, Jake, and Valentina), who have been kind enough to volunteer their time to help with the tutorials, but have plenty of other non-NHW-related duties to attend to otherwise. Please be respectful of these people's time and give them some space. Keep in mind that we're essentially holding a 50-person week-long course in the middle of their workspace. :)

### A note on programming languages
In general, most of the tutorials and break-out sessions at NHW will be conducted in the Python programming language, to the relative exclusion of other languages used in the neuroimaging community (though there will be tutorials in R and JavaScript, and probably break-out sessions that use other languages). We want to emphasize that the decision to focus primarily on Python is purely a pragmatic: it would be very inefficient, in an intensive week-long course that emphasizes development of software development and data science skills, to try to teach and work in several different languages. By emphasizing a single language, our hope is that participants will be able to focus on learning concrete computational and data science skills, rather than spending their time learning the idiosyncracies of each new language's syntax.

As we'll discuss on Day 1, we also happen to think that Python is  a particularly good choice for our course, because (a) it's relatively easy to learn; (b) it's a general-purpose language and has excellent tooling support in a vast number of domains; (c) it's already very widely used in the neuroimaging data science community; and (d) it's completely free and runs on all major operating systems. That said, we want to be very clear that the fact that Python will be the main language of instruction at NHW has *no implications at all for what languages you can and should use during the course*. A huge amount of neuroimaging software is written in languages other than Python, and there are many, many neuroimaging applications where the best-in-class tool is written in MATLAB, R, C, or something else. While we encourage all participants who aren't familiar with Python to spend a bit of time working in it, we're happy for you to work in whatever language you like. To give you a sense of the diversity, in the inaugural installment of NHW, participants contributed to projects written in Python, R, MATLAB, JavaScript, and C (as well as some projects written only in natural languages!).

### What happens at Neurohackweek...

[will add shortly]

## Schedule

The NHW17 schedule consists of several different kinds of events: data science tutorials; traditional lectures; hacking/team project sessions; and break-out sessions. Oh, and meals. Meals are also a kind of event that we will have, because in past years we've found that Neurohackweek participants learn and contribute more when they're not suffering from starvation.

All events on the schedule will be held in one of four locations: the Lander Hall (LH) residence where all participants and instructors are staying; the Data Science Studio (DSS) on the 6th floor of the Physics-Astronomy Building; the Odegaarde Undergraduate Library (OUGL); and the classrooms on the 5th floor of the Physics-Astronomy Building (PAB5). Locations for all events are indicated in parentheses below using the above abbreviations. The general idea is that breakfast and lunch will always be in Lander Hall, and (at least after Monday) morning sessions will be at the Odegaarde Library while afternoon sessions will be in the Data Science Studio. All of these locations are an easy (and very pleasant) 10-minute walk from one another.

### Sunday (9/3)

Arrival and check in. You can check into the dorms at Lander Hall at any time on Sunday, September 3rd. You will receive a room key as well as a dining card that will grant you access to the dining hall in Lander for breakfast and lunch all week (you are responsible for your own dinner on Tuesday, Wednesday and Thursday). Please be sure to check out by 11 am on Saturday, September 9th.


### Monday (9/4)

The schedule on Monday is a little different from the rest of the week, in that the afternoon will consist of data science tutorials rather than team project/hacking sessions. The idea is to make sure that everyone has the basic skills needed in order to jump in and contribute to the group projects the rest of the week.

* 8 AM - 9 AM: Breakfast (LH)

* 9 AM - 10:30 AM: Introduction to Neurohackweek (Ariel Rokem; PAB5)

* 10:30 AM - 12 PM: Reproducibility in fMRI: What is the problem? (Russ Poldrack; PAB5)

* 12 PM - 1 PM: Lunch (LH)

* 1 PM - 6 PM : Data science tutorials (PAB5)
* 7 PM : Welcome reception (DSS)

#### Monday afternoon data science tutorials
On Monday afternoon, we will have two parallel tracks of data science tutorials, held simultaneously in different rooms. You're welcome to move between rooms as you like. We've tried to organize the tutorials in such a way as to maximize the differences between the topics being covered at any given time, but it's inevitable that some people will want to attend both of the tutorials being held at a given time. While the instructor cloning machine we purchased last year is currently out of service, the good news is that video recordings and materials for all of the tutorials will be immediately available online, so you'll be able to catch out on what you missed in short order if you so choose. Also, most of the tutorial instructors on Day 1 will be hanging around for most or all of the rest of the week, and you should feel very free to approach them if you have any questions about anything they covered (or for that matter, about related topics taht they didn't cover).

| Time | Room 1 | Room 2 |
|:------------- |:-----:|:-----:|
| 1 - 2 PM | Unix shell 1 (Valentina) | Best practices in scientific computing (Chris) |
| 2 - 3 PM | Unix shell 1 (Valentina) | Best practices in scientific computing (Chris) |
| 3 - 4 PM | Git/GitHub 1 (Bernease) | Web development (Anisha) |
| 4 - 5 PM | Git/GitHub 2 (Bernease) | Jupyter/Interactive computing (Dylan) |
| 5 - 6 PM | Python programming 1 (Tal) | Intro to R (Jeanette) |
| 6 - 7 PM | Python programming 2 (Tal) | Intro to R (Jeanette) |



### Tuesday (9/5)

8 AM - 9 AM: Breakfast (LH)

9 AM - 12 PM: Cloud computing (Tara Madhyastha; OUGL)

12 PM - 1 PM: Lunch (LH)

1 PM - 3 PM: Team project pitches (PAB5)

3 PM - 6 PM: Team projects (DSS)
* Afternoon breakout sessions (optional):
    * 3 PM: AIBS data-sets (Nick Cain)
    * 4 PM: Advanced data manipulation in pandas (Tal Yarkoni)

6 PM - 12 AM: Dinner (on your own) and hackathon sessions (LH)


### Wednesday (9/6)

8 AM - 9 AM: Breakfast (LH)

9 AM - 11 AM: Machine learning (Jake Vanderplas; OUGL)

11 AM - 12 PM: Machine learning in neuroimaging (Chris Holdgraf; OUGL)

12 PM - 1 PM: Lunch (LH)

1 PM - 6 PM: Team projects (DSS)
* Afternoon breakout sessions (optional):
    * 3 PM: Statistical practice in neuroimaging (JB Poline)
    * 4 PM: Power in fMRI (Jeanette Mumford)

6 PM - 12 AM: Dinner (on your own) and hackathon sessions (LH)


### Thursday (9/7

8 AM - 9 AM: Breakfast (LH)

9 AM - 12 PM: Neuroimaging pipelines (Satra Ghosh; OUGL)

12 PM - 1 PM: Lunch (LH)

3 - 6 PM: Team projects (DSS)
* Afternoon breakout sessions (optional):
    * 3 PM: Advanced time-series analysis (Bing Brunton)

6 PM - 12 AM: Dinner (on your own) and hackathon sessions (LH)


### Friday (9/8)

8 AM - 9 AM: Breakfast (LH)

9 AM - 12 PM: Team projects (DSS)

12 PM - 1 PM: Lunch (LH)

1 PM - 2 PM: Team projects (DSS)

2 PM - 5 PM: Project presentations (DSS)

5 PM - 6 PM: Summary and feedback (PAB5)

6:30 PM: Farewell reception and Lake Union Cruise


### Saturday (9/9)

**Check out and departure.** Sadly, all good things must come to an end. In this case, the end must come by 11 am on Saturday, September 9th--when is the latest you can check out of Lander Hall.


## Projects

[will add this shortly]
