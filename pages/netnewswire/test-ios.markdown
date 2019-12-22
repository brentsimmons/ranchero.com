@template nnw_ios.html
@title NetNewsWire 5 for iOS Public TestFlight

If you’d like to help test NetNewsWire 5 for iOS, please [sign up on TestFlight](https://testflight.apple.com/join/5Mh4hVpS). (Requires iOS 13. Hopefully you’re on 13.3.)

While the app is close to being finished, there are still some tweaks to make — and there are bugs, surely. Which is the point of all this. 😀

## Feedback

TestFlight includes ways to send bug reports and crash logs — please use those.

You’re also encouraged to [join the Slack group](https://ranchero.com/netnewswire/slack). Once you’re in, join the #nnw-ios-feedback channel. This is a great place for questions, observations, and feedback — and you can get to know other members of the NetNewsWire community.

You can also file bugs and feature requests on our [bug tracker at GitHub](https://github.com/brentsimmons/NetNewsWire/issues). (This is actually quite helpful!)

## What’s in the App

The app is for iPhones and iPads. It’s free and open source, just like the [Mac app](https://ranchero.com/netnewswire/).

The features are similar to the Mac app…

* Direct feed-downloading
* Syncing via Feedbin
* Share sheet
* Dark Mode
* Starred articles
* All Unread and Today smart feeds
* Folders
* Importing and exporting OPML feed lists
* Multiple accounts
* Background refreshing
* Searching

…and it has a few features that haven’t made it to the Mac app yet…

* Feedly syncing
* Reader view
* Hiding read articles
* Timeline customization

It also supports Shortcuts! (We love automation. The Mac app is AppleScript-able.)

## Coolest Thing

If you’re using an iPad with a keyboard, you have the same keyboard shortcuts available as in the Mac app. You can fly through your feeds without touching the screen. It’s awesome!

## Help Book

[The manual is online already!](https://ranchero.com/netnewswire/help/ios/5.0/en/) If you have questions about how to do things, that’s the first place to look.

You can get to the manual via the Settings screen in the app.

## About the Design

Just as the Mac app is designed to be very much a *Mac* app, sticking closely to platform guidelines and conventions, the iOS app is very much an *iOS* app.

It supports Dark Mode, Context Menus, Dynamic Type, and accessibility. (Bug reports related to accessibility are high priority: if you notice something we can improve, please let us know asap.)

We’ve worked to make it clear, clean, and as obvious as possible. If it looks like we just kind of skipped the design process — if it looks easy, as if it didn’t take much thought — then *good*. That’s the goal.

## Screenshots

This is a detail from a larger screenshot. See the [Screenshots page](screenshots-ios) for full size screenshots.

<a href="screenshots-ios"><img class="centeredImage" src="https://ranchero.com/netnewswire/images/nnw-ipad-dark-thumb.png" width="357" height="357" style="border:1px solid black" alt="Screenshot showing NetNewsWire 5 timeline display settings on an iPhone." alt="Go to the screenshots page."></a>


## Credits

NetNewsWire is a team.

[Maurice Parker](https://vincode.io/) wrote the entire user interface of the iOS app. Some parts of it [he did twice](https://inessential.com/2019/10/21/swiftui_is_still_the_future), even. That’s a *ton* of work. He also did background refreshing, which turned out to be a surprising amount of work too.

[Brent Simmons](https://inessential.com/) designed the iOS app, along with Maurice. Brent wrote much of the under-the-hood parts, and he manages the project.

[Kiel Gillard](https://twitter.com/kielgillard) wrote Feedly syncing, which we prioritized because it’s been the most common of the syncing feature requests. This was tricky because parts of the in-app API were a moving target as he worked on this.

[Nate Weaver](https://github.com/wevah) has been our utility infielder, working here and there to fix different things. When something works a little better, there’s a good chance it’s Nate’s work.

[Ryan Dotson](https://twitter.com/nostodnayr) wrote the [iOS Help Book](https://ranchero.com/netnewswire/help/ios/5.0/en/). (He also wrote the [Mac Help Book](https://ranchero.com/netnewswire/help/mac/5.0/en/).) This is one of those things it’s easy to skimp on, or just not do, but we consider documentation massively important: it’s a matter of respecting the people who use the app.

The generous folks at [Feedbin](https://feedbin.com/) are hosting the web service we use for NetNewsWire’s new Reader view, and they’ve gone out of their way to help in many different ways, over and over.

The testers on our Slack group can’t be thanked enough for all their help testing all the early builds — and especially for their patience with all the crashes as we were getting background refreshing working.

And, finally — [Brad Ellis](https://twitter.com/bradellis) made a beautiful and modern icon for the iOS app. (Brad also made the Mac app icon.) Without a beautiful icon, we’re nothing.

<img class=centeredImage src="https://ranchero.com/netnewswire/images/NNW-iOS-Icon.png" height=564 width=560 alt="NetNewsWire for iOS icon: Earth with a satellite orbiting above it, in the foreground.">

## Press Inquiries

If you have questions for a blog post, article, or podcast, please email Brent Simmons at <a href="mailto:brent@ranchero.com">brent@ranchero.com</a>.
