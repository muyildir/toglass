# Introduction #

ToGlass is a utility app for sending a note from your android phone to Google glass.

The main idea is to stick up anything for quick reference, e.g. a shopping list, a confirmation number, a url, a phone number, some reminder, motivational stuff or a joke or anything.

You can share any text data from any application on your android device to the ToGlass app and then send it to your Glass.

The note gets displayed as a Live card and stays there until you explicitly dismiss it.

# How To Get It #

Till the time Google figures out a way of screening and distribution of apps for Glass. You can find the APK here (https://drive.google.com/file/d/0B8PI6flfarz4UVpta0pybks3bGs/edit?usp=sharing)

**UPDATE** : Updated for XE12, if you upgrade to XE12, earlier file may not work.


# How to use it #


  * Sideload the APK on your glass device as well as on your phone.

> adb -s <device id> install ToGlass.apk

  * See the video here (http://www.youtube.com/watch?v=mTO_JjVLVqY)

  * Run the app on the phone, you should see a text entry field. Type/paste anything.

  * Now, activate glass and say : Ok, glass -> Receive from phone
> > The screen should show "Listening..."

  * On the phone, hit the check box acknowledging that you have activated the Glass app. A send button will show in the menu (ActionBar). Hit the button and you should see the note on Glass.

  * Submit any issues/feature requests at : https://code.google.com/p/toglass/issues/list

  * Best way to connect with me is circle me on G+ (http://plus.advantej.com) and/or follow me on Twitter (http://twitter.com/advantej)

# Disclaimer #

The app is a quick hack put together, so use it at your own risk :)
If you are paranoid about permissions, all I use is the BLUETOOTH and BLUETOOTH\_ADMIN permissions.