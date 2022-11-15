---
title: "19 Interviews in One Year"
date: 2022-11-13
---

I quit my job in the summer of 2021 to take a sabbatical from work, and jumped back into the job market in 2022. Despite the hiring freezes, layoffs, and general uncertainty, I interviewed with 19 companies, totaling more than 100 rounds, and eventually ended up with 10 offers at the Senior or Principal level. These companies were FAANGs, but also in tech, finance, real estate, and media.

  

It was a long, fun, exhausting process, and I’m taking notes here in case this helps anyone else (and to be honest, me as well).

  

**LEVEL**

  

I was looking at Senior and Senior+ Android engineer positions. One company, in fact, ended up offering me an engineering management role but at this time I realized I wanted to stick to technical work.

  

I knew I wanted to lean into my architecture and leadership skills, but beyond that I kept an open mind: most of all I wanted a supportive team in a business I believed in.

  

I did end up rewriting my resume to reflect this level, specifically mentioning projects that I owned end-to-end or had led across multiple teams.

  

**WHY SO MANY?**

  

-   The “friction” of interviews, aka “unexpected stuff is going to happen”. Roles will get filled, hiring freezes will happen, I could flunk interviews, companies will ghost you, I could have gotten “bad vibes” from a team, etc. All of these things happened to me, and it narrowed down the field considerably.
    
-   “Senior level” Android roles cover a considerable variety of responsibilities. Some companies want someone who can go heavy on feature/UI work, some are looking for architects, some of them want engineers to be tech leads. Often it was hard to tell which until I passed the onsite and I got to a “team matching” round.
    
-   Hedging my bets. I had decided I wasn’t going to kill myself prepping leetcode, so I was prepared to flunk a few interviews.
    

  

I didn’t know when I started that I would be jumping into the worst job market in several years.

  

Thankfully I still ended up performing at a personal best - I got through 100% of my tech screens, and ended up with multiple competitive offers that I was happy with.

  

**HOW DID I GET THE INTERVIEWS?**

  

The majority of the interviews were referrals from my personal network, but several were a result of recruiter reachout.

  

**PREPARATION**

  

