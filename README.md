# NSPortoWorkshop

## Intro

The workshop would be on a weekend and would be around 16hours. It would be around Architecture and coding best practices in **Objctive-c**. The following frameworks are being considered to be used as part of the workshop (assume the use of `UIKit` and `Foundation` by default), ordered by importance:

* `Core Animation`
* `Core Location`
* `Core Data`
* `Core Graphics`

## Focus on the code

Most of our day-to-day work are mundane things: 

* Create a new class to access a service.
* Create a new `UIViewController` that displayed a given piece of information.
* Add something new to a given `UIView`.
* Fix a nasty bug on the modal layer.

These are the kind of stuff where you would mostly spend your time on. Polishing the app, creating fancy animations, custom controls are a small (**but important part**) of your work. I feel that another 16h (or potentially more) would be necessary to cover those (remember: *The devil is in the detail*). I will try to focus on the following:

* Idiomatic Objective-c code: writing code that experienced developers see and understand.
* Common patterns where/how to use them: Delegation, KVO, Notification Center, Blocks.
* Testing: because who has time for it, right?
* Architecture: both [MVC](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) and [MVVM](). I will try to cover them, where it makes sense, so you can have a taste of both.
* Cocoapods: this will be a small addendum that makes our life utterly simpler.

These topics, described above, are where I would focus primarily my attention. I would like as well to show some bits and pieces from `Core Animation` + Animation in iOS:

* What can you actually do with it.
* What's the difference between an implicit and an explicit animation and when to use one over the other.
* Delving into the `UIView`'s backing layer for simple and yet useful things like: `cornerRadius`, `borderColor` and others.
* What can you do with Pop from Facebook.
* Using UIKit Dynamics for fun and profit.


## Who's this for?

This workshop is aimed for novice to intermediate developers who are interested in creating iOS apps and improving the way they do so. By the end of the workshop you should:

* Have confidence and knowledge to create an application from scratch.
* Comprehend different patterns that exist in iOS and know where and when to apply them.
* Produce code that is reusable, modular and maintainable.
* Make tests a first class citizen on a project.
* Understand the importance of contributing to open source as way of improving oneself. 

## Requirements

The following should be met in order to make full use of the workshop:

* [OOP](http://en.wikipedia.org/wiki/Object-oriented_programming) knowledge. It would be very difficult to follow if you don't have it, at least, on a basic level.
* Git knowledge is advised but not essencial. 
* A Github account, so you can keep track of what you are doing during the workshop.
* A Macintosh with Xcode 6.0. 
* [Ruby](http://blog.zerosharp.com/installing-ruby-with-homebrew-and-rbenv-on-mac-os-x-mountain-lion/) and [Cocoapods](http://guides.cocoapods.org/using/getting-started.html) installed. We will make use of 3rd party libraries and it's important for you to get familiar with Cocoapods.

## F.A.Q

1. **I don't know anything about programming, but I am interested, should I go?**
I would advise against it. I will do a swift (no pun intended) revision on Objective-c, but how to actually code, no. You should be familiar with concepts like: `if`, `for`, `string`, `int`, `class`, `method`.

2. **Will this be a paid workshop? If so, how much?**
As it stands yes, as for the amount it depends on the number of people that are interested and if I am able to find a place with the necessary infrastructure: space, internet, projector, etc. But I am setting a maximum of 200€ per person and minimum of 100€, depending on conditions described previously. 

3. **Is there a limit to the amount of people who can attend?**
I want to keep this at 15 people max. More people would jeopardise me being able to assist anyone with an issue and still being able to respect the schedule.

4. **I am student and I can't afford it, is there any kind of discount?**
I will make a discount to students if there are spots left.

5. **When will it be?**
I want to make in December, but this can be postpone to maximize the number of interested people.

6. **Is there a possibility to make it with Swift?**
Right now there isn't idiomatic code in Swift and the compiler, language and Xcode are not stable enough to risk making a workshop wiht it. So bottom line: right now, no, but in a near future possibly. Above all, I would like to show patterns that belong to Swift (functional paradigms) and not direct ports from Objective-c.

## Feedback

Any suggestion, please, create an [issue](https://github.com/RuiAAPeres/NSPortoWorkshop/issues/new).I will also accept Pull Requests. If you prefer, you can reach me via [email](mailto:rui.a.peres@gmail.com).
