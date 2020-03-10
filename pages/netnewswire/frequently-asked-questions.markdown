@template nnw_page.html
@title Frequently Asked Questions
@description Answers to frequently asked questions about NetNewsWire.

*Last update: 8 March 2020*

## The iOS app has Feedly syncing, but the Mac app doesn’t. Will you be bringing Feedly syncing to the Mac app?

Yes. We will be adding Feedly syncing to the Mac app in NetNewsWire 5.1.

Both apps will have the same features (except for features, like Siri Shortcuts or AppleScript, that are platform-specific).

However, sometimes, one app may be ahead of the other for a little while — because we’re not going to hold off on shipping one app while the other catches up.

## Are you planning on FeedWrangler support? Or support for <strong>__</strong>?

Yes — we’d like to support all, or as many as possible, of the services like FeedWrangler, Inoreader, and so on.

If you’d like to volunteer to work on syncing for a specific service, please join the Slack group to make sure it’s not already in progress. We’ll also help you get started with it.

## Does it sync via iCloud?

No — or, at least, not yet. We think it would be a great feature, and we’re investigating the possibility.

## Why does the Today feed show the last 24 hours of articles?

Because it’s not that great when you’re reading your feeds at midnight and the Today feed empties out.

We realize that we’re stretching the meaning of “Today,” but we’ve decided that it’s okay. 🐣

## The first time I ran the app, there were some feeds already in there. Where do they come from? Why are they there?

We include some default feeds for new users — we think you’ll like at least some of them. You might even find a couple you didn’t know about, but that you like.

The reason we include those feeds is so you have something to read right away. It’s especially useful for new users, who may not know how RSS readers work — this way they can see, without having to do anything at all, how the app works.

You’re free to delete any or all of these feeds!

The number of these default feeds is always 16, which, to a programmer, is a round number since it’s a power of two. We’ve been doing 16 feeds since NetNewsWire Lite 1.0 back in 2002. It’s a tradition. 🐥

(We change the feeds from time to time. We don’t have any arrangements with the feed owners, though we usually ask permission — unless it’s something like Daring Fireball or Six Colors where it would obviously be no problem.)

## Why doesn’t NetNewsWire for Mac run on macOS 10.13 (or earlier)?

Supporting older versions of macOS takes a lot of work! We decided to prioritize features — such as supporting more syncing systems (Feedly, etc.) — instead.

Also, we specifically chose 10.14.4 and up because that’s the first release where we wouldn’t have to include the Swift libraries with the app. This meant a dramatic reduction in size.

## Can I get older versions of NetNewsWire for Mac that might run on my older Mac?

Yes! See [Old Versions of NetNewsWire](old-versions).

## Where should I report bugs and make feature requests?

The best place is <a href="https://github.com/ranchero-software/NetNewsWire/issues">GitHub issues for NetNewsWire</a>. You can also post them on the Slack group or email Brent.

## Is NetNewsWire 5 a drop-in replacement for NetNewsWire 3? Or NetNewsWire 4?

It’s not — it’s a separate app with a separate ID. You can run old versions alongside the new app.

To move to NetNewsWire 5, export OPML from your old app and import it into NetNewsWire 5.

## Do you plan to localize it in German? French? Etc.?

We’d like to, yes. It takes time, and it’s no small effort, but it’s important.

## What happened to Evergreen?

For most of its development life, the app was called Evergreen. When Brent <a href="https://inessential.com/2018/08/31/netnewswire_comes_home">acquired the name NetNewsWire back from Black Pixel</a>, Evergreen was renamed to NetNewsWire.

(NetNewsWire 5 does not use any code from previous versions of NetNewsWire. It’s a brand-new app.)
