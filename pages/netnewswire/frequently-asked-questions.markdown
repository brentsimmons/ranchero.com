@template nnw_page.html
@title Frequently Asked Questions

*Last update: 2 Jan. 2020*

### Are you planning an iOS version?

Yes — we’re already working on it.

### How can I get on the TestFlight beta for the iOS version?

[This page has instructions for signing up.](https://ranchero.com/netnewswire/test-ios)

### Are you planning on Feedly support? Or support for ______?

Yes — we’d like to support all, or as many as possible, of the services like Feedly, Inoreader, and so on.

If you’d like to volunteer to work on syncing for a specific service, please join the Slack group to make sure it’s not already in progress. We’ll also help you get started with it.

### Why does the Today feed show the last 24 hours of articles?

Because it’s not that great when you’re reading your feeds at midnight and the Today feed empties out.

We realize that we’re stretching the meaning of “Today,” but we’ve decided that it’s okay. 🐣

### Why doesn’t it run on macOS 10.13 (or earlier)?

Supporting older versions of macOS takes a lot of work! We decided to prioritize features — such as supporting more syncing systems (Feedly, etc.) — instead.

Also, we specifically chose 10.14.4 and up because that’s the first release where we wouldn’t have to include the Swift libraries with the app. This meant a dramatic reduction in size.

### Where should I report bugs and make feature requests?

The best place is [GitHub issues for NetNewsWire](https://github.com/ranchero-software/NetNewsWire/issues). You can also post them on the Slack group or email Brent.

### What happened to Evergreen?

For most of its development life, the app was called Evergreen. When Brent [acquired the name NetNewsWire back from Black Pixel](https://inessential.com/2018/08/31/netnewswire_comes_home), Evergreen was renamed to NetNewsWire.

(NetNewsWire 5 does not use any code from previous versions of NetNewsWire. It’s a brand-new app.)

### Is NetNewsWire 5 a drop-in replacement for NetNewsWire 3? Or NetNewsWire 4?

It’s not — it’s a separate app with a separate ID. You can run old versions alongside the new app.

To move to NetNewsWire 5, export OPML from your old app and import it into NetNewsWire 5.

### Do you plan to localize it in German? French? Etc.?

We’d like to, yes. It takes time, and it’s no small effort, but it’s important.
