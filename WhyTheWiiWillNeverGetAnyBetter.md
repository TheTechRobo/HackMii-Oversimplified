 If you look at lists of software updates for the PS3 or the XBox 360, you’ll find things such as PS3 update 2.40, which made XMB available in-game, or XBox 360 update 2.0.7357.0, which added the New XBox Experience, among many smaller updates are stability fixes, new peripheral support, and new features like in-game screenshots. A large amount of the features affect or improve the in-game experience.

Meanwhile, the Wii got all of:

1. Things, such as copying saves to SD, which should have been there from the start
1. Support for new features for new games, with zero improvements for any games already released (USB keyboards, WiiSpeak, etc).
1. Updates to built-in channels (Wii Shop Channel, etc)
1. Wii menu or messageboard tweaks, like moving channels or, get this, a clock.
1. Security updates, or their failed attempts at stopping homebrew.

This isn’t a coincidence. As it turns out, Nintendo chose not to have any operating system or common code at all running on the main processor. When you run a game, everything that shows up on your screen, ever, is being loaded from that spinning polycarbonate disc. And there are no mechanisms for anything else to run on that processor: no update system, no Home Menu updates, nothing.

Now, the Wii *does* have software known as "IOS" that runs as the back-end on a separate processor. So, why can't they improve things from there? Well, Ninty has decided to add new features as **a new IOS**. Your Wii has oh so many IOS versions on its NAND (similar to a hard drive). Nintendo has only updated these old IOS versions with security fixes, e.g. fixing homebrew (without actually fiximg it). As of 2009, there are **23 versions of IOS** residing on your Wii. 23! This is wasting the already limited storage space on the Wii. Every time they've added new features (a very small number), old games can't use them. You know how in new games the disc slot light blinks when you take out the disc while it's in use? Games like Zelda don't have this - they're using the old IOS9 which has only the features that existed in 2006. Plus - IOS can't write *anything* to the screen, only the game can, which makes almost all decent feature requests impossible. Even worse – some things that should have been implemented in IOS aren’t. 

As a specific example, let’s look at the much-discussed future ability to load channels from an SD card (seriously, what the heck were they thinking with 512MB of internal storage and no sane infrastructure to ever expand it externally?) There are three possible solutions to get this to work:

1. Add new code to old versions of IOS, disabling any SD card access for titles that launch from SD
1. Add new code to old versions of IOS and send out updates to games that use SD cards, to replace the in-game code with a call to IOS code
1. Just fake it and transparently copy titles to the Wii system memory when you want to launch them, causing more wear and tear, longer launching times, and ruining the point of copying to the SD card (to free up space)

Chances are they’re going to go for number 3, because the other two are a lot of work. Even though this could have been avoided had they created a smarter system.

While other consoles get firmware updates, new peripheral support, bugfixes, and even major updates like the XBox New Experience, pretty much everything on the Wii will remain just as it is now. The best Nintendo can do is update the Wii Menu, but once you get into a game, there’s nothing it can do. Forget about an improved Home Menu. Forget about any changes to online gaming beyond minor server-side tweaks. A unified friends system to avoid having to enter friend codes for every game? Not going to happen. Bad game bugs? Tough luck, there’s no patching system (remember the Zelda issue?) Some future proper online support with social features, like the other consoles have? Will never work with older games. Worse, Nintendo are really proud of themselves, so they won’t admit that they screwed up their software by releasing such big new features and having them only work for newer games.

All in all, the Wii’s software stack is designed with little to no future proofing. There are basically zero provisions for any future updates; even obvious things like new storage devices or game patches. What’s worse is that this will affect the compatibility mode of any future Wii successor. Just like DS titles won’t get WPA (the successor to WEP WiFi password technology; now superseded by WPA-2 and WPA-3) support on the DSi, effectively making the DSi’s WPA mode useless if you ever want to use DS titles on-line. The DS WiFi drivers and configuration stack are built in to every game.

Remember, when Nintendo fails to deliver new Wii features, it won’t be because they aren’t trying. It’ll be because they’ve killed their chances from the start.
