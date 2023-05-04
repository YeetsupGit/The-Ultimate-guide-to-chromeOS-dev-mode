# Developer Mode and how to get to it
*markdown Edition*

#### created by [u/yeetsupwillneverdie](https://reddit.com/u/yeetsupwillneverdie "my new reddit account cuz i got banned")

>*please note that the official chromiumOS docs contain as much information as this repo. this is just a more, **simplified** version of those Docs.*

sooo, you're feeling a little techsy, and you feel like destroying that spare chromebook you've had sitting in a drawer since 2015... you've come to the right place. It's funny that some people actualy read these, and it's even funnier that most people don't know that I edit these in ChromeOS 72's Default Text editor. Anyways, to the point:

## What *is* ChromeOS developer mode?

ChromeOS developer mode is a much less locked-down version of ChromeOS. Normal, non-developer mode ChromeOS Has this thing called "system verification." System verification, Basically, makes sure you are running a safe, un-modified version of chromeOS. which means that you can't modify chromeOS, be running Ubuntu Linux, Or anything cool like that without turning on developer mode. I know, It's Annoying, but that's Just the way it is.

...And That's why I'll show you **how** to enter developer mode.

## But wait... Is Developer Mode Safe?

If you Don't know what you're doing, no
and if you *do* know what you're doing... no-ish.

There's a lot of reasons I don't recommend it, including, but not limited to: 

No System Verification!(I already said this, but it allows for chromeOS to be modified, in a malicious or non malicious way)

Full Root Access!(you already know why this is risky)

A Full Bash shell!(you could accidentally run a malicious script)

Your warranty void!(your warranty, void!)

## Okay, I know the risks of developer mode, and now I'm ready to use it.

So, Now that you know the risks of developer mode, I think you're ready to use it. I'm gonna do a step by step on how to enter it now, and yes, I know this is a crappy segway to the step-by-step, leave me alone.

##### Step one: Key Combo/hole Of Death

So, First things first, you need to back up, back up, backup! whether you use google drive or an SD card, I don't care. Your Chromebook will powerwash throughout the process of entering dev mode, which will delete *all* user data stored on the hard drive/SSD/On-board storage.

Okay, Backed up? now, here's a funky key-combo: `esc + ⟳ + ⏻` or `esc + F3 + ⏻`

alternatively, on a chromebox, there should be a little hole called the recovery hole, usually by the kesington lock(the little rectangle thing that's not a USB port). if you can't find it, just google search "\[Your model name here\] recovery hole. you'll also need a paperclip or something to stick in the hole. Now, While the chromebox is off, stick the paperclip in the hole and turn on the chromebox.

both of these methods will bring you to a screen saying "chrome OS is missing or damaged" with a big, orange "!".

##### step 2: `CTRl + D` Makes my day

Now, On the screen with the big, orange "!", don't follow the recovery instructions. instead, to bypass this screen, press `CTRL + D`. now, you should see a screen saying "to turn off system verification, press enter/space" follow these instructions, and turn off system verification.

>note that this is your last chance to press the power key to go back to the login screen before the powerwash

##### Step 3: Waiting, a lot of waiting 

Now, You should be seeing a screen saying "system verification is turned off." press `CTRL + D` to bypass it.

Now, there'll be a screen saying "preparing your device for developer mode. turn off your computer now to cancel" sit there and wait patiently, because your patience will be rewarded.

eventually, after 30 seconds or so, your chromebook will now pop up a funky screen saying "your system is switching to developer mode. please do not turn off your computer." you'll also see a timer in one of the top corners for 5-10 minutes. this is how long your computer will take to switch to dev mode(that's a long time, huh). so go grab a snack, watch some YouTube, and wait like a good boy/girl.

##### step 4:  I'M DONE WAITING, LETS GO! 

kk, now that ur done waiting(RIP in kill speiling), you'll see the "system verification is blah blah blah" screen again. again, press `CTRL + D` to bypass it

##### Step 5: trollge.

trollge.
⣀⣠⣤⣤⣤⣤⢤⣤⣄⣀⣀⣀⣀⡀⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠉⠹⣾⣿⣛⣿⣿⣞⣿⣛⣺⣻⢾⣾⣿⣿⣿⣶⣶⣶⣄⡀⠄⠄⠄
⠄⠄⠠⣿⣷⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⣿⣿⣿⣿⣿⣿⣆⠄⠄
⠄⠄⠘⠛⠛⠛⠛⠋⠿⣷⣿⣿⡿⣿⢿⠟⠟⠟⠻⠻⣿⣿⣿⣿⡀⠄
⠄⢀⠄⠄⠄⠄⠄⠄⠄⠄⢛⣿⣁⠄⠄⠒⠂⠄⠄⣀⣰⣿⣿⣿⣿⡀
⠄⠉⠛⠺⢶⣷⡶⠃⠄⠄⠨⣿⣿⡇⠄⡺⣾⣾⣾⣿⣿⣿⣿⣽⣿⣿          
⠄⠄⠄⠄⠄⠛⠁⠄⠄⠄⢀⣿⣿⣧⡀⠄⠹⣿⣿⣿⣿⣿⡿⣿⣻⣿
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠛⠟⠇⢀⢰⣿⣿⣿⣏⠉⢿⣽⢿⡏
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠠⠤⣤⣴⣾⣿⣿⣾⣿⣿⣦⠄⢹⡿⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠒⣳⣶⣤⣤⣄⣀⣀⡈⣀⢁⢁⢁⣈⣄⢐⠃⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⣰⣿⣛⣻⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡯⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⣬⣽⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⢘⣿⣿⣻⣛⣿⡿⣟⣻⣿⣿⣿⣿⡟⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠛⢛⢿⣿⣿⣿⣿⣿⣿⣷⡿⠁⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠉⠉⠉⠈⠄⠄⠄⠄⠄⠄

