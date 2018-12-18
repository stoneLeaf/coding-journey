# coding-journey

My personal journey as a self-taught web developer.

> Disclaimer: As an aspiring developer, I'm merely exposing my chain of thoughts which will, hopefully, lead to some half decent knowledge. You should take my stance and analysis on technologies as an earnest *work in progress*. My opinions will most likely mature with time, and I will try to reflect these changes as much as possible.

## Table of contents

- [Background](#background)
- [Right on tracks](#right-on-tracks)
- [JavaScript == 42?](#javascript--42)
- [Modern JavaScript front-end frameworks](#modern-javascript-front-end-frameworks)

## Background

To say the least, I had a very early access to computers, as I made my first (baby) steps on PCs in the 90s on [386](https://en.wikipedia.org/wiki/Intel_80386) and [486](https://en.wikipedia.org/wiki/Intel_80486) machines paired to black and white CRT monitors. I have vivid memories of [incredible DOS games](https://en.wikipedia.org/wiki/Day_of_the_Tentacle), witnessed the dawn of modern era OSs with [Windows 3.11](https://en.wikipedia.org/wiki/Windows_3.1x), and experienced all the things we used to do on computers before the Internet era.

Jumping in time, in 2002, at age 13, I published a [personal website](https://web.archive.org/web/20030205181607/http://webmastheur.free.fr/), written in php and backed by a MySQL database, around my newfound interest for web development offering [html](https://web.archive.org/web/20040604235747/http://webmastheur.free.fr:80/?page=html&rub=tutos) and [php](https://web.archive.org/web/20040604235747/http://webmastheur.free.fr:80/?page=php&rub=tutos) tutorials. While it was very naive and candid, it certainly denoted an early inclination towards web development.

A decade later, around 2011, I embraced [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming) with Java. I liked it so much more than any languages I had played with before. The code architecture and patterns felt so clean and powerful, its static typing beautifully cementing the whole. Also, around that time, mobile platforms were booming and app stores a land of promise for indie devs. I seriously thought about trying my luck but ultimately did not go through with it and parted with a feeling of unfinished business.

To sum it up, coding, and computers in general, were always present throughout my life, as a hobby and strong interest. Soon turning 30, after studies in various areas and a few years as a salesman for a big company, I intend to pursue that passion and make it a full time job.

## Right on tracks

Eager to learn a proper web development stack, I first picked [Ruby on Rails](https://rubyonrails.org/). A well known and very mature framework, with lots of resources and known for allowing very fast prototyping. My goal being at that time to target new startups as a potential full stack developer, it seemed the perfect fit. I knew from the start it was not *the* latest trend of web development, but I thought to myself I had to focus on efficiency and reliability instead of trendiness.

After a few Ruby courses, and a [famous Rails tutorial](https://www.railstutorial.org/book), I dived in and made a first project, a simple time tracking application. In a matter of days, I was able to lay out my models, controllers, and easily implement a fully-featured authentication using an [external library](https://github.com/plataformatec/devise). I spent a lot of time on data validation, learning how to use the very handy Rails helpers, and on code refactoring, trying to grasp the principles [RuboCop](https://github.com/rubocop-hq/rubocop) was hastily throwing at me.

With a workable back-end, I then focused on the front-end. Being a time recording app, I wanted it to feature a live clock and a stop button in the nav bar whenever the user was currently recording an activity. It meant [AJAX](https://en.wikipedia.org/wiki/Ajax_(programming)) requests and [DOM](https://en.wikipedia.org/wiki/Document_Object_Model) updates. But the [way to do it](https://guides.rubyonrails.org/working_with_javascript_in_rails.html) using the classic Rails stack felt wrong and outdated. For instance, I really didn't like the idea of serving JSON to Ajax requests with the same controllers which would also serve regular html requests. For lack of betters words, let's just say it seemed *hacky* and very time consuming.

Lately, I had been reading my daily share of articles about pretty much everything related to web development. And it is at that moment that the idea of a [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application) querying a back-end suddenly made a lot of sense. Making a traditional multi page application did not anymore, at least in that project's scope. Plus, having a truly distinct back-end and seemed a better architectural choice, especially in the long run as it could also be used to serve native mobile apps. Even though it is [perfectly possible](https://evilmartians.com/chronicles/evil-front-part-1) to pair Rails with a modern front-end solution, I thought it was a good time to reconsider the whole stack I wanted to work with.

## JavaScript == [42](https://www.google.com/search?q=the+answer+to+life+the+universe+and+everything)?

This decade has all been about JavaScript, steering away from its shallow roots toward a respectable language and ecosystem. I must admit that using it to power a back-end still seemed really strange to me, at that time, as I had not yet ever used [Node.js](https://nodejs.org/en/). As a remedy, I decided to start by building a standalone back-end API. Regarding my choice of stack, I didn't want to use a fully-featured framework such as [LoopBack](http://v4.loopback.io/), but instead go layer by layer to get a good sense of the architecture and inner mechanics.

The almost 3 weeks I spent, as a result, building from scratch [a workable RESTful*ish* API](https://github.com/stoneLeaf/timeflies-backend) were really intense. For an in-depth perspective, you can check out the [development journal](https://github.com/stoneLeaf/timeflies-backend#development-journal). To sum it up in terms of experience, it had been a big leap for me in terms of paradigm and consequently a very satisfying learning opportunity.

The language I had the most knowledge and experience with, prior to enterprise, had been [Java](https://en.wikipedia.org/wiki/Java_(programming_language)), which is class-based OOP and strongly typed, whereas [JavaScript](https://en.wikipedia.org/wiki/JavaScript) is prototype-based OOP and weakly typed. And the only web framework I had worked with before was [Rails](https://en.wikipedia.org/wiki/Ruby_on_Rails), which is very opinionated, has embedded generators for code scaffolding and advocates [convention over configuration](https://en.wikipedia.org/wiki/Convention_over_configuration). [Express](https://expressjs.com/), on the other hand, is quite the opposite as it is very minimalist and only handles routing and middleware stacking, without promoting any pre-defined project structure and practices.

Previously obscure concepts such as middlewares and asynchronous programming were now very familiar. I was also very proud of the fact that I tried to the best of my ability to embrace [test-driven development](https://en.wikipedia.org/wiki/Test-driven_development), at least at an integrated level. The end result, while being far from any perfection, was good enough to back the first attempts at front-end clients that would come. I still had *lots* of ideas for improvements and architectural changes and intended to come back to this project at the appropriate time.

## Modern JavaScript front-end frameworks

I picked [Angular](https://angular.io/) as the first front-end JavaScript framework I would get my hands on. [React](https://reactjs.org/) was also a good candidate, but it was less popular in terms of job offering in my area. I'm switching now to my first front-end client [development journal](https://github.com/stoneLeaf/timeflies-angular#development-journal) for insights, and will resume writing here when done.
