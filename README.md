What's this?
============

A Microsoft Universal Printer Driver (aka Unidrv) "minidriver" for the [Royal LetterMaster](http://blog.ajf.me/2015-04-08-daisy-wheel-diaries-part-1), a budget 1980s daisy wheel printer. It's supposed to run on Windows 2000 or later.

It doesn't work, unfortunately. Something about the .INF or .GPD file means it won't install. Which is a shame.

It's also pointless. After struggling with it and being unable to get it to work, I discovered that the Windows "Generic / Text Only" driver supports unprintable margins, bold and underline, so long as you tell it the correct commands. Which means this driver is a waste of time, since those were the only problems with Windows's own driver.

Oh well.

If you want to get this to work, you'll need to [start Windows in the mode where it doesn't check driver signatures](http://revryl.com/2013/02/19/force-driver-windows-8/), because it's unsigned. Even surmounting that hurdle, though, the driver seems uninstallable: something's wrong with it, but I'm not sure exactly what.
