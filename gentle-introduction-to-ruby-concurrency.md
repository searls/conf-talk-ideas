# A Gentle Introduction to Ruby Concurrency

Conferences: RubyConf 2015

## Title

A Gentle Introduction to Ruby Concurrency

## Abstract

Breaking this inline:

> Concurrency is one of today's hottest topics. You can't throw a virtual stick these days without hitting a book, blog post, or conference talk about concurrency.

Not everyone feels that way (I literally only think about concurrency a few times a year, heh), so I'm not sure I'd spend 161 precious characters playing up the assumption it's a hot topic for everybody.

> Although there's a ton of information out there, it's often deeply technical, highly academic, or both.

Now _this_ I can get behind, because it's exactly the reason I don't care about concurrency. I'd lead with a pithy swipe at this and that **this is why** people only pay fleeting attention to lip service and instead of understanding it they flock to other languages b/c hackernews said it was concurrent. And that you're going to teach us better!

> Most programmers don't care about the inner workings of the various interpreters or the advantages of one locking model over another. 

Agree we don't care, but at 133 characters, this statement is a long way to reinforce what I don't care about.

> Most Rubyists just want to know one thing: How will this make my programs better? 

Another way to look at it is that as a Rubyist i want to write ruby at work, so I want somebody to help me prove at work that Ruby's good enough at concurrency for me to keep using versus popular alternatives

> This introductory presentation will show that with only two simple patterns and abstractions virtually any Ruby program can be enhanced with safe, reliable, and easy to use asynchronous behavior.

+1. If you plan on using concurrent_ruby in this talk, I urge you to mention it by name and call yourself out as the author
