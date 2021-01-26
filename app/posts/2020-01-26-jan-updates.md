---
title: SQP and SLP journey
description: How we designed and test the SQP and SLP journey.
date: 2020-01-05
---

This month we've focused on the SQP and SLP journey. This has been a challenging journey because it meant that we went from a linear journey to a branching journey. However, with a few variations we have now successfully designed, tested and verified a journey which works for our users and this is how we done it.

## Changes to the journey
To introduce the SQP and SLP forms we needed to create an alternative journey as the company number wouldn't exist at this point for those form types.

We considered 3 options:
1. Adding a second start now button on the homepage
2. Adding an additional question in the journey before the company number page
3. Adding a skip link to the company number page

We ruled out the first option as we felt that this would be too confusing to the user seeing two buttons. The problem with the third option is that it allowed the user to skip the company number page for a form type that requires a company number so that left us with option 2.

Our concern with option 2 is that all users would have this question and for those who are not uploading a SQP or SLP document then it is a slight hassle to make an additional decision. This is something we wanted to keep in mind when we went into user research.

## Wording the question

### Option 1
The question would be: **What type of document are you uploading?**

With the answers being:
1. A document to register a Scottish limited partnership or Scottish
qualifying partnership
2. Other type of document

### Option 2
The question would be: **Are you uploading a document to register a Scottish limited partnership or Scottish qualifying partnership?**

With the answers being:
1. Yes
2. No

### Option 3
The question would be: **Does the company or entity you are uploading the document for have a company number?**

With the answers being:
1. Yes
2. No I’m uploading a document to register a Scottish limited partnership or Scottish qualifying partnership

With these options in mind we tested all of them with a range of users and came to the conclusion that **option 2 was the preferred option**. From listening to feedback we believe users preferred this option as there is less cognitive load in the decision making as the user only needs to know the document type they are uploading.

## Conclusion
Overall we felt that we are now in a good position to make changes to the service to enable these form types to be uploaded. We are confident about the journey and the design and content of the question page.

The only downside is that we needed to introduce this question page but it is important the user makes this decision at the point we've put it in as it does impact the pages they see further down the service.
