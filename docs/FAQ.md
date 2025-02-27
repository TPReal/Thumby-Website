# Frequently Asked Questions

If one of the below options doesn't answer your question(s), you can post on the <a href="http://forum.tinycircuits.com/" target="_blank" alt="Thumby Tinycircuits forum">**Thumby section of our forum**</a>, or get in touch with <a href="https://tinycircuits.com/pages/contact-us" target="_blank" alt="Send a message to tinycircuits support on this page">**customer support**</a>.

---

### Code Editor Connection

**Why is my Thumby not connecting to the Web Code Editor?**

* Make sure you only have one Code Editor tab open - sometimes an older tab can be connected to Thumby and interfere with your current attempt to connect
* Make sure the Thumby device is ON - power switch should be to the right when looking at the screen
* Try a different cable - Since no port is coming up at all when the Thumby is turned on - it's possible that the cable you are using does not have the necessary data lines for communicating with the Thumby. Many Micro USB cables have just the power and ground wires to charge or power electronics. Try another cable, or test that you are able to transfer data with that cable in a different way - possibly by transferring files or pictures from a different device.
* Unplug the device completely and open your 'Device Manager' (windows) -> click on 'Ports' -> plug the device back in to see if anything shows up. For thumby you should see "USB Serial Device (COM##)" where ## can be any number
* If you still don't see anything showing up, try turning your computer off and restart. It's possible you have some serial device interfering with your ability to communicate with Thumby. Such as a USB hub or other peripheral devices, like a mouse.

**The Thumby hardware freezes when it connects to the Code Editor, is it broken?**

Not at all! This is natural behavior. The Thumby hardware appears to stop working, or 'freezes' when you connect it to the Thumby Code Editor. To test changes you upload to the Thumby, you will need to disconnect the unit and power cycle it (turn it off and back on).

---

### Thumby Settings menu

**Can I change the audio and brightness?**

Yes! Turn on the Thumby, scroll down once to the 'GAMES' menu and right once to view the 'SETTINGS'. Here you can press the DPAD down button to the setting you want to alter and press either red action button to change the setting mode:

* Audio: On/Off
* Brightness: Mid/Hi/Low     *-- Note: we couldn't fit the whole word Brightness on the screen, so it reads as just Brite*

The changes automatically save after being changed. 

---

### Thumby Credits

**Where is the credits menu and whose names are on it?**

To view the credits menu on the Thumby, turn Thumby on, scroll down once to the 'GAMES' menu and press the DPAD button right twice to scroll past the 'SETTINGS' menu to see the credits roll 4 names at a time.

Kickstarter backers that selected a Special Edition Thumby were able to submit one 16 character name (or something) on the credits list per Special Edition Thumby purchased. To view the full credits list, you can connect Thumby to the <a href="https://code.thumby.us/" target="_blank" alt="TinyCircuits Thumby Web Browser Code Editor page">**Thumby Code Editor**</a> and view the credits.txt file from the 'filesystem' directory.

---

### Playing and Adding More Games

***How do I play the games on the Thumby?***

Turn on the Thumby and once the "Start" text displays below the Thumby logo, you can scroll down to see the list of games downloaded to the Thumby. There are 5+ games preloaded onto the Thumby.

Select any game with a red action button to start playing. When you want to stop playing or play a different game, turn the Thumby off and back on with the power switch. Thumby will remember the last game you played. When the Thumby is first powered on and the 'Start' text is selected, you can press a red action button to start playing the last game played.

**How do I add more games?**

There are plenty of free games made by the community that you can play on your Thumby. <a href="https://thumby.us/Code-Editor/Arcade-games/" target="_blank" alt="TinyCircuits Thumby add games tutorial">**Check out this tutorial to learn how to add games to Thumby**</a>. 

---


### Multiplayer Link Cable

**Is the Thumby Link cable the same as an OTG cable, or is it different?**


The pin wiring of the OTG cable would need to be verified. 

<center>
![TinyCircuits Thumby Link cable](/images/USB-pinout.jpg)
</center>
<center>
*Micro USB Pinout diagram*
</center>

The Thumby Link cable is a custom cable that connects GND to GND (pin 5), and ID pin to ID pin (pin 4) for data transfer.

---

### Audio

**How can I test that the audio is working?**

Check that the Audio is turned on in the settings menu: Turn Thumby on -> scroll down once -> scroll to the right once -> check that the 'Audio' setting is 'ON'.

Not every game has sound effects, but some of the preloaded games do. You can test audio with the game **SaurRun** - try playing this game and holding the Thumby closer to your ear to hear the tiny piezo sounds while jumping the running Dinosaur. Or play the **TinyBlocks** game to hear tiny ticking sounds as the play blocks fall down the screen.

---

### Charging & Battery Life

**How long does Thumby take to charge? Is there an indicator when it is charged?**

Thumby takes around 1 hour to completely charge. An indicator LED will turn on from inside the Thumby case to show that the battery is being charged. The LED will turn off when the battery is fully charged. The LED is located to the left of the micro USB connector.

*Note: The charging LED may be difficult to see through opaque plastic cases. Try turning off the lights in the room you are in if you are having difficulty seeing the LED while charging.*

**How long can I play Thumby on a full charge?**

You can play Thumby for up to two hours on a full charge. Games that display more white pixels will use more power than games that are darker.

--- 

### Software Updates

**How do I know if my Thumby has the latest firmware/software?**

You can update the Thumby firmware after connecting your Thumby to the Web Code Editor - the files system panel has an 'Update' button that will turn red when it detects your software is not up-to-date. Press the 'Update' button to load the newest software. The update will only overwrite a few core Thumby files.

--- 

### Linux with Thumby

**How do I connect Thumby to a Linux system?**

If you have already tried to connect Thumby to your Linux machine and failed, it's likely you have encountered an error message like: "Could not open serial port /dev/ttyUSB0"

You will need to add your user to the ```dialout``` group to have access to the USB device. Use the command: 

```sudo adduser $USER dialout```

The $USER keyword will fetch your username, so there is no need to alter the command. Then, log out of your user account or restart your machine for the changes to take effect.

---

### Distributing Thumby

**Can I distribute Thumby?**

Yes! Check out the different levels of our <a href="https://tinycircuits.com/pages/reseller-program" target="_blank" alt="Distributor program information">**distribution program**</a> on our main page.