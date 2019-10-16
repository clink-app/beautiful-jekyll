---
layout: post
title: Project Design Check In
subtitle: Updated tasks and design sketches
published: true
---

## Task recap:

1. Search Events based on personal preferences
2. Easily access detailed information
3. Publicize events for others to see
4. Share events with friends
5. Easily add events to personal calendar
6. Passively receive event recommendations



**New (novel!) tasks:**

7. Transportation arrangement -- increase the convenience of attending events by allowing Clink! to book your transportation (e.g. call an Uber that allows you to arrive by x time, tell you which time you should catch the train in order to make the proper connections). This would be a two-way integration, so Clink! could also see and help schedule transportation for events you have listed on your personal calendar. 
8. Rendezvous scheduling. It’s always hard to find a time to meet up with friends (both new and old) and even harder to try and find something that you’d both like to do. Since Clink! would have the information described in (3) about all its users, it would find free periods in each person’s schedule and automatically generate options for events that would most interest you both. You could specify the type of event you’d like to plan for (need a quiet space to catch up? Want to do something active/ adventurous? Need to stay indoors?) and Clink! will do the rest, including arranging transportation, and letting the other party know if someone is running early or late. 


## Sketch One

This is a minimalist, pared-down design meant to reflect the idea that Clink! helps to streamline and simplify the users life. We do this by making it as convenient as possible to find and attend events. This design highlights this  convenience factor in all parts of the process by focusing on one main (new) task: effortlessly setting up a time to meet with a friend. It can be very hard for friends to find time to meet, whether they are catching up after a long time apart or just looking for something new to do, and it can be even more difficult to find and decide on what to do while spending time together. Clink!’s meet a friend feature makes this effortless when two users are looking to meet. This storyboard shows the process of using this feature as well as the features that allow you to gather more detailed information, add the event to your personal calendar, and schedule transportation to get you there.


![](/img/storyboard_meeting.jpg)

- **Meet a friend**: You can link your personal calendars and select times that work, and after setting a set of meeting criteria, Clink! will find a select set of events or activities that would be the most likely to attract both of you. You both select the events that interest you out of this very select list, and Clink! will display the top selected choice. 

- **Gather more information**: Integration with external source allows the user to press on any word or phrase contained in the event description and gather more information about it. The reference to which the user is directed depends on information access: it may be the site of the original event poster, a community event board with detailed descriptions, or google, if no other resources are available. 

- **Save to calendar**: Easy integration with a personal calendar makes it easy for Clink! to limit its recommendations to events occurring at times the user is available and for the user to easily add events they want to attend to their personal calendar. Here, the user just has to click one button and review the details that Clink! automatically populates, and the event will be added. Then, their default notification settings will alert them when it’s almost event time. 

- **Schedule transportation**: Clink integrates with google maps as well as different transportation platforms, such as lyft and uber. This allows the user to see what their transport options are, and select the one that works best for them in terms of time, cost, and preference. If the person is planning to drive, parking availability approximations will be provided.

## Sketch Two

This sketch illustrates how the design is meant to make it convenient for the users to post, share, schedule event and transportation to the event. One of the main issues we encounter during our contextual inquiries is that the reason behind most people’s refusal to attend community events is because of time management or transportation schedule. The app is meant to resolve this problem by having a reminder to the user that the event is happening, and schedule a form of transportation for them if needed. The ability to create events and share that event is also essential to our app design. One difficulty would be that while we’re trying to make it easier for the user to fill out their event information, we still would like to get as much information as possible in order to categorize this event for other users who might be looking for it. Sharing the event as a newsletter (PDF) form also helps the event receiver to just receive the event without the need to sign up for the app. 

![design_check_in2.jpg]({{site.baseurl}}/img/design_check_in2.jpg)

- **Adding an event**: Having an online event form so event organizers can fill them out. We want as many details as possible in order to categorize the event: from event type to time commitment to transportation availability to requirements to join and extra information links. After the user fills out the form, the event will be saved into the database for a time range, and can be searched for by fellow event-lovers.

