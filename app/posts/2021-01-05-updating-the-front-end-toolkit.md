---
title: Updating the front end toolkit
description: The BSA elements toolkit is now outdated and we're planning to move to the NHS Digital front end toolkit. 
date: 2021-01-05
---

We believe that redesigining PPC online with the NHSUK Front end Kit will be a useful feature for users as it will create familiarity and trust with users with the NHS branding. 

It is also up to date with the accessiblity point of view as well as being more recognisable and trustworthy to end users.

This will help users to confidently use the service.

What we reviewed:

* Created a back link
* Removed the cancel link
* Content in the Start page
* Following GDS guidance changed 'Next' label to 'Continue'

You can see an example of some of the pages that have been updated below. 

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Start page - Elements kit",
      img: { src: "01-start-page-old.png" }
    }, {
      text: "Start page - NHS.UK frontend",
      img: { src: "02-start-page-new.png" }
    }, {
      text: "Name page - Elements kit",
      img: { src: "03-name-page-old.png" }
    }, {
      text: "Name page - NHS.UK frontend",
      img: { src: "04-name-page-new.png" }
    }, {
      text: "Dob page - Elements kit",
      img: { src: "05-dob-page-old.png" }
    }, {
      text: "Dob page - NHS.UK frontend",
      img: { src: "06-dob-page-new.png" }
    }]
}) }}
