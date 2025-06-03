---
homepage: true
layout: main
title: Blog test
eleventyNavigation:
  key: Principles
---

{% from "govuk/components/phase-banner/macro.njk" import govukPhaseBanner %}

{{ govukPhaseBanner({
  tag: {
    text: "Version 1.0"
  },
  html: 'Test test</a>.'
}) }}

* * *

![A picture of bristol looking up the bristol channel, there are colourful houses on the horizon and a boat in the middle distance.](/assets/images/bristol.jpg)
