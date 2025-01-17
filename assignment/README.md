# Final Project Proposal

Your assignment this week is to write a proposal for your final project.
In proposing your final, try to address each of the following areas.
Please produce at least a paragraph which addresses the topics below

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

<br>
I will use the MUSA practirum project as my final project.  Our application aims to visualize how the bikelanes will influence the number of bike trips. 
<br>
Ideally, the users are able to:
<ul>
<i>Select some features, like the distance to the closest bikelanes</i>
<i>Select the region: like neighborhoods</i>
<i>Whether to add bikelanes or not</i>
</ul>

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?
If your data is too large to be conveniently used on the frontend, how will
you work around it? A backend? Vector tiles? Chat with me ASAP if this is
something you need help with!

<br>
In the practirum, we use the NYC DOT data, which are tracks of GIS bike trips and LION data, which are routes and bikelanes in New York City. The size of datasets are very large, so we will limit our analyze on Sep1st-Sep15th. Moreover, in order to avoid long processing time of calculations, I will save the data, and the produced features into cloud. 


## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

<br>
I plan to use Leaflet, jquery, underscore, and bootstrap.


## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
- What do they gain from your application' use?
- Are there any website/application examples in the wild to which you can compare your final?


<br>
The users will be city plannars, and people who are interested in local infrastructures.
They will have a sense about how added bikelanes will influence the bike trips inside the city.
Would be similar to: https://hanyongxu.com/rmd/austin/index.html


#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

<br>
The sidebar will divide into two parts. One is the choices for users, and another is plots that summarizes visualization.
The design will require selections and data manipulation.


## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

<br>
Due to the fact that we are still not finish our model, one difficulity will be the uncertain brought from our model.
Another difficult would be that we are not able to visualize the results very clearly. I plan to have a "fly to" function that zoom into a smaller area, or a single line of bikelane is very hard to visualize.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get help interpreting a technology's
purpose/usage).

I do not have the missing pieces now.

