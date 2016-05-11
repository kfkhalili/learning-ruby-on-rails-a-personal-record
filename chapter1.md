# Chapter 1 From zero to deploy

Valuable information from the first chapter.

> If you are new to the subject, the Ruby on Rails Tutorial will give you a thorough introduction to web application development, including a basic grounding in Ruby, Rails, HTML & CSS, databases, version control, testing, and deployment—sufficient to launch you on a career as a web developer or technology entrepreneur.

My Ruby is not terrible. My HTML, CSS, and JavaScript skills are fledgling. I understand databases and my SQL is pretty good. I can use Git as well as any person so that's all good. I understand Test Driven Development, more or less. This part of the book would be helpful.

> On the other hand, if you already know web development, this book will quickly teach you the essentials of the Rails framework, including MVC and REST, generators, migrations, routing, and embedded Ruby.

I know MVC well enough, but have never implemented it in code, and I know little about REST, or the rest of the things he mentions.

> The Ruby on Rails Tutorial takes an integrated approach to web development by building three example applications of increasing sophistication, starting with a minimal hello app (Section 1.3), a slightly more capable toy app (Chapter 2), and a real sample app (Chapter 3 through Chapter 12).

Nice so we'll do some work, the first app will probably be lame, the second one could be more interesting. The third will be more challenging for sure.

Reading a little deeper reveals that the third website will be a lot like twitter, that will be useful for my future projects. Mr Hartl assures us that we will learn generic principles, which are always the best to learn. He also says that your skills don't need to be high and that the book has proven to be pretty popular with complete beginners. He also promises to have made changes that aim to "lower the barrier to getting started with Rails"

First chapter task is to install necessary software and setup the git repository. We will conclude the task with deploying our first simple app to the web, I guess on Heroku. We will not be using much scaffolding in the beginning. He says it is a feature that generates code and might seem easier but can mess you up if you're a beginner trying to understand the basics.

The second chapter is about the second, more serious project. This chapter will explain the basic workings of a Rails application. We will use scaffolding here to generate code for the app.

The third chapter onto the end of the tutorial will be about building the twitter-like website and learning a whole lot. The second app will evolve into the third and final, sample app.


## Introduction

* In 2004, David Heinemeier Hansson wrote the Rails framework using the Ruby programming language. It has evolved into a powerful tool, used in multi-million dollar companies. 
* Since then, the Ruby on Rails framework has grown to be so large that it pretty much has its own chunk of the web development industry.
* It is 100% open-source, available under the MIT License.
* Rails relies on awesome Ruby.
* Rails creates a domain-specific language for writing web applications. This means that generating data models and routing URLs is simpler with Rails. This leads to rapid web development.
*  Full use of REST architectural style for structuring web applications.
*  Rails creator always updates the library and that means new features.
*  Rails has a very active community so googling errors helps a lot.


### Prerequisites

* The tutorial is self-sufficient. Sounds good.
* Having a background in HTML and programming helps. I'm safe.
* He repeats that complete beginners have completed his tutorial. Reassuring.
* He says doing the tutorial twice has helped some people. Yeah, maaaaaybe.
* If you have no programming experience, you should learn Ruby. No problem here.
* If you're excited about making web apps and don't want to wait, then there is a tutorial called [Try Ruby](http://tryruby.org/) that one can try.
* By the end of the tutorial, we'll be intermediate to advanced in skill and ready for more advanced resources.

### Conventions in this book

This section has details about how information and code are displayed. Skimming through.

* $ means Unix-style terminal.
* We follow the / style of UNIX file systems.
* We specify path of the files within the app directory, not globally.
* Google your errors.
* The tutorial covers testing Rails apps. Code for failing tests is in red and for passing tests in green.
* We will complete the exercises, though they are optional. The more exercise the better.

## Up and running

### Development environment

We'll use the cloud integrated development environment, [Cloud9](http://c9.io/). We get a text editor, file system navigator, and a command line interface for free.

In this stage, we create the environment on Cloud9, and install Rails.

To install Ruby on Rails with a specific version.

$ gem install rails -v 4.2.2

## The first application

To create our first app, with a specific version.
```$ rails _4.2.2_ new hello_app```



The ```rails``` command creates files and directories and is part of the advantages of convention over configuration. Benefits include being able to navigate other people's projects



