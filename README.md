# SSH Notifier

**SSH Notifier** is a ***nix** script made with PHP to notify the user whenever an SSH connection is started and / or finished.

You can customize the script by setting the interval on when it will start rescanning your system. by **default**, it is set to **1**.  

**I recommend that you set it to a longer interval (such as 5 seconds) if you have a slower machine.**

## Dependencies

### ALL

You need:

 * **GIT**: Well, not really... if you download this from the site.
 * **PHP**: This is a must though... sorry
 * **SSH**: What's the point of using this if you don't have that right?

###Ubuntu
`notify-send` is already built-in with Ubuntu.

###Other Linux Distributions
I'm not sure about **Notification Commands** of other distributions. Please feel free to edit this to your liking and inform me as well so I can make adjustments and what not.

###OSX
You need  **Growl Notify** You can download this here: http://growl.info/downloads


##Running SSH Notifier
So far, it is still a small script wherein you can just run it from the terminal.

###1. Go to your home directory (or wherever you want this to be.)
 `$ cd ~`

###2. Get a copy of the project
`git clone https://github.com/aeolu/ssh-notifier.git`

###3. Make the script into an executable
`$ cd ssh-notifier`
`$ chmod +x main.sh`

###**NOTE:** you can test the script first by running `php main.sh` and establish SSH connection.. **Try it out!**

## Author Comments:

### If you would want, run it as a startup application

### Please feel free to port it and comment on which language is better to port this on
I'm just really, **REALLY** fond of PHP but if there's better options, I can port this to other languages.

### Remember that this APP is still in an Alpha version, so please be careful in using this

## Updates I would love to have:

### Multiple Notification
So far, with what I've done, it can only show one update at a time.. I mean:

If two people disconnect at the same time, it'll only notify for the first guy.. *Sorry for that*

### Array Verification
To make it quicker, I just made a difference counter checker... Kinda stupid now that I think about it cause I've used `array_diff_assoc` which could've made counter checking void...

**NOTE: Gonna update later, I'm sleepy...**

### Windows Support
I'm really not sure if Windows has a notification system or something, but if has, then adding it would be easy peazy! ;)


