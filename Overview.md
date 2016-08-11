# Laracon 2016

(Short talk given to coworkers after the fact)

Laracon 2016 was held in Louisville from the 27th to the 29th at the

It's hard to pin down a general recap for the event
  - 18 talks over 3 days
  - 16 different speakers
  - Topics ranging from performance tuning PHP to interface and application design
  - Not really one specific theme; Not even Laravel

There were a few sponsors there, including Nexmo which we already use in the MI PIM to send texts.

Sentry and bugsnag both look like they sort of do the same thing - error reporting.  Personally, Sentry looked more polished and simpler to plug in to multiple languages/projects.

## Topics

1. Testing
 - There were two talks given about various testing strategies
 - One talk was on TDD (Test Driven Development) and the other was on BDD (Behavior Driven Development)
 - The TDD talk was a little easier to follow, but BDD seems interesting with more expressive tests
2. API's
 - There was an interesting talk about Lumen, a lightweight version of Laravel
 - It doesn't have a few pieces - Facades are missing, as are views
 - These speed it up, but make it less versatile.  You can add them back in if you need them though.
3. Vue
 - Vue.JS is a javascript library similar to Backbone and others where you create templates and manipulate them bases on application state
 - It has grown in popularity in the Laravel community.  I don't see a need to switch to it from Angular for us.
4. Refactoring and code cleanliness
 - There were a number of talks about how to clean up code and write cleaner code to begin with
 - Tests help, but things can still get messy
 - Laravel collections provide a lot of powerful functionality to help reduce loops
 - Code Smells - they're bad but they're fixable.  Every smell has a fix. (Break up methods, decouple classes, etc)
5. Miscellaneous Technical talks
 - Really cool talk on HTTP/2
  - Server Push is a new technology that lets the server send resources before the client asks for them
  - It's available now for some servers, and packages exist for it already.
 - There was a good talk about the history of PHP
  - Co-creator of the language talked about how it came to be
  - Graphs of historical speed increases on benchmarks
  - PHP7 is 30% or more faster than PHP 5.6 on real world benchmarks. (I've seen this on my tests)
 - Interesting talk on server security
  - A lot of it kind of went over my head, but Chris Fidao has a lot of the information up on his website
  - All about whitelisting certain ports and protocols for your internal and external web traffic
  - Dropping packets instead of erroring on them to keep port information secure
6. Design talk
 - Ryan Singer from Basecamp gave a very interesting talk on design
 - Design hierarchy, (Domain Experience -> Situations -> Flows -> Affordances -> 2D Layout)
 - Start with Flows to determine Affordances.
 - Domain Experience lets you figure out what Situations are likely to come up, which can inform you of useful Flows.
