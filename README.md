# Schedule application

## Weekly calendar

Mikko is in need of an application where he can plan his daily schedule between 8 and 16. He doesn't want to plan the weekends, but only the 5 weekly working days. Right now he's on vacation so he's just testing it for fun with his friends and their hobbies. But he actually wants to use it at work only for himself to plan his daily meetings. Somehow he finds the calendar app not useful for him, don't ask why.

The app is very simple, it doesn't require login, because he's using it only for himself, neither does it require notifications.

The app must display a calendar week view only with the 5 working days, from Monday to Friday, and times on the vertical axis between 8:00 - 16:00.




Events are added by clicking on a free space inside a day box. In this case the dialog designed on the next page of this document should open and Mikko can fill it with the details of the event.


If Mikko clicks on an existing event which is in the future, and it hasn't passed already, then the same dialog appears, the event's details are filled in automatically, and he can edit the event.


Each event can start only at a fixed hour, so he should be restricted from adding 8:30 for example, but only 8:00. Also no event can overlap another event, because he can not be in 2 places at the same time.






For the event, Mikko must set a date, start time and end time. The event thus can not extend from one day to another. It also can not start before 8 in the morning nor can it end after 16 in the afternoon.

Mikko can also specify who are the friends or colleagues he's expecting to participate in the event. He can write the name of the person in the Add participant field and press the + button to add it to the list of participants for the current event. At the same time, if the name does not exist in the database it will be saved automatically so that next time when Mikko starts writing the friend's name, it will appear in a drop down list, below the Add participant field, and from there it can just be selected.



Thus, when Mikko is typing in the Add participant field, the application must search in the database all friends starting with the typed text and display them in a popover box, just below the Add participant field and over the list of selected participants.




If Save is pressed the event is saved in the database together with the list of participants for the current event, and immediately displayed in the weekly calendar view.


If the Cancel button is pressed, ask for confirmation in case changes are made.


Mikko can navigate through the weeks of the calendar using the left / right buttons and also select the current week from the button in the middle lower part of the page.



The current day should be made visible by using a specific style on the day’s identifier on top of it’s box or the box itself.
