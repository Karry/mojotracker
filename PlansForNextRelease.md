# Introduction #

MojoTracker isn't perfect. We have many ideas how make it better. This page summarises basic ideas.

If you mean that something is missing on this page, let us know. You can comment this page, or create new Issue on [MojoTracker issue tracker](http://code.google.com/p/mojotracker/issues/list).


## More configuration items ##

We want add some configuration choices:

  * Refresh frequency
  * Start saving track at startup
  * Accuracy value for warning (show this value red)
  * **Maximum accuracy for export**
  * ...

## ~~Add waypoints~~ ##

Add button for add waypoint to current track. It would be possible specify name and comment (and photo or sound record?).

## ~~Make MojoTracker localizable~~ ##

Many texts are directly in source code. It would be nice move it to special locale file (json?) and make MojoTracker localizable.

## Write own file service ##

Mojo applications can't access files on internal storage directly. It must use installed service for this (mostly written in Java). MojoTracker use [FileMgr Service](http://www.precentral.net/homebrew-apps/filemgr-service) by Jason Robitaille.

This service is little bit buggy. Main developer of this service don't want release it as open source, so we can't fix it!

We really need **open source** file service...

## ~~Show saved track detail (done)~~ ##

Now, we show only track name, length and nodes count. It will be nice add page with track detail. See this outline:

<a href='http://mojotracker.googlecode.com/svn/wiki/images/ideas/trackdetail.jpg'><img src='http://mojotracker.googlecode.com/svn/wiki/images/ideas/trackdetail.jpg' alt='Track detail outline' width='200' /></a>