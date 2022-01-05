# MPC LIVE II Tutorial
Welcome to this tutorial for the MPC LIVE II!  
This particular MPC (**M**usic **P**roduction **C**enter) in front of you is one of the recent models in a long history of music devices developed by the Japanese company Akai. 

![MPC gif'd](https://33.media.tumblr.com/e8319b663e1ccbd6406e5e41e44a1d5f/tumblr_n916rkRm451rrb2jro1_r1_500.gif)  
[MPC gif'd](https://robynthinks.wordpress.com/2015/10/30/mpc-gifd/)

MPCs influenced the history of hip-hop significantly, for they are best know for their capability to aid you during the creation of [Dope Ass Beats (DAB)](https://www.youtube.com/watch?v=hRlGHMQfmPA).  
In this tutorial, you’ll learn how to make a DAB of your own.

While the first MPCs can be thought of as samplers, the MPC LIVE II is a Linux computer running a DAW, enclosed within a very sophisticated MIDI + audio interface.   

Have a look at all the connections on the back!   
Using these, you can easily control and record your hardware synths, record anything you like (your voice?) and perform songs in a live setting. During this tutorial, it might dawn on you that you prefer the MPC workflow over your conventional DAW (Logic, Live etc.) and that’s completely valid. 

Before we dive into the meat of this tutorial, a quick note on the images that I use: With the MPC LIVE II, I haven’t figured out a way to take screenshots. Even Akai themselves does not use any in their manuals. This is why I had to rely on the [MPC Bible]( https://www.mpc-samples.com/product.php/268/mpc-bible/?e=%3C%3C%20Test%20eID%20%3E%3E&goal=0_b067d2a12e-23c9c5309f-) by Andy Avgousti for screenshots taken with a previous model with an older version of the software. Because of that, the screenshots do not always fit perfectly.

## The Basics
To turn the MPC on, press the **POWER** button on the back.   

![POWER](/imgs/01.png)

The pads will light up and the screen is gonna flash. One of the great features of this model is its touch display!   
Open one the demo project by simply touching it.  This will take you to the **MAIN** view, which serves as our “hub area”.   
Press the **PLAY** button to start the music and **STOP** to stop it (surprising, I know).

Do you already hear something?   
Maybe one of the students before you was kind enough to leave the speakers on. If not, you can switch them on the back here.  

![Speakers](/imgs/02.png)

I like it a lot to use the speakers, but you can of course also connect a pair of headphones right next to the speaker switch. To adjust the volume, turn the **MASTER** encoder here:

![MASTER](/imgs/03.png)

Keep in mind that this encoder controls the volume for the speakers as well as for the headphones! While it might be fun to entertain your neighbors with the speakers, keep in mind to turn down the volume if you switch back to headphones (dependent on your model) unless you want to go deaf. 

### Navigation

What I like a lot about the MPC is that offers multiple ways of navigating the software. You can intuitively rely on the touch controls, but in many cases the encoders on the left can speed up your workflow dramatically.   
If you touch the BPM selector for example, you’ll notice a red border around it. 

![BPM](/imgs/06.png)

That means that you can turn the big encoder on the left to change this particular parameter – try it and you’ll hear the tempo of the song change!

![Big Encoder](/imgs/04.png)

Hold **SHIFT** if you want to change the tempo in smaller increments.  
Press down the big encoder to open up an additional window for the selected parameter – this could be a list or a GUI to enter a number like it is for the BPM.   
Another way to increase or decrease the BMP are the **+** and **-** buttons next to the big encoder.   
These context sensitive controls work for most of the MPC software! Since there are so many ways of achieving the same ends, you don’t have to learn any crazy shortcuts. If you think it should work, it usually does. 

#### Q-LINK

There’s another way to speed up your workflow even further: **Q-LINK**.   
Dependent on the view your currently in, you can use the small Q-LINK encoders on the left to change parameters. There are four banks of different controller setups for you to switch between. Hold down the **Q-LINK** button to open an overview of all the bindings. Somewhat confusingly, in some views the Q-Link banks are grouped horizontally, in others vertically. 

![Q-Link banks](/imgs/05.png)

Press the **Q-LINK** button to switch between the different banks – did you notice that the LED underneath indicates which bank you’re currently on?   
Switch to the last bank and turn the first Q-Link encoder to change the BPM without having to select it. 
This approach requires a bit of learning and muscle memory to be effective, but it’s worth it. 

### MAIN View
Let’s talk more about the **MAIN** view really quick.

![MAIN](/imgs/07.png)  

First up, we have the **SEQUENCE** section. You can think of sequences as the individual parts that make up a song, such as the intro, the verse etc. A single sequence can also contain the entire song though.   
You can change the length of the sequence by changing the number of bars.   

A sequence is made of multiple tracks, which contain the MIDI events for your selected **PROGRAM** to play.   
What’s great is that you can change up the tracks for each sequence without one of them affecting the other.  

You can change your program, which creates the sound, in the **PROGRAM** section underneath.   
What might be confusing is that you can assign a single program to multiple tracks at the same time. If you change a program, it changes for all the other ones it is assigned to as well!  

There’s much more to the **MAIN** view, but this is enough for now. If this was all a bit confusing for you – don’t worry about it, you'll figure it out as we go on. 

### MENU View

To switch to a different view, press the **MENU** button and you’ll be presented with a plethora of icons to touch.   
You can also quick-save your project by touching the floppy disc icon.   

![MENU](/imgs/08.png)

Some of these can be accessed by via the buttons such as the **MIX** view. To access the view that is written underneath, such as the **SAMPLER**, press **SHIFT + MIX**. 

### The SHIFT Button

The **SHIFT** button is of extreme importance in general – you can hold it to display different icons on the bottom of the screen in many views. 

### Basic Project Management

Go back to the **MAIN** view and touch the **PROJECT** selector in the top left corner.   

![Projects](/imgs/09.png)  
![Project Management](/imgs/10.png)

Here, you can save your project (which contains all recorded samples) internally or onto SD/thumb drive. You can also export your current selected sequence as a .wav file. Touch the **NEW** icon at the bottom to go back to the starting screen and this time, select an empty project for you to fill.

## Pick your Poison

Now it’s time to choose one out of three tutorials.   
Since the MPC can do so much, it is impossible to cover them all in one tutorial (and I only know a tenth of them myself to begin with…). You can do all of these if you have the time or just choose one that fits your skill level and interests. You can also just go by the audio examples. 

To hear the audio examples within VS code, I recommend [this extension.](https://marketplace.visualstudio.com/items?itemName=sukumo28.wav-preview)

In the first and second tutorial, you'll come across code blocks that look like this:

```
HINT
Some text.
```

These boxes give you additional information that is completely optional. You can skip these if you're running out of time and you definitely don't have to do everything explained in there yourself. 

All of these techniques can be replicated in your DAW too (often much easier...), so hit me up if you're interested in that. 

### [Breakbeat Tutorial](breakbeat_tutorial/breakbeat_tut.md)
In this tutorial, you’ll create a short loop that will [sound similar to this.](breakbeat_tutorial/audio/02.wav)  
This is the tutorial that is the closest to the traditional MPC workflow, since it will show you how to slice apart existing recordings and to stich them back together into something new in a Frankensteinian way.     
Choose this tutorial if you have almost no experience with making music or if you’re unsure about what tutorial to choose. It’s probably the best one. 

### [IDM Tutorial](idm_tutorial/idm_tut.md)
In this tutorial, you’ll also create a short drum loop, [but it sounds quite different this time.](idm_tutorial/audio/07.WAV)  
I took concept of emergence from our CC1 class and applied it to drum sequencing to create a loop that sounds different every time you play it. This tutorial highlights the idea that you can achieve things with the MPC that it was never meant for, as long as you think a bit outside the box.   
You can do this tutorial without any prior knowledge, but it helps if you know the basics of drum programming.   
Choose this if you’re into that kind of that kind of sound.

### [Song Mode Tutorial](song_mode_tutorial/song_mode_tut.md)
This tutorial will show you how to create a whole song [like this one](song_mode_tutorial/audio/01.wav) (can someone please fix the end for me? I got a bit lazy there) instead of just loops. This tutorial requires a basic understanding of some recording concepts such as overdubs and automation. 
Choose this if you’re confident that you can come up with music on your own or if you want to continue one of the earlier tutorials like I did with the second one. 

You must choose, but choose wisely.   

If you run into any issues, just call me.   
Don’t forget to save your final project as “yourSurname-tutorial”; “winter-breakbeat” for example (we’re not allowed to use _ for some reason). 

Good luck and happy music making!  
![Spechouse](https://images.squarespace-cdn.com/content/v1/5af60e6d7106994d8097b88a/1580092865594-L6XZJZRI2ZH110NZPW9A/Spechouse-8bit-Girl-Gif-2-CHAGE.gif?format=1000w)  
[Spechouse](https://images.squarespace-cdn.com/content/v1/5af60e6d7106994d8097b88a/1580092865594-L6XZJZRI2ZH110NZPW9A/Spechouse-8bit-Girl-Gif-2-CHAGE.gif?format=1000w)




