---
layout: post
title:  "CLI Data Gem Project"
date:   2016-08-23 23:37:22 +0000
---




Before I started working on my CLI project I peaked at what it looked like. I was a little overwhelmed by what it entailed. I thought that I didn't know how to do a lot of what was being asked. But I also thought that by the time I do it and figure it all out, I will have learned a heck of a lot.

It's hard to say exactly what I have learned because it's hard to remember what you knew and din't know a couple weeks ago. What I can say is that having done the project, I now feel it's pretty simple.  There are ways to make it way more complex, but I avoided going down those avenues. 

I actually ended up scrapping my first project. I made some decent progress, but ultimately got stuck trying to scrap an impossible site to scrape. I spent a whole day trying to scrape http://www.usaswimming.org/ViewNewsArticle.aspx?TabId=1&itemid=15733&mid=14491 . By the end of the day I was completely discouraged, and questioning everything. I assumed I couldn't scrape it because of own shortcomings as a newbie programmer. I remember it was a Tuesday, and I had plans that night. I turned my computer off feeling completely defeated, and in a terribly lousy mood. Before I left though, I pasted the site in the learn_neighbors slack channel, asking what they thought. When I got to where I was going, I opened my ipad and saw what my peers had to say. Immediately all my self-doubt and discouragement washed away. Other students way more knowledgeable than myself were saying how impossible the site was to scrape. A week later, and we're still making jokes about it. 

I moved on from trying to scrape that terrible site, and started out looking for another one. All I wanted to do was create Swimmer objects of the 2016 US olympic team, how hard could it be to find a site that has all the information I needed? Turns out harder than I thought. Every site I turned to was just as bad as the first one, well maybe not just as bad, but too hard for me to scrape. 

Another problem I initially had was that I had no clear plan on how to go about creating my project. I just jumped from one class to another, created a scraper method with no thoughts about how I would implement it. After a couple days I was just lost in a maze, and add on the seemingly never ending frustration on trying to successfully scrape a webpage, I had just had enough and decided to start a new project, on a different subject.

During a thoughtful Thursday Avi told someone else, who was thinking about scrapping their project, that you should never scrap a project, you should figure out what's wrong with it, and learn how to fix it. While this is probably true, I think in my case, scrapping my original project was the right move. While trying to work through the frustration and figure out what was wrong with my project, I did learn a lot of random programming things, and became more comfortable writing code. I'm a big believer in learning through experience and practice. I gained a lot of experience and practice working on my original project. It made it a lot easier to create my second project.

I did run into an odd error trying to scrape a wikipedia page for my actual project. I got this error message: "SSL_connect returned=1 errno=0 state=SSLv3 read server certificate B: certificate verify failed" when trying to scrape: https://en.wikipedia.org/wiki/New_York%27s_congressional_districts . My first thought gave me flashbacks to college. There was always a rule against using a wikipedia as a source for a research paper. My thinking was that scraping a wikipedia page was similarly frowned upon. 

I started having flashbacks to my original project. A perfect page with all the data I wanted, all I have to do is scrape it, and ugh can't scrape it. This lead to a whole day trying to resolve this error. From a quick google search, and a stack overflow search, it seemed the problem stemmed from an outdated version of Ruby. Talking to other students about this error strengthened my suspicions, they were all able to scrape this page with no problem. After countless random suggestions about how to resolve the issue, I had no luck. It was suggested that it could be a router issue, so I tried working from the library, and no luck. Once again I moved onto a different webpage. I found an ok page that had some information, I scraped the page, and created my NyDistrict objects, and completed my CLI Data gem project. I haven't let it go yet though. I tested scrapping it from my girlfriend's computer, and obviously had no issues. Reminds me of a Greek mythology tale:  https://en.wikipedia.org/wiki/Tantalus .

If I were to give advice to someone just starting the project it would be:
* Watch Avi's videos before you do anything
* Find a good site to scrape, and then revolve your project around that. It'l make so many more things           simple.
* Don't let the frustration get you down. It's supposed to be challenging. If it weren't you wouldn't learn         anything

