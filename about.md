---
layout: page
title: About
permalink: /about/
show_in_nav: true
---

It's about giving it my all.
----------------------------

I'm Courtney Christensen and software development is my passion. I have a keen
interest in all things UX and UI. Great software should be effortless to use,
by design. It must *solve* problems, not create them.

I'm particularly interested in the rapidly changing world of front-end web
technologies. MV* frameworks, web components, server-side Javascript, and real
package managers(!) have all grown up in just the past few years. It's an awesome
time to be into web programming, and this is where is spend most of my development
(and research) time.



At a Glance
-----------

Hover over the bubbles on the timeline. Click on the popups for details from [my resume](/resume).


<svg class="timeline" height="200" viewbox="-50,0 1100,200" 
  xmlns="http://www.w3.org/2000/svg"
  xmlns:xlink="http://www.w3.org/1999/xlink"
  preserveAspectRatio="xMinYMax meet"
>
  <defs>
    <circle id="event-bubble" cx="0" cy="0" r="8" class="event-bubble" />
    <polyline id="event-desc" points="-4,-6.5 -25,-30 -70,-30, -70,-100 350,-100 350,-30 -6.5,-30 -4,-6.5" class="event-bubble-desc" />
  </defs>

  <filter id="dropshadow" height="130%">
    <feGaussianBlur in="SourceAlpha" stdDeviation="1"/> <!-- stdDeviation is how much to blur -->
    <feOffset dx="1" dy="1" result="offsetblur"/> <!-- how much to offset -->
    <feMerge> 
      <feMergeNode/> <!-- this contains the offset blurred image -->
      <feMergeNode in="SourceGraphic"/> <!-- this contains the element that the filter is applied to -->
    </feMerge>
  </filter>

  <polyline points="0,150 1000,150" class="time-axis" />
  <text x="-20" y="180">2006</text>
  <polyline points="0,150 0,160" class="time-axis" />
  <polyline points="100,150 100,160" class="time-axis" />
  <text x="180" y="180">2008</text>
  <polyline points="200,150 200,160" class="time-axis" />
  <polyline points="300,150 300,160" class="time-axis" />
  <text x="380" y="180">2010</text>
  <polyline points="400,150 400,160" class="time-axis" />
  <polyline points="500,150 500,160" class="time-axis" />
  <text x="580" y="180">2012</text>
  <polyline points="600,150 600,160" class="time-axis" />
  <polyline points="700,150 700,160" class="time-axis" />
  <text x="780" y="180">2014</text>
  <polyline points="800,150 800,160" class="time-axis" />
  <polyline points="900,150 900,160" class="time-axis" />
  <polyline points="1000,150 1000,160" class="time-axis" />
  <text x="980" y="180">future!</text>

  <!-- OIT -->
  <use xlink:href="#event-bubble" x="90" y="150" class="event-keyframe oit" />
  <g class="event-desc-holder oit" data-url="/resume/#oit">
    <use xlink:href="#event-desc" x="90" y="150" />
    <text x="35" y="80" class="event-date">December 2006</text>
    <text x="35" y="105" class="event-title">Earned B.S. in Software Engineering, OIT</text>
    <polyline points="90,150 0,150" class="event-span" />
  </g>

  <!-- Alliance -->
  <use xlink:href="#event-bubble" x="110" y="150" class="event-keyframe alliance" />
  <g class="event-desc-holder alliance" data-url="/resume/#alliance">
    <use xlink:href="#event-desc" x="110" y="150" class="alliance" />
    <text x="55" y="80" class="event-date">January 2007</text>
    <text x="55" y="105" class="event-title">First software job, Alliance Engineering</text>
    <polyline points="110,150 410,150" class="event-span" />
    <!-- <text x="55" y="100" class="event-learn-more alliance">(click for more)</text> -->
  </g>

  <!-- ViewPlus -->
  <use xlink:href="#event-bubble" x="410" y="150" class="event-keyframe viewplus" />
  <g class="event-desc-holder viewplus" data-url="/resume/#viewplus">
    <use xlink:href="#event-desc" x="410" y="150" class="viewplus" />
    <text x="355" y="80" class="event-date">February 2010</text>
    <text x="355" y="105" class="event-title">Started as accessibility R&amp;D dev at ViewPlus</text>
    <polyline points="410,150 650,150" class="event-span" />
  </g>

  <!-- Nant -->
  <use xlink:href="#event-bubble" x="650" y="150" class="event-keyframe nant" />
  <g class="event-desc-holder nant" data-url="/resume/#nanthealth">
    <use xlink:href="#event-desc" x="650" y="150" class="nant" />
    <text x="595" y="80" class="event-date">June 2012</text>
    <text x="595" y="105" class="event-title">Started developing enterprise web GUIs, iSirona</text>
    <polyline points="650,150 850,150" class="event-span" />
  </g>

  <!-- Interactive Ticketing -->
  <use xlink:href="#event-bubble" x="850" y="150" class="event-keyframe nant" />
  <g class="event-desc-holder its" data-url="/resume/#its">
    <use xlink:href="#event-desc" x="850" y="150" class="its" />
    <text x="795" y="80" class="event-date">Aug 2014</text>
    <text x="795" y="105" class="event-title">Started SPA overhauls, Interactive Ticketing</text>
    <polyline points="850,150 950,150" class="event-span" />
  </g>
</svg>


Contact
-------

Want to contact me about a position? Have a question about a project? Send an
email to [zourtney@gmail.com](mailto:zourtney@gmail.com) or contact me via
[StackOverflow Careers](http://careers.stackoverflow.com/zourtney).

Also, be sure to check out [my resume](/resume) page!