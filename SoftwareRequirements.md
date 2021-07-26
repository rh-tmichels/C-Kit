# Software requirements for the C-Kit

## Operating system (OS)

These requirements **ALWAYS** overwrite any feature or "nice-to-have" or what is not absolutely necessary.

1. The OS must provide all necessary functionality for the basic operation of C-Kit.
2. The OS must be easy to maintain
3. The OS must be as small as possible, so there are as many resources available as possible.
4. The OS must be rock solid and reliable.
5. The OS must be fast
6. The OS must boot as fast as sensible in regards to the requirements mentioned above.
7. The OS shall be a version of linux
8. The OS **MUST BE FREE OF ANY COST AND OPEN SOURCE** until the end of time. Period!
9. The OS should be able to be operated in different languages. English is default.

## Webserver
For the easiest access and most commonly usage, the complete content will be provided as static HTML pages. 
This is for most reliable service and least consumption of resources and power.
The Webserver shall consume as few resources as possible. 

## Proxy
There will be a customized proxy, with a limited set of resources like RAM, CPU ...
**The proxy will block absolutely ANY SOCIAL MEDIA like Facebook, Instagram, Youtube, Twitter, etc.**
This is to prevent any unwanted content sent out into the internet (dead bodies, desperate people, ...) and even more important to save bandwith where ever possible.
Even the press and journalists will not be able to send their content over the C-Kit network. 
**There is no news as important as to save any live!!!** If you have a problem with this statement, stay away from this project and don't waste our time with discussions.
This is not negotiable. Period!

## Watch-Dog
The "Watch Dog" shall be a daemon, that takes care of all configured applications to be operational.
The "Watch Dog" will shutdown applications in a configured sequence, if there is a need to save as much power as possible.

## Applications
There will be a set of applications to be run on a C-Kit. 
There will be basic applications and there will be additional applications.
The basic applications will provide the minimal services of the C-Kit. They are controled by the Watch-Dog and restarted if necessary.
The additional applications, will provide additional functionality. This may vary depending on the purposes of the rescue workers or the kind of disaster e.g. flood, bushfire, blizzard, etc.

If a person has a mobile connected to any C-Kit, it will display a set of basic applications

### "I'm alive" application
This application provides a service where you can type in your name, your birthday and if you are okay or in the need of help or medical care into a basic webfront end and press "Send".
You may type in as many information as people are around you, as there might be more people as working mobiles around.
The MAC-Address and the IMSEI number will be stored and tracked.  Logging information will be limited, but also transmitted.
So it will be trackable if there are changes in the status of the people.

### "life or death" application
If the user uses this application, the application will ask for information about the current situation. 
"Is a person life in danger?" - if the answer is yes, the application will ask just a the absolutely necessary questions and then sends the request with highest priority to the C-Kit command post.
If possible, it provides the GPS information of the mobile. If this is not successful with in three seconds, it wil provide the GPS postion of the C-Kit the person is connected to.
This is NOT optimal, but much better than "some where in the disaster area" and it is FAST.
