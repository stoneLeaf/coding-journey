# coding-journey

My personal journey as a self-taught web developer.

> Disclaimer: As an aspiring developer, I'm merely exposing my chain of thoughts which will, hopefully, lead to some half decent knowledge. You should take my stance and analysis on technologies as an earnest *work in progress*. My opinions will most likely mature with time, and I will try to reflect these changes as much as possible.

## Table of contents

- [Background](#background)
- [Right on tracks](#right-on-tracks)
- [JavaScript == 42?](#javascript--42)

## Background

To say the least, I had a very early access to computers, as I made my first (baby) steps on PCs in the 90s on [386](https://en.wikipedia.org/wiki/Intel_80386) and [486](https://en.wikipedia.org/wiki/Intel_80486) machines paired to black and white CRT monitors. I have vivid memories of [incredible DOS games](https://en.wikipedia.org/wiki/Day_of_the_Tentacle), witnessed the dawn of modern era OSs with [Windows 3.11](https://en.wikipedia.org/wiki/Windows_3.1x), and experienced all the things we used to do on computers before the Internet era.

Jumping in time, in 2002, at age 13, I published a [personal website](https://web.archive.org/web/20030205181607/http://webmastheur.free.fr/), written php and backed by a MySQL database, around my newfound interest for web development with homemade [html](https://web.archive.org/web/20040604235747/http://webmastheur.free.fr:80/?page=html&rub=tutos) and [php](https://web.archive.org/web/20040604235747/http://webmastheur.free.fr:80/?page=php&rub=tutos) tutorials. While it is very naive and candid, it certainly denotes an early inclination towards coding.

A decade later, around 2011, I embraced [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming) with Java. I liked it so much more than any languages I had played with before. The code architecture and patterns felt so clean and powerful, its static typing beautifully cementing the whole. Also, around that time, mobile platforms were booming and app stores a land of promise for indie devs. I seriously thought about trying my luck but ultimately did not go through with it and parted with a feeling of unfinished business.

To sum it up, coding, and computers in general, were always present throughout my life, as a hobby and strong interest. Soon turning 30, after studies in various areas and a few unsatisfactory years as a salesman for a big company, I'm finally going back to it all, this time for good.

## Right on tracks

Eager to learn a proper web development stack, I chose [Ruby on Rails](https://rubyonrails.org/). A well known and very mature framework, with lots of resources and known for allowing very fast prototyping. My goal being to target new startups as a potential full stack developer, it seemed the perfect fit. I knew from the start it was not *the* latest trend of web development, but I thought to myself I should focus on efficiency and reliability instead of trendiness.

After a [few Ruby courses](https://www.codecademy.com/catalog/language/ruby), and a [famous Rails tutorial](https://www.railstutorial.org/book), I dived in and made a first project, a simple time tracking app. In a matter of days, I was able to lay out my models, controllers, and easily implement a fully-featured authentication using an [external library](https://github.com/plataformatec/devise). I spent a lot of time on data validation, learning how to use the very handy Rails helpers, and on code refactoring, trying to grasp the principles [RuboCop](https://github.com/rubocop-hq/rubocop) was hastily throwing at me.

After 50 commits, it was time to focus on the front-end. Being a time recording app, I wanted it to feature a live clock and a stop button in the nav bar whenever the user was currently recording an activity. It meant [AJAX](https://en.wikipedia.org/wiki/Ajax_(programming)) requests and [DOM](https://en.wikipedia.org/wiki/Document_Object_Model) updates. But the [way to do it](https://guides.rubyonrails.org/working_with_javascript_in_rails.html) using the classic Rails stack felt so wrong and outdated to me. For instance, I really didn't like the idea of serving JSON to Ajax requests with the same controllers which would also serve regular html requests. For lack of betters words, let's just say it all seemed *hacky* and also very time consuming.

Lately, I had been reading my daily share of articles about pretty much everything related to web development. And it is at this point that the idea of a [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application) querying a back-end suddenly made a lot of sense. Making a traditional Multi Page Application did not anymore. Plus, having a truly distinct back-end and front-end seemed a better architectural choice, especially in the long run since it could also serve native mobile apps.

Even though it is [perfectly possible](https://evilmartians.com/chronicles/evil-front-part-1) to pair Rails with a modern front-end solution, I thought it was a good time to reconsider the whole stack I wanted to work with.

## JavaScript == [42](https://www.google.com/search?q=the+answer+to+life+the+universe+and+everything)?

The last decade has all been about JavaScript, steering away from its shallow roots toward a respectable language and ecosystem. I must admit using it to power my back-end still seems really strange as I have not yet played with [Node.js](https://nodejs.org/en/). Regarding my choice of stack, I don't want to use a [fully-featured framework](http://v4.loopback.io/), and instead go layer by layer to get a good sense of the architecture. So I will start with [Express](https://expressjs.com/) for basic routing and an ORM to handle my relational data.

Now switching to [the specific project's readme](https://github.com/stoneLeaf/timeflies-backend#readme) for insights, and will resume writing here when done.