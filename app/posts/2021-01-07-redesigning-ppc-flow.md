---
title: Redesigning how we ask for an address
description: We look at the user flow for how we ask for an address and what pain points our users currently have. 
date: 2021-01-07
---

We believe that redesigining PPC online user flow based on pain points & user feedback will be a useful feature for users as it will create a better user experience while purchasing a PPC. This will help users to quickly and easily obtain help with health costs.

What we reviewed:

* Re-designed 'How long do you want your PPC to last?' screen : broke it into several screens (to follow GDS guidance of 1 question per page)
* Re-designed : When do you want your PPC to start? This screen has been split into 3 different screens to cater 3 different users (New user, User with expiring certificate, User with expired cert) - we believe by displaying information relevant to this type user might be useful to them to ease their user experience (This is following the implementation of the new API Exemtption Search)
* Following user research a user need been identified (link) : added information about Prescription payment refund
* Following user feedback on how many screens it takes to key in address - this has been shortened & simplified

What we plan to test:

* Whether or not users finding it easy to manoeuvre the new user journey
* How do users fill up the new address screen
* How do users find information about 'What option is best for me' in 'How long do you want your PPC to last?' screen
* Do users find it useful having information about their current PPC - is it expired? when is it expiring?
* 2 different screens for 'How would you like to receive your PPC'/ 'Would you like to receive your certificate by email?'
* FP57 - the refund receipts : Do users know this? is it a helpful information to them?

What we found:

* 2 participants welcomed the opening line about saving money
* Start page : 'How it works' section is it a right title?
* New address screen : no partcipant had any issue with the new journey - they all managed to go through it without any problem
* The 3 months option explanation was queried by 2 participants. Both felt it wasn’t clear how much you would save / what your break even point is
* One participant said that it is a pain to have to phone up to change the regular dates. They and another said that many people want to set their outgoing dates to suit their salary dates, so why do we make people phone up to do it?
* The screen - 'Would you like to receive your certificate by email?'- was welcomed by all participants

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Find address screen",
      img: { src: "01-find-address-screen.png" }
    }]
}) }}
