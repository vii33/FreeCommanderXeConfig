# FreeCommander XE Configuration

## Motivation

For me, the features of the standard Windows Explorer are not sufficient. So I evaluated some alternative file explorers and stuck with [FreeCommander XE](https://freecommander.com/en/summary/). It's a great freeware and I can really recommend checking it out (see *Features* below).

>*But:* The interface and the sheer number of features can be overwhelming for new users. Without extensive customization in the settings, it is quite bulky to use.

>So I created an optimized starter pack configuration, which in my opinion addresses these challenges. The number of UI elements is reduced, further settings are streamlined.
This hopefully helps people to get a head start with a more powerful file explorer.

Vanilla Windows Explorer | Vanilla FreeCommander | Custom FreeCommander Configuration
--- |--- |---
Lack of comfort features  | Cluttered UI and bulky default settings | Optimized settings for better user experience
![Vanilla Windows Explorer](readme_images/winex1.PNG) | ![Vanilla FreeCommander](readme_images/fc1.PNG) | ![Customized FreeCommander Configuration](readme_images/fc2.PNG)

<br/>

----------

## Installation Instructions
1. Install [FreeCommander XE](https://freecommander.com/en/summary/)
1. Clone this git repository.
(Beginners: Click on the green "Code" button and then on `Download ZIP`)
1. Open up FreeCommander. Go to `Tools / Restore all settings`. Select the cloned folder.
1. Confirm and wait for FreeCommander to restart.
1. Done!

> *Remark:* You have to update the links in the favorites section or create new ones yourself (right-click in the favorites section) 

> *Remark:* When you change something, hit the `Tools / Save Settings` button. This is not done automatically to reduce the closing time of the software. You can re-enable this in the settings if you want to.

> *Remark:* You can change the UI language under `Tools / Settings / General.`

<br/>

----------

## Customized Features

Feature | Description | Shortcut | Screenshot
--- | --- | --- | ---
**Tabs**  | Use tabs instead of having to open multiple windows (similar to your browser). I edited the tab size and coloring.  | <ul><li> `New:` Double click on empty space right of a tab</li><li>`Restore:` Right-click on existing tab</li></ul> | ![](readme_images/fc2.PNG) 
**Split View**  | Two parallel views for comparison use cases. Powerful feature, now easily accessible | Press `Spacebar` to activate/deactivate | ![](readme_images/fc5.PNG) 
**Property-based file name colorizing**  | You can use any file property like date, size, type. My configuration colors the *read-only* files & folders in orange and *newly* created files in dark blue. This helps a lot in my daily work.  | (done automatically. Changeable under `Settings/View/File-Folder-List`) | ![](readme_images/fc4.PNG) 
**Custom Action Toolbar**  | Fully customizable. I rearranged everything to better show the relevant elements.  | Changeable with right-click on `Action Toolbar`. | ![](readme_images/fc6.PNG) 
**Custom File Views**  | You can set what file information is displayed in the list and how. I edited a lot of smaller stuff here. Also, I set up an *automatic change* from a list view to a thumbnail view, when more than half of the files in a folder are images.  | If you want to modify this, go to `Setting/View/Column Profiles`. | ![](readme_images/fc8.PNG) 
**Quick filters**  | Easily pin down the one file you are looking for. Works in an instant. Capable of search expressions like logical AND/ORs. (I enlarged the filter field to be more recognizable)  | See the documentation on the [FreeCommander Website](https://freecommander.com/fchelpxe/en/Quickfilter.html). | ![](readme_images/fc3.PNG) 
**Copy file paths to clipboard**  | You can select multiple files and get all their paths copied into the clipboard.  | Just hit the marked button from the action bar. | ![](readme_images/fc7a.PNG) ![](readme_images/fc7b.PNG) 
**Fast parent folder navigation**  | Small gem at the end: You can double click on a free area in the file list to move up to the parent folder. You will miss this feature in Windows Explorer after 5 minutes of usage. Promised.  | `Double click on a folder:` Move hierarchy down. `Double click on a free area:` Move hierarchy up. | ![](https://i.pinimg.com/originals/df/98/da/df98da8cb74b9148c795d855bba96c79.png) 

----------

## Further (untouched) features

There are many more things, FreeCommander is capable of doing.

* You can start command prompts from your current folder. I disabled the input field for this, as I do the right click method directly on a folder.
* You can work with multiple quick access views / favorite views. Handy if you want to seperate work or dev folders from general folders.
* You can have other color themes, like a dark mode. Switch to it with a shortcut, for example.
* FreeCommander is capable of doing a diff on two folders.
* FreeCommander has a built-in multi rename capability (not yet tested).
* FreeCommander actually has a usable search, where you can fine-tune your search parameters, e.g. search only files or folders, maximum file size and so on.


----------

## Conclusion

FreeCommander might be a bit overwhelming at first because there are a lot of possible tweaks. In my opinion, it is worth the effort, though. This due to two reasons: 

First, you probably locate files each day on your computer, therefore it should be customized to your needs. 
Second, this is a rare effort, as you can save & backup your customizations.

*Happy exploring!*