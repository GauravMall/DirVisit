# DirVisit
This library was created as a result of a StackOverflow Query about how to open a directory. The question can be found here: [Android open an external directory using an intent](https://stackoverflow.com/questions/57670811/android-open-an-external-directory-using-an-intent/57670970)

It is meant to be the tool which allows you to do a variety of tasks associated with navigating the local and external storage of any Android device. Specifically you can:
- Open any directory on the device using the directory's file path.
- Open any of the pre-designated directories like `Folders.Download`
- Open any file with it's file path using the default installed app*

*Beware that any attempt at opening any file that isn't supported by the mobile device is obviously going to fail.

**NOTE**: This app is intended to follow every official Android guideline. It is not a hack nor a cracked version of some software, rather a library developed to support something that Android Development at the moment does not, but easily *can*.

# Development
Development is on-going. I would say I'm at an intermediate stage (there are a lot of issues, Android specifically wants us to not access directories). That said it is coming together with many devices supported as of right now. Maybe in the summer there will be a beta version, although it's more probable that in December a very early release will happen.

# What you can do?
Once this library is out, it is obvious that we need to do **testing**. Testing, testing, testing! A rigorous testing procedure on a variety of android devices will allow us to detect bugs, version-specific issues and obviously if there is a device that doesn't support this library.

Yes, I will be running tests on my own. Trying DirVisit on my smartphone, and using official test labs. But you WILL help us out, if you test them out on any of your devices. Maybe there's a phone that you have and it is a little...eccentric. You could develop an app with this library, deploy it and report back whether it works or not.

# Donating
As of now, not even a beta version has been ruled out, so donating is out of the game. This is intented to be free and open-source once live. But I'll put a donate button right here when I think that I've made a product that I'm proud of. And you will be helping me out a bunch if you decide to donate. So stay tuned!
