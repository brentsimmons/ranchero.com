@title Maurice on Zavala 4
@pubDate 2026-02-16 21:31:46 -0800
@link https://vincode.io/2026/02/16/building-zavala.html

If you use NetNewsWire you know Maurice Parker’s work — so much of NetNewsWire, from Feedbin and iCloud syncing to the iOS app itself, was written by him. He’s up to version 4.0 of his cool outliner app Zavala and he writes on his blog about [the decisions and tradeoffs](https://vincode.io/2026/02/16/building-zavala.html) that went into it. (I love this kind of thing. Every developer should write like this after shipping a major release. Me too.)

One of the questions Apple-ecosystem developers all have to wrestle this these days is how to handle Liquid Glass. Maurice:

> Unfortunately, it is very difficult to have a Liquid Glass version of your interface along side the legacy look and feel of previous OS versions. This is because you have to update to the latest API’s to correctly use Liquid Glass and some things, like the spacing of elements have been changed. Basically to keep backwards compatibility for OS’s before the version 26 ones, you need to maintain two different versions of the user interface code.
> 
> So I made the difficult decision drop support for previous versions of iOS, iPadOS, and macOS.

I know what that decision is like, and I know Maurice is understating it a *lot* when he calls it difficult.
