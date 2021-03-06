---
id: 33
title: 'Tasker and Recording the Location of an Android Device [Part 1]'
date: 2011-04-01T15:57:38+00:00
layout: post
guid: http://www.williamsgodfrey.com/?p=33
permalink: /using-tasker-to-record-the-location-an-android-device-part-1/
dsq_thread_id:
  - 2051221686
categories:
  - Tasker
tags:
  - Android
  - Droid X
  - GPS
  - Location
  - MotionX GPS
  - Stolen Phone
  - Tasker
  - Track
excerpt: "Part 1 of a 2 part series discussing the use of the Tasker application to record the location of a device running Google's Android mobile OS."
comments: true
share: true
---


<span style="color: #808080;"><em>[This is Part 1 of a 2 part series discussing the use of the Tasker application to record the location of a device running Google&#8217;s Android mobile OS. This part discusses what lead me to use the Tasker application; <a href="http://www.williamsgodfrey.com//using-tasker-to-record-the-location-an-android-device-part-2/">Part 2</a> discusses <em>how to set up the Tasker profile </em>and my first impressions.]</em></span>

### Why Tasker?

I have always been intrigued with the idea of one&#8217;s location history, i.e. the path an individual creates throughout a lifetime. I have very specific memories from my childhood of riding in the car with my parents, travelling through the wide open northern Illinois countryside and obsessing over whether I had been on that particular road before. This began, obviously, before I was old enough to begin forming the mental map that we all have in our heads about the areas we live or have lived in so I was never really certain if we were taking a new road or one we had taken many times before. Back then, the best thing I could think of doing to help record the path of my parent&#8217;s car was attaching a stick to the bumper with a piece of chalk on the end of the stick, rubbing on the ground. My idea being that the chalk would draw a line everywhere the car went. Mind you, this was long before consumer GPS devices (Garmin, TomTom, etc), cellphones, or even carphones.

Fast forward about 23 years and I know find myself with a multitude of products available to do exactly what 4 year old me. For example, in 2009, [while riding my bike across the country](http://bikeandbuild2009.wordpress.com/), I attempted to use [MotionX GPS](http://itunes.apple.com/us/app/motionx-gps/id299949744?mt=8) on my iPhone3G to record the route we took. Unfortunately, at that point MotionX GPS was a relatively young piece of software and I found that it ate through my battery power incredibly quickly. (I think I ended up with less than 40% of the total 3,800 mile route recorded.)

<figure>
  <img src="{{ site.url }}/images/Sailing_Practice.jpg" >
  <figcaption>Recording a GPS track during sailing practice on a friend's boat.</figcaption>
</figure>

In 2010, I bought a Motorola Droid X and promptly began using Google&#8217;s [My Tracks](http://mytracks.appspot.com/){.broken_link} to record my bike rides/sailing trips/random trips around town. I found that the software worked much better than MotionX GPS worked on my iPhone; it tended to be easier on my battery and the GPS fix was more accurate and consistent. I sailed from Chicago, IL to New Buffolo, MI during the summer of 2010, a trip of over 10 hours, and the phone&#8217;s battery just barely held up the entire way. The image to the right shows how accurate My Tracks was during a sailing practice in June, 2010.

These pieces of software are really great for recording a very detailed, continuously updated GPS track of a phone, but their battery and CPU use do not make them a practical tool to record the phone&#8217;s location _at all times._ For continuous, passive location monitoring (and recording), I found [Google Latitude](http://en.wikipedia.org/wiki/Google_Latitude) _[Ed. 11/5/2013 &#8211; Latitude has since been discontinued by Google. Even more reason to make your own solution!]_ to be a very useful. Google Latitude is marketed mainly as a geo-social networking tool. The idea being that Google records your location using GPS and wifi and shares that information with friends of your choosing. That way, one can know when, say, a friend from out of town is unexpectedly in the area. Ideally this knowledge will phone call or text and a social gathering of some sort will occur. Latitude is cool, and it does record your phone&#8217;s location at all times, but I don&#8217;t like that _I_ am not incontrol of that data, Google is. I admit that I didn&#8217;t read the EULA when I installed Latitude on my phone, I don&#8217;t even want to know what they are going to use that data for.

I eventually decided that I needed to find something that would record my location, like Latitude, spare my battery, unlike My Tracks, and allow me to retain ownership of my location history, unlike Latitude. Enter [Tasker For Android](http://tasker.dinglisch.net/), a deceptively complex piece of software that enables all sorts of automation for devices running Android.
