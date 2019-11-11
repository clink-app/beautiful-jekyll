---
layout: post
title: Usability Testing Review
published: true
---

# Our Tests





# Results

### Test 1

| problem          | severity         |
|------------------ | ------------------ |
| 1. Not clear whether filters will be applied when added  |  3  |
| 2. Not clear that user is meant to type in filters page  |  2  |
| 3. Not clear that header icons could be clicked          |  2  |


### Test 2

| problem          | severity         |
|------------------ | ------------------ |
| 1. Unsure about the difference between "apply" and "(x)" on filter menu  |  4  |
| 2. (Still) not clear that user is meant to type in filters page  |  2  |
| 3. meaning of "quick find" unclear        |  4  |
| 4. function of "rate" unclear-- how is it different from like/dislike?        |  3  |


### Test 3

| problem          | severity         |
|------------------ | ------------------ |
| 1. Meaning of "quick find" unclear  |  4  |
| 2. Would be helpful to have "events list" implemented  |  2  |

*Note: the change addressing problem two from the second user test (adding greyed out text signifying that the user can type) was implemented after user test 2, before user test 3.

# Revised Prototype

![user-test-filter]({{site.baseurl}}/img/user-test-filter.jpg)

![Recommended-for-me]({{site.baseurl}}/img/user-test-quick-find.jpg)

# Most Important Changes to Design

**1. Changing “quick find” to “recommended for me”**

All three of our users have trouble with the second task (finding a recommended events) because they aren’t sure of the difference between find events and quick find. We realize that the main purpose of our recommending system is not carried across with this wording, so we decide to change it into “recommended for me”. Now, the distinction between manual looking for events, and asking the recommending system to suggest events based on the user’s calendar is made much more distinguishable.

**2. Changing the position of the Apply button in Filters section**

Originally when the app is designed, the apply and cancel buttons were located at the end, and have an extra cancel signifer (an X) at the top of the page. Through our first usability testing, we realize this is a source of confusion. Our user thinks that simply clicking X will apply the changes to the filter, without noticing the Apply button at the end of the filter section, which only appear when the user scrolls down. As a result, their filters are not applied. We decide to add the Apply button at the top instead, so it is clear to the user when they are making changes to the filters that they need to click Apply in order for the changes to be effective.

**3. Adding textbox signifier in the Filters section**

Our original design has different text boxes in which the user can type in their likes and dislikes; in these respective text boxes stored the tags of their default interests. In our first two usability tests, our users are very unsure about whether it is ok to type inside the same boxes, as they are also occupied by the tags. As a result, they think they can only change the setting inside Profile. We decide to add the signifier that the user can type in the textbox with the sentence “Begin typing your likes/dislikes/locations”. In our third usability test, the user recognizes immediately that this is a space that they can type in.


