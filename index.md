---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
venue: "Fermi National Accelerator Laboratory"
address: "online"
country: "us"
language: "en"
latitude: "45"
longitude: "-1"
humandate: "January 26, 2023"
humantime: "8:00 am - 11:30 am"
startdate: "2023-01-26"
enddate: "2023-01-26"
instructor: ["Claire David", "Michael Kirby"]
helper: ["mentor1", "mentor2"]
email: ["claire.david@cern.ch","mkirby@fnal.gov"]
collaborative_notes: "2023-01-26-dune"
eventbrite:
---

The aim of this tutorial is to provide participants an expedited opportunity to learn the basics of DUNE Computing.  A similar half-day session was presented in [December 2021](https://dune.github.io/computing-training-202112) from which this site extends.  A three half-day version  of this tutorial was offered in [May 2021](https://dune.github.io/computing-training-202105/), and a recent two-day version in [May 2022](https://dune.github.io/computing-training-basics) and may prove to be a reference. 

Here our schedule spans two parts, and advise your complete attention throughout.

<!-- this is an html comment -->

{% comment %} This is a comment in Liquid {% endcomment %}

> ## Prerequisites
>
> Command line experience is necessary for this training. We recommend the
> participants to go through
> [The Unix Shell](https://swcarpentry.github.io/shell-novice/), if new to the
> command line (also known as terminal or shell).  
{: .prereq}

By the end of this workshop, participants will know how to:

* Utilize data volumes at FNAL.
* Understand good data management practices.
* Provide a basic overview of art and LArSoft to a new researcher.
* Develop configuration files to control batch jobs.
* Monitor jobs submitted to the grid.

> ## Getting Started
>
> First step: follow the directions in the "[Setup](
> {{ page.root }}/setup.html)" to arrived prepared for this event. Follow the instructions; we give you an easy exercise 
> to make sure you are good to go.
{: .callout}

<h2>These pages are a mockup of an upcoming computing tutorial</h2>

You will need a valid FNAL or CERN account to be able to do the tutorial and be on the DUNE Collaboration member list. If you do not, contact your team leader.


<h3 id="schedule">Schedule for Thursday, January 26, 2023, 8:00 am - 11:30 pm (CST/GMT-6)</h3>


{% comment %}
{% include custom_schedule3.html %}
<center><img  alt="" src="fig/Schedule_computing_training_202105.png"/></center>
An [asynchronous session]({{site.baseurl}}/asynchronous/) is designed as later day acivities for the first two days of the workshop.
Schedule
{% include sc/schedule.html %}
Syllabus
{% include sc/syllabus.html %}
Intro 
{% include sc/intro.html %}
{% endcomment %}


{% include links.md %}
