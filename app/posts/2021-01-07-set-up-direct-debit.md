---
title: Set up direct debit when all pay fails
description: We look at how users can continue their journey when the external All pay fails to process a payment due to their systems being down. 
date: 2021-01-07
---

**Hypothesis**

We believe that allowing users to still get their PPC when All Pay failed to process the payment due to system being down (after user's bank details been checked) will be a useful feature for users as it will allow them to get help with their health costs and start purchasing their prescriptions.

**What we reviewed:**

* Content : Review the Done page
* New page: Done page when All Pay failed to set up a DD
* Further review on FP57 - refund receipt
* Review on whether it is needed to move DD details (on when payment will be taken) to Bank Details (Set up DD) screen from the current screen to avoid cognitive overload & to avoid long information in an conditional reveal
* Content : Information on renewal for users who choose to pay via DD
* Review on any other alternative option for users to save keep their cert.User feedback : User can't print because they don't have a printer and they don't have an email.
* Review : DD Guarantee and DD Instructions; on where and is it needed to have this in the service
* Following user feedback about calling in to change their DD date : Review the process (Moved to future iteration)
* Used the 'Warning card' from NHS service manual to display the DD payment Terms and condition

**What we plan to test:**

* Done page for different scenarios
* Save Certificate option - is it useful for users?
* Following extensive investigation about DD Guarantee & DD Instruction (this is a legal requirement) - decided to put DD in an expander and AB tested the DD Instruction both in an expander and display
* Whether or not the usage of 'Warning Card' in the CYA was appropriate

**What we found:**

* Participants found the payment summary with DD Details in "Set up DD" page to very useful
* 1 participant found that information about DD and auto renewal in 'How do you want to pay for your PPC?' page to be useful
* 2 participants expressed and questioned about the 10 payments ('Would it not be better if it is made 12 - it will bring down the cost further') - the rule behind 10 monthly payments is stipulated in the legislation. The team agreed to further investigate this
* 2 participants welcomed the choice to print the certificate although 1 was confused with the symbol of save; he thought it was an email.
* No participant read the DD Guarantee & no participant read the DD Instruction in the explander; but acknowledged the displayed DD Instruction
* Although the CYA page was long - participants accepted it and stop to read the 'yellow box'(Warning Card)

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Set up direct debit",
      img: { src: "01-set-up-direct-debit.png" }
    }, {
      text: "Done page - Email cert",
      img: { src: "02-done-page-email.png" }
    }, {
      text: "Done page - Print cert",
      img: { src: "03-done-page-print.png" }
    }]
}) }}
