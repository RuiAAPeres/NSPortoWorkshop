# NSPortoWorkshop

## Intro

The workshop would be on a weekend and would be around 16hours. It would be around Architecture and coding best practices in **objctive-c**. The following frameworks are being considered to be used as part of the workshop (assume the use of `UIKit` and `Foundation` by default), ordered by importance:

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
* Cocoapods: this will be a small addendum but that makes our life utterly simpler.

These topics, described above, are where I would focus primarily my attention. I would like as well to show some bits and pieces from `Core Animation` + Animation in iOS:

* What can you actually do with it.
* What's the difference between an implicit and an explicit animation and when to use one over the other.
* Delving into the `UIView`'s backing layer for simple and yet useful things like: `cornerRadius`, `borderColor` and others.
* What can you do with Pop from Facebook.
* Using UIKit Dynamics for fun and profit.


## Who's this for?

This workshop is aimed for novice to intermediate developers that are interested in knowing better ways of creating iOS applications. By the end of the workshop you should:

* Have confidence and knowledge to create an application from scratch.
* Comprehend different patterns that exist in iOS and know where and when to apply them.
* Produce code that is reusable, modular and maintainable.
* Make tests a first class citizen on a project.
* Understand the importance of contributing to open source as way of improving oneself. 

## Requirements

The following should be met in order to make full use of the workshop:

* [OOP](http://en.wikipedia.org/wiki/Object-oriented_programming) knowledge. It would be very difficult to follow if you don't have it, at least, on a basic level.
* Some basic Git knowledge is advised but not essencial. 
* A Github account, so you can keep track of what you are doing during the workshop.
* A Macintosh with Xcode 6.0. 
* [Ruby](http://blog.zerosharp.com/installing-ruby-with-homebrew-and-rbenv-on-mac-os-x-mountain-lion/) installed and [Cocoapods](http://guides.cocoapods.org/using/getting-started.html). We will make use of some 3rd party libraries and it's important for you to get familiar with Cocoapods.

## Feedback

Any suggestion, please, create an [issue](https://github.com/RuiAAPeres/NSPortoWorkshop/issues/new). On the other hand if I misspelled something, or any bad formmating, please, send a Pull Request. If you prefer, you can reach me via [email](mailto:rui.a.peres@gmail.com).

## F.A.Q


