---
layout: page
title: What's New
include_in_header: true
---

# Version 1

## **Version 1.2.1**

This update fixes an issue where the new Safari extension would not show up in the Safari's settings on iOS, iPadOS and macOS.

## **Version 1.2.0**

LinkBin is back! After a short break, this app will receive updates on a regular basis again. With this version, some exciting new features and stability improvements were implemented.

- There is a new Safari extension on iOS and macOS. Save the currently opened web page as a link in LinkBin with just a few clicks. You can optionally attach a label as well. iOS 15 is required for this.
- On iOS, LinkBin now has an "Add to LinkBin" action extension which can be found in the share sheet. This allows you to add a label before saving, compared to the already existing Share extension.
- Do you like LinkBin? You can now post a rating on the App Store via the settings screens.
- The manuals are now placed on the start page on iOS and in the Help entry of the menu bar on macOS. Also, some of them have been rewritten and received some screenshots for additional clarity.
- There is a new default view: Favorites. Star a link via the context menu and it will land in this separate area.
- The link lists received quite a performance boost under the hood. Especially on macOS, scrolling should be faster, thanks to the improvements that were made.
- The context menu is now able to handle all selected links. Previously, only one link at a time could be processed through the context menu.
- On iOS, the share extension should operate a bit faster with this update.

I really hope that you like these changes! Please file any feedback and bug reports via the app's settings.

## **Version 1.1.3**

- Restructured some source code in order to allow me to implement new feature more easily.
- Deactived the context menu when multiple links are selected since the actions only support one link for now.
- The button to reset the formatting of links in the copy view is now working.
- You can now choose a label for a link from the context menu.
- The view for editing a link or copying links does not crash anymore on macOS.
- Fixed a bug where pasting a link from the pasteboard would result in a crash on macOS.
- Added a Shortcuts action to open a saved link in LinkBin's browser view.
- Added a Shortcuts action to create a label.

## **Version 1.1.2**

- Fixed a bug where saving a link through the Safari extension on macOS would result in a crash.
- Fixed a German translation in an info pop-up.
- Added the ability to save a link or a label by pressing the return key on the keyboard.
- The in-app browser is macOS is now scalable.
- Added the possibility to edit a link's URL after it has been saved.

## **Version 1.1.1**

- You now have the ability to open a link in the device's default browser via the context menu.
- Shortcuts actions and widgets can now be configured to query archived links and all links. The latter was added so that you don't have to recreate a widget or an action when you want to deselect a chosen label.
- The list with all labels that appears when you configure a Shortcuts action or a widget now comes with icons for a better visual appearance.
- LinkBin now supports Siri Suggestions.

## **Version 1.1.0**
Okay, this is a big one. Thank you for your patience until this update, I really appreciate it.

- LinkBin now supports Apple's Quick Note feature. Open a link with the built-in browser and you'll be able to deeplink to that website and add notes. Requires iOS 15, iPadOS 15 or macOS 12 Monterey or later.
- Handoff support is here. Visit a link with the built-in browser and continue on another device where you left off.
- The macOS version also has an in-app browser now. This can be optionally deactivated from the app's settings.
- New Shortcuts action: Copy the newest link into the system clipboard.
- This update also comes with quite a few widgets. Place them on your homescreen and interact with your links even quicker.
- Need to copy a link in HTML or a similar format, for example for WordPress? No problem, you can now do this in LinkBin with just a few clicks.
- A confirmation dialog does not appear anymore when you swipe to delete a link or a label.
- All Shortcuts actions from iOS and iPadOS are now available on your Mac as well. Requires macOS 12 Monterey or later.
- You now have the ability to edit a link's title. This is especially useful when they all have the same generated title, like Google Drive links.
- Ever wanted to explore more of LinkBin's features? I got you! There is now a section in settings with some help articles which should give you a better idea about the features the app has to offer.
- Added a new alternate app icon. Requires a LinkBin Club purchase.

As always, please leave bug reports and feature requests!

## **Version 1.0.4**
- Implemented a lot of under the hood improvements for iCloud sync. For example, the app don't crashes anymore when you agree to new terms and conditions.
- You can now display archived items in the main lists via a new toggle in settings. Archived links show up with an archivebox icon, so that they are visually separated from other entries.

## **Version 1.0.3**
- Newly created labels that are attached to a link afterwards did not get synced to iCloud in some cases. This is now fixed.
- The iCloud account status is now determined at every startup to avoid unwanted behaviour.
- Textfields are now immediately focused when they appear.
- On macOS, you were not able to create a new label when you wanted to assign it to a link. This is now possible.
- On iOS and iPadOS, there is now a new button that allows to save a link from the clipboard. This is similar to the CMD+V feature that was introduced in the last version.
- Editing and deleting labels on macOS was not possible due to a bug introduced in the last version. This is now elliminated.

## **Version 1.0.2**
This new version also comes with some bug fixes, as well as some improvements and two new features.

- The share extension on iOS now displays a little feedback that indicates if the shared link is saved successfully.
- You can now rename labels and change their color.
- On macOS, the button for the privacy policy pointed to a wrong URL. This is now fixed.
- Save links from the clipboard by pressing CMD + V on an iPad or a Mac. When you have a label open, it will get attached automatically.
- It is now possible to create a new label from the view where you can assign one to a link.
- Adjusted the appearance of the buttons for creating a label.

## **Version 1.0.1**
Thank you for using LinkBin and giving feedback. I really appreciate your support. This version contains bug fixes and some minor improvements and additions.

- LinkBin's share extension now supports text. This means that you can share a text from a text editing app and LinkBin parses all links in it.
- Added a share sheet on iOS and a share menu on macOS.
- If you select black or a dark color for a label's color, the font color automatically turns to white.
- Added a link to LinkBin's Twitter account in settings.
- Corrected a typo in the App Store description.
- Adjusted the size of the screenshots on the App Store page so that their content is more readable.

## **Version 1.0.0**
Initial version of LinkBin.