I already mentioned I wasn’t prepared to kill myself with leetcode prep, so I gave myself a month and allocated about an hour or two a day. Given that constrained time, I got overwhelmed pretty quickly by the sheer amount of online prep material and the thousands of questions on Leetcode itself.

  
Eventually, I sprung for [AlgoMonster](https://algo.monster/), which was super helpful in giving me a limited, structured way to practice. I spent the majority of the month on this. I also found these resources helpful for theory support in addition to the coding practice:

  

[Tech Interview Handbook](https://www.techinterviewhandbook.org/)

[Vaidehi Joshi's Basecs Series](https://github.com/vaidehijoshi/basecs-series)

  

For system design: Honestly there are no real Android-specific prep materials for this kind of thing; it was pretty much just me designing apps the way I normally would. Experience really shows here. I will say that Alex Xu’s [System Design Interview](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF) was really helpful for general design principles.

  

For behavioral rounds, I took a mentor’s advice and prepared 3-4 “stories” ahead of time - complex projects I had led before or issues I had to solve. The project stories had to stand up to 20-30 mins of in-depth questioning, so I thought a lot before picking these.

  

That being said, once I had my onsites lined up (most of them back to back over two weeks), I ceased doing any extra prep. Someone had told me at the beginning of my career that each interview itself is great practice, and that was absolutely true. Each interview became prep for the next one.

  

Interviewing was also really the only way to prep for “interview talk” - the process of narrating my thought process, discussing multiple solutions and tradeoffs, while keeping the balance of driving the session and gathering feedback from the interviewer. This was the hardest skill for me to practice, because I do my best thinking in silence, with a paper and pen. Doing “interview talk” while simultaneously solving complex problems was probably the most difficult thing I had to do, but it got easier each time.

  

Doing the interviews back to back paid off in that sense.

  

Next, the interviews themselves:

  

**STRUCTURE**

  

Tech screens usually came in one of two flavors:

  

 1. Leetcode style coding + verbal Android tech questions

  

	Speed was so important here. I realized if I didn’t end up on the right track within 10 minutes of coding, I was usually scrambling at the end. AlgoMonster paid off here because they trained me to match algorithm patterns, and once that clicked, I had the implementation ready.

  

2. Take home Android project (usually extended in the onsite)

  

	This was more fun in the moment, but also way more time-consuming. I wish to God I had made a simple sample project for my Github for companies to look at; it could have saved me a tech screen round. As it was, I ended up making four or five very similar take-home Android projects. It wasn’t a total waste because I liberally copy pasted (no need to waste good code), especially boilerplate like Adapters.

  

It’s worth asking to skip this portion by the way. I always asked, and a couple of companies did agree to send me straight to the onsite due to my experience.

  

I got through all of my tech screens, so onto the onsites!

  

Pretty much every company did at least one behavioral and at least one system design, but the technical rounds varied wildly. I ran into two types:

  

1. Coding-focused

  

	Very similar to tech screen version - speed and communication are super important. Getting to the right solution fast matters. Being able to get code fully written, compiled, and running matters.

  

2. Android live coding, with or without a take home project

  

	This was again way less stressful because it felt the most natural. This was coding from experience, and not far out of the scope of the take home challenges.

  

**COMMON TOPICS**

  

These were the topics I encountered multiple times throughout the interview process. If I had to interview again, this is what I would definitely brush up on.

  
  

**ANDROID**

  

Architecture patterns: MVC/MVP, MVVM, MVI/Redux

Memory leaks and ANR’s: how they happen, and how to debug them

Multithreading:

-   How threads and processes work in Android
    
-   Coroutines vs RxJava vs Kotlin Flows
    

UI Performance issues, including:

-   Image processing and rendering
    
-   View hierarchy and rendering processes
    

Recyclerviews: how they work internally and possible performance issues

Dependency Injection: how it works and its tradeoffs

Data persistence options for Android and tradeoffs for each

  

**DATA STRUCTURES AND ALGORITHMS**

  

Algorithms I implemented in multiple solutions:

-   Depth First Search (five separate times!!)
    
-   Binary Search
    
-   Breadth First Search
    

  

Data Structures:

-   Array (in nearly every interview!)
    
-   List
    
-   Hashmap
    
-   Set
    
-   Heap
    

  

Obviously, I had to be familiar with Big O time and space performance in each of these.

  

One thing to note: I had to be familiar with the algorithms that the Kotlin and Java Collections library use under the hood, along with their performance.

  

**BEHAVIORAL**

  

In general, interviewers wanted to dig deep into my successful projects, and what it said about my technical and leadership skills. I also talked a lot about my failures, whether it was due to failure of communication, planning, or strategy.

  

**SYSTEM DESIGN**

  

I used everything I knew about clean Android architecture: separation of the data/network layer from UI, small and tightly-scoped classes, reactive observers to link the layers together, enough flexibility in the design to handle future complexity, etc.

  

I also proactively designed with the following in mind:

-   UI performance
    
-   Online/offline states
    
-   Caching/persistence layers
    
-   Good backend communication: aka pagination and queueing/buffering logic
    

  

**COMMUNICATION**

  

It’s worth talking about this, because I felt this played a huge role in getting senior+ level roles. I drove a lot of the interview conversation, even in the technical rounds. It helped to pretend that the interviewer was a slightly junior colleague and I was the tech lead, collaborating on a project.

  

Sounding relaxed and confident was critical, even if I didn’t feel it at first. Feedback from several companies indicated that my communication skills pushed me firmly into senior territory.

  

I also asked every interviewer a lot of questions, and didn’t shy away from asking the difficult ones (What are some frustrations you deal with often? Tell me about a time when you had to give negative feedback to coworkers, and how was it received? etc)

  

**OFFERS**

  

As I said, I ended up with quite a few companies interested in moving forward. I was transparent with all my recruiters about my other interviews; when I had offers on the table, I asked to speed up any lagging timelines. I also proactively talked numbers with recruiters, so I was able to rank companies by pay ahead of time.

  

Once all my onsites were complete I had a clear idea of which teams and projects were my top choices; since I had rough pay information already I preemptively turned down the companies I wasn’t interested in.

  

In the end, I had four strong offers, each of which I’d be happy to move forward with. I used the “Best Acceptable Alternative” strategy for each negotiation call: one initial ask, and then a secondary alternative. I also did research into each business since my comp was weighted so heavily towards equity.

  

I didn’t have to negotiate much in the end as each company started with a strong offer (having competing offers helped in that sense); by the end of two weeks, all four were in the same pay ballpark, and I committed.

  

**TIMING**

  

I started serious interview prep in August, did more prep and tech screens in September, nearly all of my onsites in October, then finally signed an offer at the end of October.

  

Most of this was part-time - approximately two hours a day, except for the two week period where I dedicated myself to onsites full-time.

  

All in all, it took three months from start to finish, although I also spoke at two conferences during this time and that slowed me down a bit.

  

**CONCLUSION**

  

Despite these interviews being the toughest I’ve done throughout my career, I enjoyed them the most. Interviewing is a skill set; and like all skills, the process became a lot more fun once I had gained competency in them.

  

I realized however that so much of the interviewing game is down to luck, opportunity, and timing. So much of this process was out of my hands: Meta went into a hiring freeze the day of my onsite. Another company filled a dream role, again, the day I had the onsite for it. I lost a role I was excited about due to scheduling chaos; and then another because the company decided to downlevel the position. Most companies weren’t able to offer the full team-matching experience because I was interviewing in a bad market.

  

A lot of it is also arbitrary. Other engineers I knew would interview at the same company for similar roles and their interview process would look completely different.

  

It was less about finding the *one perfect job* than it was about figuring out *good enough*: Are there good people here? Is this a company that does good work?

  

In the end, I got *good enough* and more, and that was enough.