##### Step 6: Now ya gotta set it up...

so, after you bypass the verification screen, you'll see the normal setup screen. go through the normal setup process, and you'll be in developer mode.

>note that this screen will appear every time your chromebook reboots in developer mode. you can bypass it by typing `CTRL + D` 

## cool tricks!

You Can Open The bash shell by pressing `CTRL + ALT + T`, then typing `shell`, then hitting the `enter` key!

you DualBoot chromeOS and linux using crouton, and find a really detailed guide about it [here](https://github.com/dnschneid/crouton "crouton readme and stuff by a dude named dnshneild")

you can Delete chromeOS! Please Don't, it'll screw your chromebook up real bad unless you install linux or something!

...You can Install Linux by using a distro called "gallium OS!"

Or If you hate open source software, you can install windows 10 by using an .exe application called "Rufus!"

Windows 10 invading your privacy? you can also install windows 8.1 using rufus on a windows 8.1 computer!

## Other chromeOS boot modes

So, you know how you used `CTRL + D` to bypass the "system verification is off" screen All the way back in step 3? you can actually use other key combos to do other things, such as booting to the legacy BIOS(all though there's some things you need to do before you can), or booting from an USB/SD. soo uhhh, here they are:

`CTRL + U` boots from an USB stick. 

`CTRL + L` boots from zee legacy seaBIOS, *but*, you have to do some and some first, and it's to long to explain how, so I'll just tell ya to go [to mr. chromebox's website](https://mrchromebox.tech/#bootmodes "Just Click me, cmon."). 

## Kid Named Finger:

Kid named finger:
⠀⠀⠀⠀⠀⠀⠀⠀⣀⣴⣶⣿⣿⣿⣿⣿⣿⣿⣶⣦⣀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⣤⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣄⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠀
⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣛⣻⣿⣿⣟⣿⣿⣿⣷⠀⠀⠀
⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣫⣽⣾⣻⣾⣿⣿⣿⣿⡿⣿⣿⠀⠀⠀
⠀⠀⠀⢰⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠻⡿⠿⠟⠛⣟⣿⣽⠀⠀⠀
⠀⠀⠀⠸⣿⣿⣿⣷⣿⣿⣿⣿⡿⠍⠈⠀⠁⣴⡆⠀⠀⠠⢭⣮⣿⡶⠀⠀
⠀⡴⠲⣦⢽⣿⣿⣿⣿⣿⣟⣩⣨⣀⡄⣐⣾⣿⣿⣇⠠⣷⣶⣿⣿⡠⠁⠀
⠀⠃⢀⡄⠀⢻⣿⣿⣿⣿⣽⢿⣿⣯⣾⣿⣿⣿⣿⣿⢿⣿⣿⡟⣿⠀⠀⠀
⠀⠀⠣⠧⠀⢿⣿⣿⣿⣿⣿⣿⣿⣿⠟⢸⣿⠿⠿⠿⣧⠙⣿⣿⡿⠀⠀⠀
⠀⠀⠀⠁⠼⣒⡿⣿⣿⣿⣿⣿⣿⣿⣠⣬⠀⠀⠀⠀⣾⣷⡈⣿⡇⠀⠀⠀
⠀⠀⠀⠀⠀⠉⢳⣿⣿⣿⣿⣿⣿⣿⢟⠗⠼⠖⠒⠔⠉⠉⠻⣿⠇⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠈⣻⡿⣿⣿⣿⣿⡿⡀⣤⡄⠸⣰⣾⡒⣷⣴⣿⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠂⢸⡗⡄⠘⠭⣭⣷⣿⣮⣠⣌⣫⣿⣷⣿⣿⠃⠀⠈⠀⠀
⠀⠀⠀⠀⠀⠈⠀⢸⣿⣾⣷⣦⡿⣿⣿⣿⡿⢻⠞⣹⣿⣿⠏⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⢘⠀⠘⢻⡿⢿⣋⣤⣤⠌⠉⠛⠛⠀⠈⠉⠁⠀⠀⠀⠀⠀⡀
"Is that you in the foir suit, woltuh?"

## A bunch of links for more dev mode stuff

So, we're very fastly approaching the end of this document file thingy, so, I'm gonna give you a few more links for dev mode stuff. you can also click the documents in the document tree to learn more about specific stuff.

[r/chromeOS on reddit](https://reddit.com/r/chromeOS/ "r/chromeOS") 

[chromeOS unofficial discord](https://discord.gg/chromeOS/ "chromeOS server")

[chromeOS dev docs official wiki](https://chromium.googlesource.com/chromiumos/docs/+/HEAD/developer_guide.md "them dev docs").

[mr. chromebox and his wonderful firmware](https://mrchromebox.tech "yaayyy firmware!")

[Wanna learn about crouton?](https://github.com/dnschneid/crouton)

[see me on reddit](https://reddit.com/u/yeetsupwillneverdie "the reddit admins hate me so much i had to tell them id never die through my username")

[see my stalker on reddit](https://reddit.com/u/g1zm08)

[a random telegram group that has nothing to do with chromiumOS](t.me/YeetsupsCult "when you start a cult on telegram")

[a random discord server that has nothing to do with chromiumOS](https://discord.gg/ypqsab8gVk "warning, not for the light-hearted!!")
## goodbye

goodbye. just goodbye. I hope this .MD document helped someone learn about chromeOS and it's developer mode. 



goodbye, and see you next time

*-yeetsup*
