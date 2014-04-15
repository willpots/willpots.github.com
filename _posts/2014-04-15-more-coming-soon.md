---
layout: post
title: "MiddMap: A New Middlebury Events Calendar"
date: 2014-04-15  4:35 pm
categories: nothing
---

Given my interest in mapping and software development, I like showing traditionally non-spatial applications in a spatial manner. A few months back, I tried to redesign the Middlebury College events calendar by centering it around a map rather than a calendar or feed.

An alternative to the traditional events calendar, MiddMap shows Middlebury College events happening in the future. Using the official Middlebury events feed, MiddMap parses the "location" field and translations a placename to geographic coordinates. The site also allows for events to be filtered by start time.

Currently, events are only ingested from the official college feed, but I intend to allow individual users to pull in their personal Facebook feeds as well as add their own events to the calendar. I'll also be adding an iPhone app at some point soon.

Visit the site at [www.middmap.com](http://www.middmap.com). I'd love to hear any thoughts you may have -- dev {at} willpots {dotcom}.

Code can be found [here](https://github.com/willpots/middmap).