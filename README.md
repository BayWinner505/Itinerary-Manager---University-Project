# Itinerary-Manager---University-Project
Itinerary Manager - University Project
''''
----------------------------------------
Scenario
------------------------------------------------------------------------------
Exciting Activities Ltd is a company that specialises in organising interesting
activities for individual and corporate clients. They want a system to manage these
activities and the attendees more effectively, in particular for calculating the cost.
You are required to design and build a prototype Java application for their activity
planner.

There are various kinds of diverse activities that attendees can sign up for, often
attendees participate in an itinerary of several activities. Some examples include:
• Building a bridge from paper
• SAS-style assault courses
• Cookery classes
• etc.
Each activity has as a minimum the following information:
• Base-cost (i.e. the cost before any discount is applied)
Object-Oriented Programming CIS1068-N 4 of 24
• Title,
• General description of the activity
• Location
• Date/time
• Expected duration
Exciting Activities Ltd has a pricing scheme offering discounts based upon the number
attendees and number of activities taken – see the table below.
Activity Itinerary Cost Table
Attendees
Activities < 5 6 to 10 11+
1 – 3 0% 4% 8%
4 – 6 4% 8% 12%
7+ 8% 12% 20%
Activity and Itinerary Add-ons
In addition to the basic activities and itineraries, attendees can optionally add-on
additional services each comes with an additional cost.
Examples of activity add-ons:
• Travel
• Insurance
• Photography
• Etc.
Examples of itinerary add-ons:
• Accommodation
• Coffee/Tea breaks
Object-Oriented Programming CIS1068-N 5 of 24
• Lunch
The overall cost paid charged is calculated by the total cost of each of the activities +
add-on costs + itinerary add-on costs – discount.
