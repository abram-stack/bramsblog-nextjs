---
title: "Landing Page for Cloud Hosting using HTML, CSS and Js"
date: "2022-03-29"
---

_Namaste.._
Uuuh.. Finally, i just finished the winter semester which was pretty much exhausting. I've had this project from the University about Wireless Sensor Network, which to be honest quite challenging, how to build and connecting all the sensor using the Zigbee microcontroller, and at the end using the raspberry pi as server. Luckily with great team efforts we managed it!!

I've been meaning to post about my project in my last post, it will come out soon!!
Little sneek peak, we are going to create our backend application using node.js and InfluxDB as our database, since we are dealing with timeseries data, so every measurements that has been recorded will have the timestamp as their "unique" id.

Anyway, i have no more exams and modules left this semester, and i am still looking for my internship, soo wish me luck that i'll get it soon. Alright enought talking, now i am basically have more time which is... yeaah! making some side projects! !!
it's been quite sometime and i want to refresh again my **HTML, CS and JS**.

This landing page is built only with HTML, CS and JS, well very small JS code. A little recap about this project is we will use the JS script to get the DOM and render it dynamically, so we can get nice and easy collapsible component.
I also use normalize.css which is some kind of css helper that helps to make it "normal" when create page from scratch
To build this project into production, we will use parcel-bundler.
In order to install parcel-bundler we need to install use npm first. I am using version 1.12.3
We will host our website to netlify with their basic price which cost **nothing**. Awesome right!?

```
  npm install -D parcel-bundler@1.12.3
```

To build the project then we will need to run some script and add it into our package.json
One thing we can also do is to install parcel-bundler globally
if you are working with Mac or Linux

```
  sudo npm i -g parcel-bundler@1.12.3

  parcel build index.html

  npm run build
```

---

Well, the story goes on.. stay tune, as i will put some more details on it.
while you are here check the actual landing page that i already hosting it using netlify online, and for free by the way..

> Credit to Mosh Hamedani, he is well known as youtube creator Programming with Mosh, incredible teacher! I have learnt lot of programming, my computer science study journey from Mosh!

[Cloud Hosting Landing Page](https://cloudlandingpage.netlify.app "Cloud Hosting Landing Page")

Thanks for reading! :D
