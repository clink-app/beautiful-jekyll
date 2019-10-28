---
layout: post
title: User Experience Research Overview
---

# **Clink! Creating Community through Connection**

## Team:
- Phoebe Huang: Designer and Researcher
- Michaela Smith: Designer and Researcher
- Vy Nguyen: Designer and Researcher


## **Problem and Solution Overview**

The problem we focus on is the difficulty surrounding finding ways to engage in community life. Our [CI review](https://clink-app.github.io/2019-10-02-CI_review/) showed us that three main pain points felt by those looking to engage in community activities and events (both on and off campus) are related to 1.) convenience, 2.) accessibility of information, and 3.) personalization. These three points are closely connected, as convenience largely includes the ease with which information can be attained and the degree to which the things you learn about are tailored to your interest. It also involves other difficulties, such as scheduling activities you’d want to do with others, and the tedious work of keeping track of which events you’re interested in. As a result of these findings, our solution focuses on mitigating these constraints. It will be in the form of a mobile app, and will provide the user with customizable, personalized information about events near them. The main purpose will be to increase the ease with which users can access and save information, and to limit the information they receive to a manageable amount. Events can be tagged to a physical location, so users can see on a map where events take place, or become aware of something they may not have known about otherwise. For users who want to do as little work as possible, the app will also be able to give recommendations about what events are a best match based on the user’s past selections and ratings. This means that with almost no effort on the part of the user (they do need to set up their preferences), they would still be able to get personally tailored event recommendations that fit their schedule.


## **Design Research Goals, Stakeholders, and Participants**

The goal of our design research was to learn more about the context surrounding our problem: what different parties were involved, and who could be helped by a solution? What were the things that contributed to the problem, and what solutions were there already? Where did people feel that there needed to be better solutions? The three main participants in our design research (described [here](https://clink-app.github.io/2019-10-02-CI_review/) in sections marked *process* and *research participants*) were NW, PC, and JM; each of these people came from different groups of stakeholders. PC is the director of CLiA, and works very closely with both community members wanting to attract students (and other community members) to their events and with students. She serves as a main point of connection between these groups, and so is aware of the difficulties each face. NW is a student at Williams who also works with CLiA’s communications office. They are exposed to many of the same stakeholders that PC is, but as a student, was able to provide more in-depth insight into the student perspective. JM works with the music department, and is in charge of publicizing events. Their audience includes both students and members of the broader community, and they’ve tried many different methods of publication to see what gets the best results from different groups. This perspective was helpful because he was able to speak about the challenges faced by those who want to learn about a very specific kind of event.


## **Design Research Results and Themes**

The results from our design research included a number of key findings (described in part one, [here](https://clink-app.github.io/2019-10-02-CI_review/)), including:
- Important to encourage good fit between the events and those attending events
- There are many methods for sharing information that attracts different audience groups
- Activities with a variety of participation options are more attractive
- Time and availability are constraints; it’s hard to fit things into a schedule if they are not planned in advance
- Not knowing about events is a significant constraint
- Transportation is a constraint
- There are plenty of opportunities available on/off campus
- Personal connections, personalization, and convenience help people overcome constraints
- Participation can be encouraged with external perks
- Technology proves a significant barrier for many older Williamstown/local residents
We condensed these findings into three main themes, which established the direction we took to design a solution. The main themes, as described in our problem and solution overview, relate to the convenience, accessibility, and personalization of information. Our research showed that current information-gathering mechanisms left users frustrated along these lines and posed a significant barrier to finding ways to engage in community life. As a result, we focused our design around solving these problems.


## **Answers to Task Analysis Questions**

Users: People who are looking for suitable events to attend. Cater to large range of users, from college students to neighborhood members

Present: Established sources of scheduled event listings such as Posters, email lists, and FaceBook pages, or Daily Messages (at Williams)

Desires: A more convenient, accessible and personalized way at looking for events.

Learned: Various forms of community outreaching: posters, fliers, event pages, personal newsletter and Facebook event pages, even face-to-face event introduction (advertisement). There is no universal standard. 

Location: Can be performed anywhere, at anytime. Users can check for events happening at a time and place of their choosing. People updating live events will be at the location of said event to drop their geotag.

Relationship:  Informative and consistent. The goal is for a user to know what is happening that is of interest to them. User will have a wide variety of information about events to look at and take from, provided by the members in the community. User can also post their event to notify others about the opportunity to attend.

Options: Include social media platforms, posters, handbooks, information sessions, or from person to person.

Communication: Through event posts or geotag, through which they can learn more about the organizers and get in contact directly if desired.

Frequency: Events updated every week to keep up with the newest posts and event tags. 

Time Limits: As long as the event posts are updated on time, the rest should be spontaneous, with no delays.

Errors: Users can fall back on the normal event calendar. There can be an implemented Help session that helps users who detect issues report them back to the system.


## **Proposed Design Sketches - “3x4” -**

### Sketch One

Our first proposed design is a minimalist, pared-down design meant to reflect the idea that Clink! helps to streamline and simplify the user’s social life. This design supports the tasks of setting up a time and place to meet with friends, gathering detailed information about an aspect of an event, adding the event to a personal calendar, and scheduling transportation to an event.

![](/img/storyboard_meeting.jpg)

- **Meet a friend**: You can link your personal calendars and select times that work, and after setting a set of meeting criteria, Clink! will find a select set of events or activities that would be the most likely to attract both of you. You both select the events that interest you out of this very select list, and Clink! will display the top selected choice. 

- **Gather more information**: Integration with external source allows the user to press on any word or phrase contained in the event description and gather more information about it. The reference to which the user is directed depends on information access: it may be the site of the original event poster, a community event board with detailed descriptions, or google, if no other resources are available. 

- **Save to calendar**: Easy integration with a personal calendar makes it easy for Clink! to limit its recommendations to events occurring at times the user is available and for the user to easily add events they want to attend to their personal calendar. Here, the user just has to click one button and review the details that Clink! automatically populates, and the event will be added. Then, their default notification settings will alert them when it’s almost event time. 

- **Schedule transportation**: Clink integrates with google maps as well as different transportation platforms, such as Lyft and Uber. This allows the user to see what their transport options are, and select the one that works best for them in terms of time, cost, and preference. If the person is planning to drive, parking availability approximations will be provided.

### Sketch Two

Our second design sketch focuses on making it convenient for the users to manage their own schedules and events. It focuses on the tasks of posting events, sharing events, scheduling events, and scheduling transportation to events. 

![design_check_in2.jpg]({{site.baseurl}}/img/design_check_in2.jpg)

- **Adding an event**: Having an online event form so event organizers can fill them out. We want as many details as possible in order to categorize the event: from event type to time commitment to transportation availability to requirements to join and extra information links. After the user fills out the form, the event will be saved into the database for a time range, and can be searched for by fellow event-lovers.

- **Sharing event**: The main focus of the app is to be able to share event digitally no matter what. As long as the receiver has some form of email address or phone number, the sender can send the information about the event in a compact, PDF-styled form, ready to be viewed. One reason that prevents people from joining event is their unfamiliarity with modern technology, and this approach helps tear down that barrier.

- **Adding event to personal calendar**: The user can add the specific event to their personal calendar, and the app can automatically connect to their Google calendar and add a space for that event. If there is space, then the event can be added smoothly, if there is a time conflict, they can be notified. The app can also set up a notification reminder on the day of the event, along with information to remind the person of the event details.

- **Transportation schedule**: Once a person has indicated they’re interested in going to an event, the transportation schedule system can check whether there are transportation provided by the organization. If there is, it will specify a time and pickup location; if there isn’t, it will inform the user and ask if they want to schedule a uber/lift, and can automatically connect with the uber/lift app and get a car. All the user has to do is hop on and go!


### Sketch Three
Our third design proposal focused on making the individual’s event planning experience more convenient on the host and attendee side. This design focused on the tasks of finding events that match user preferences, publicizing events with attributes that can be searched for, getting passive event recommendations, and arranging transportation.

![](/img/design_3_all.jpg)

- **Search Events Based on Personal Preferences**: General personal preferences for events can by editing the profile. The preferences are automatically applied when the user looks for events. They can add additional temporary filters if they want to narrow their search.

- **Publicize Events for Others to See**: A template is provided for people who want to post an event. They can upload a photo and type in information about the event, like the name, location, time, and description. They can also put tags on the event so people can filter for it.

- **Passively Receive Event Recommendations**: When a long period of free time in the user’s schedule is detected, the user will get a recommendation for an event that fits the time and the user’s preferences.

- **Transportation arrangement**: A user can schedule transportation to any event in their calendar that has a location. When the user selects such an event, they will get a list of several options of transportation and a google map view of their potential path. They can then select a method of transportation and have it scheduled in the app.

We chose our third, mobile design for it’s minimal layout and clear progression from one task to another. It clearly displays what features users can engage with, including the tasks that are central to the purpose of the app as well as the supporting features, such as personalization of one’s profile to include what event specifications and search parameters should be the default.

The two tasks that we chose for our final design are manually searching for events based on interest, and giving event recommendations based on user interest and time availability. We chose these tasks because they are the most central to what we hope to accomplish: connecting people with community events. The first allows the user to perform a manual search themselves. This would be done when they want to personally survey their options and optimize their event choice, or if they are looking for some very particular kind of event. The second task focuses on giving recommendations that meet the specifications users lay out with regards to their personal interests, and suggests only the top matches for the user. The recommendation system integrates with the user’s personal calendar, so that recommendations are only made for events during times that the user is free and able to attend. Both the recommendation and the search are limited to the events meeting the interest, duration, and other specifications that the user has outlined in their profile. 


## **Written Scenarios- “1x2”**

Scenario 1 (represented by Storyboard 1):
Sam has an empty schedule and wants to fill it with an activity. They use Clink! to check what events are going around them. Since there are too many events that show up, they add some filters to their profile so Clink! can show them only events related to their interests, which are animals and music. They also usually don't go to sport events but are feeling unusually sporty today so they add a temporary sport filter. Clink! then shows them all events that relate to animals, music, and sports. They check the events available again and see a baseball game they want to go to. They add the baseball game to their event list and now they have something fun to do today!

Scenario 2 (represented by Storyboard 2):
The same user from scenario 1, Sam, is watching YouTube when they get a notification from their phone. The notification lets them know that Clink! has found a 5 hour chunk of free time in their schedule and has found some activities that would fit perfectly into that slot. Sam taps the notification and is taken to a Clink! app page with three event suggestions that fit their interests and time constraints in their profile and schedule. Sam sees a dog lovers meeting that sounds interesting and taps on it to check event details, since they only want to go if it is close by. It turns out the event is close by! They then add it to their event list. They now have a fun event to go to!

## **Storyboards of the selected design**

### Storyboard 1, corresponding to scenario 1.
![](/img/revised_storyboard_1.jpg)


### Storyboard 2, corresponding to scenario 2.
![](/img/revised_storyboard_2.jpg)