- **Sharing event**: The main focus of the app is to be able to share event digitally no matter what. As long as the receiver has some form of email address or phone number, the sender can send the information about the event in a compact, PDF-styled form, ready to be viewed. One reason that prevents people from joining event is their unfamiliarity with modern technology, and this approach helps tear down that barrier.

- **Adding event to personal calendar**: The user can add the specific event to their personal calendar, and the app can automatically connect to their Google calendar and add a space for that event. If there is space, then the event can be added smoothly, if there is a time conflict, they can be notified. The app can also set up a notification reminder on the day of the event, along with information to remind the person of the event details.

- **Transportation schedule**: Once a person has indicated they’re interested in going to an event, the transportation schedule system can check whether there are transportation provided by the organization. If there is, it will specify a time and pickup location; if there isn’t, it will inform the user and ask if they want to schedule a uber/lift, and can automatically connect with the uber/lift app and get a car. All the user has to do is hop on and go!

## Sketch Three
Clink would work well as an app for a smartphone or tablet because it should be mobile and has features that rely on location services and wifi to function. The home page of the app has four buttons that directly correlate with the four main tasks this design focuses on. This design’s focuses on tasks that make finding, scheduling, and getting to events an easier and more personalized process. The user can look at their calendar of all events and have the app schedule them transportation. They can also set their interests and dislikes in their profile so that when they look for events, there is already a preliminary filter. They can then use the additional filter on the preliminary list of events if there is anything they are looking for in particular on a specific day. A user can also post an event to share it with other users of Clink. Lastly, the user can get a list of recommended events based on their marked interests, availability, and past events they have participated in. This design and tasks that it focuses on are very much for the individual experience. The filterable event list reduces the effect of information overload on the user, which was a problem we heard about from one of our contextual inquiries. A recommended list makes it even easier for the user to find events that they want to participate in, since the list has been curated to reflect the user’s past choices and preferences. Being able to post events keeps Clink’s database full with a lot of events for users to choose from. It also allows the hosts of events to advertise their activities and get new participants or meet new people. Transportation was another big issue we heard about from our contextual inquiries, so having a transportation scheduler should mitigate that problem somewhat and allow users to go to more events.

![](/img/design_3_all.jpg)

- **Search Events Based on Personal Preferences**: General personal preferences can be set by clicking on the profile icon in the header and then clicking the pencil in the bottom right corner of the profile page. The user can write in tags for things they are interested in and things they dislike. They can also set their location. To return to the home page, click the Clink logo or name in the header. To see a list of events, click the “Events” button. The information saved on the profile page is automatically applied to the events Clink has, so the list that shows has already been filtered. By clicking the “+ Filter” button on the side, the user can manually put in extra preferences for the events that show.

![](/img/design_3_preferences.jpg)

- **Publicize Events for Others to See**: On the home page, there is a “Post” button. Clicking it will lead to a template for an event where the user can upload a photo and type in information about the event, like the name, location, time, and description. They can also put tags on the event so people can filter for it. Once a user finishes editing, they can clock the check mark at the bottom and post it.

![](/img/design_3_post.jpg)

- **Passively Receive Event Recommendations**: The recommendations button on the home page leads to a page with a list of recommended events that fall within a long period of free time in the user’s schedule. Clicking on one of the events listed opens up a more detailed event page where they can learn more about the event.

![](/img/design_3_rec.jpg)

-**Transportation arrangement**: Clink will have access to a person’s calendar and all the events that have been scheduled on it, regardless of whether it was scheduled through Clink. Clicking the calendar button on the home page leads to a view of the user’s calendar and all the events that have been scheduled. Clicking on an event expands its description and brings it to the front and center. A button in the shape of a car will be right beneath the expanded description of the event, if there was a location provided. Clicking the button will open the transportation page, which lists several options of transportation and a google map view of your potential path. Choosing an option will lead to a confirmation page, and a receipt if a purchase was made.

![](/img/design_3_calender.jpg)
