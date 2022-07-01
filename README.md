# Soilpunk_joulethief

alternative for soilpunk workshop HDSA2022<img src="./images/soilpunkwsimage.jpg" alt="" width="600"/>


*ALTERNATIVE SCRIPT - SOILPUNK*

In this workshop we will imagine and try out ways to radically reduce the energy use associated with communication technologies such as the Internet. 

The workshop incorporates two experimental approaches simultaneously: one that is focused on peeling back to the bare-bones of communication, and creating our own far from flawless but hyperlocal interpersonal protocols for information transfer. 

And secondly: by exploring the strategies from DIY biotechnology where bacteria found in local iron-rich soil are harnessed to generate and store energy. SoilPunk: muddy speculations on desirable techno futures. 

## Materials and tools

**For the mud battery**

*Materials*

* this
* this
* that

*Tools*

* this
* this
* that

**For the joule thieves**

*Materials*

* a small breadboard
* an LED (and optional: a small buzzer)
* an NPN Transistor 2N3904 (this type has an EBC pinout which is pictured in the instructions, if you take another NPN transistor, check pinout and adjust accordingly)
* a 1K and/or 2K ohm resistor
* a ferrite toroid with an inner diameter of 9mm or so
* a 1.5V AA battery (doesn't need to be full)
* thin enameled copper wire, about 100 cm
* 2 crocodile clips
* a few jumper wires will be handy
* a momentary switch (a push button)
* an AA battery clip (1 cell)

<img src="./images/parts.jpeg" alt="" width="600"/>


*Tools*

* a lighter to melt the enamel off the copper
* sand paper (to sand the copper wire removing last bits of enamel)
* a multimeter
* clippers to cut wires

## Prior knowledge that will come in handy

To build the joule thief you will need to have basic working knowledge of how to use a multimeter (or watch a couple of youtube videos and you'll be fine too). It's handy if at least one person has basic knowledge of how to build and troubleshoot a breadboard circuit. But just looking carefully at the images and checking your own set up will probably get you there as well! And you can contact us for help via Zulip! 

* [A multimeter tutorial](https://www.youtube.com/watch?v=bF3OyQ3HwfU)
* [How to use a breadboard](https://www.youtube.com/watch?v=6WReFkfrUIk)
* [Background info on how inductors work](https://www.youtube.com/watch?v=KSylo01n5FY)
* [	Video of someone else who made a joulethief](https://www.instructables.com/Joule-Thief-Circuit-How-to-Make-and-Circuit-Explan/)

## VERSION 1 (IN-PERSON)

Duration: 8 hours (2x4 hrs, should have a one day break in between to charge battery)
Before starting: check kit and supplies (some shopping might be necessary)

### Day 1 - duration: 3-4 hours

Today we make the power supply with soil, bacteria and time

#### Intro Hackitects (pre-recorded video + written instructions)

Steps

Steps



#### Make DIY biobatteries from iron-rich soil with materials supplied 

Steps

Steps


#### Allow the bacteria to multiply and charge the biobattery for at least 24 hours

Info


### Day 2 - duration: 3-4 hours

Today we make an inductor circuit (joule thief) to amp up the small voltage we get from the mud battery. Take a look at [this video](https://www.instructables.com/Joule-Thief-Circuit-How-to-Make-and-Circuit-Explan/) to get the basic idea. This circuit will allow us to create light and sound signals, which could be seen as basic elements needed to encode and send information (on/off, zeros/ones, lights/no light, sound/no sound). We propose to explore the concept of communication protocols we encounter every day, and create our own protocols for communication using a very bare bones, hyperlocal, low energy infrastructure. 

#### Intro by H&D

Exchange thoughts about communication protocols in different contexts (walkie talkie, SPI, IP, daily life) using the background information and prompts provided in the workshop script, e.g. [this wiki page](https://en.wikipedia.org/wiki/Communication_protocol), or for example [this youtube video](https://youtu.be/kkMVv0dMavM) 

* example + questions to think about
* example + questions to think about

This short text migt be interesting to read and discuss together: Byfield, Ted (2008) “Information” in: Matthew Fuller (ed) Software Studies: a Lexicon. Massachussetts, MIT Press: p. 125-131. [PDF here](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiVsvmbrtf4AhXCuKQKHaMcBe8QFnoECA8QAQ&url=https%3A%2F%2Fmonoskop.org%2Fimages%2Fa%2Fa1%2FFuller_Matthew_ed_Software_Studies_A_Lexicon.pdf&usg=AOvVaw3hRsaRblaUFCh9FChmyOqc)

* Reading question 1
* Reading question 1



#### How to make the most of a battery: DIY inductor intro (Joule thief)

We will build an inductor circuit that can power an LED with as little as 0.5V (in comparison: typically you need 2V). Our mud battery is likely to be able to supply this amount after 24 hours if all went well. We added a button to the circuit so the device can double as an extremely simple communication device. By connecting the LED you can send light patterns using the button. If you replace the LED with the little buzzer you can send sound signals. 

<img src="./images/joulethief_simple.jpeg" alt="" width="600"/>

If you only have the afternoon: make 2 groups. One group makes joule thieve devices. The other group makes pairs and designs communication protocols. If you have the luxury of time: do it all!

**GROUP 1**

Build a joule thief circuit with the components provided, following the step-by-step instructions in the script (will be translated adaptation of this [Dutch tutorial](https://ingegno.be/realisations/jouledief.html)) There are a lot of similar tutorials so if anything is unclear it's worth looking around a bit, maybe somebody else has a way of explaining that is clearer for you :) 


##### Step 1: prepare the inductor 

* Gather the tools and materials listed at the top. 


<img src="./images/copperwire.jpeg" alt="" width="600"/>

- take approx. 100cm of enameled copper wire and fold in half
- try not to make bumps and tangles, keep wire nice and smooth
- loop the closed end through the ferrite toroid, keep about 4 cm 

<img src="./images/11windings.jpeg" alt="" width="600"/>

- make 11 windings with the double, make sure they sit next to each other neatly
- clip the ends, make sure you have about 4 cm left
- now clip the closed end of the loop from the beginning of the coil

<img src="./images/markwires.jpeg" alt="" width="600"/>

- you now have 2 separate wires wrapped around the ring, creating 4 loose leads: 2 at the beginning, and 2 at the end of the coil
- take a multimeter and match which lead at the beginning is connected to an end lead (use the continuity setting, if it beeps, it's the same wire).

<img src="./images/connectwires.jpeg" alt="" width="600"/>

 
- what we now want to do is take a lead from the beginning of (and going into) the coil, and connect it to an one of the end leads coming out of the coil. But these two should not be the same wire! So check with the multimeter that it's the other wire you are connecting (see images). Wrap these around each other a couple times, making sure you still have 2 cm untangled wire at the end. In the pictures we marked the two different wires with two piece of tape before coiling, then you can see it without a multimeter too. 

<img src="./images/stripwires.jpeg" alt="" width="600"/>

- now for all four ends, take a lighter and burn off the plastic enamel wrapping the copper wire (you might not see it but it's there and acts as an insulator, preventing electricity to go through). 
- sand off the ends until you see copper color that is slightly lighter than before.
- this is your inductor! the two connected leads will be connected to the positive + side of your AA or mud battery, and the two other separate leads are connected to the transistor and the resistors as shown in the images of the circuit. 


##### Step 2: make the circuit with an LED

Gather all your components. These should be in the kit provided to your node, or if you are a remote participant, you will have received a shopping list. The parts might look slighty different but recognisable. You will also receive a battery clip for easier connecting to the breadboard with crocodile clips.

<img src="./images/circuit_led.png" alt="" width="600"/>

**LED**
Note that this part has polarity, so should be connected with the right orientation. The LONGER leg (usually with the bend) is marked in RED in the diagrams. The SHORTER leg is marked in BLACK in the images and is always connected to GND (or -).

**NPN transistor**: Note that this part also has an orientation. In the diagram you see that the transistor's flat side is facing you, and the round side is facing the away. Make sure you copy this orientation when you connect it to your breadboard.

**Your inductor coil** obviously looks different :) In the diagram you see the two wires making up the coil marked with a different color (blue or yellow). Ours are both copper colored but you will have marked them with tape or measured with a multimeter. The leads on the right are connected to row 14, with the + side of your battery. You can either wrap them making one leg so to speak, or keep them separated and just connect both on row 14. Both options are a way of connecting them.

The leads on the left side of the coil are not connected to each other. One goes to the Emitter (E) of the transistor (row 5) and one is connected to the the resistor (row 7).

**Button**: has 4 legs. In the diagram, the two legs on the left are connected, and the two legs on the right side are connected too. When the button is pressed, the left side and the right side make a connection too (allowing electrons to flow). On the back side you can see marks showing you which legs are connected. If unsure, check with the multimeter (continuity setting). If your button is not working, you can try rotating it 90 degrees, you might have it connected in the wrong orientation.

**Resistor** has no orientation, either way is fine. You can influence the working of the circuit a bit by trying different values. If you have more resistors: try some in the range of 400-2000ohm and see what happens!

[Example of the working circuit with a LED](https://www.youtube.com/watch?v=umFwwJs-5BA)

[Example of the working circuit with a buzzer](https://www.youtube.com/watch?v=va7Zxcri2gk)

<img src="./images/schematic.png" alt="schematic diagram of the circuit" width="600"/>


##### Step 3: test the circuit with a 1.5V battery

Check that your circuit works by connecting one 1.5V AA battery to it. The LED should go on when you press the button. If it doesn't work: 

1. check all the connections again, wiggle them a little, make sure they're firmly in the breadboard
2. check again that all the connections are in the right rows/columns on the breadboard
3. try another battery (safe bet is to try with one that has at least 1V left)

*Optional*: replace the LED with a buzzer to send sound signals. The sound may be lower/higher depending on the amount of windings in your coil, and the Voltage of the battery. Changing the value of the resistor can tweak this a bit (try some resistors in the 200-2000 Ohm range if you have them).

<img src="./images/circuit_buzzer.png" alt="" width="600"/>

##### Step 4: connect the mud battery to the circuit

Test the mud batteries with a voltmeter and find the positive and negative pole.

* Find the positive and the negative pole. If you try to measure the Voltage of the battery and the display gives a negative images: your probes are the wrong way around (you're holding the black lead to the positive pole of the battery instead of the negative pole). If it reads a positive value: your red probe is touching the positive pole and the black probe is touching the negative pole. With this information you should be able to replace your AA battery with the mud battery the right way around. 
* if it measures 0.5V or higher proceed with single battery
* if it measures less than 0.5V, connect two batteries in series. For more info: [https://www.batterystuff.com/kb/articles/battery-articles/battery-bank-tutorial.html](https://www.batterystuff.com/kb/articles/battery-articles/battery-bank-tutorial.html) 


**GROUP 2**

Group 2 can pair up or make groups and design a communication protocol. How can you convey information with only on/off? How does the receiver now when to be alert? How do they know when the message is ended? Communicating is as much about listening as it is about sending. What might be ways to attune? How might this translate to the simplest of forms? In comparison: a simple walkie talkie protocol entails some agreements such as: 

* opening with: "person A to person B, over"
* responding with: "person B to person A, over"
* closing with: "over and out"

Research and think a bit more on this together, and try to create an analog communication protocol to send e.g. an SMS (160 characters), an emoji, an image, a phone number, other. 

* *Question to consider*
* *Question to consider*


**TOGETHER**

* Connect your joule thief to the mud battery and see if it works. We haven't tried this yet, so it really is an experiment! 
* Try sending information using your joulethief, using your communication protocol
* Share the resulting messages, discuss how and when entropy (noise) entered the process
* Display your mud batteries with LED lights in your space :) 



## VERSION 2 (HYBRID) 

Duration: from 4 hours (half a day) up to 8 hours spread out over 2 days, depending on selected activities

Materials list should be shared with remote participants ASAP so they can order components and do shopping

Node facilitates a session for participant to pair up based on shared interest, choose one or more of the following:

Make a mud battery (work together remotely in small groups, those who were able to get materials), note that it needs to rest to charge! 

Make a joulethief (those who were able to get the materials) and use it with an old half-empty AA battery

and/or:

Design a communication protocol and test it out via webcam/audiocall. This can be done with readily available household materials, like a small torch or penlight, knocking on the table for sound, flashing a red piece of paper at a webcam.

Before starting: decide on moments to check back in together, and when you will stop working on the activity, and how and when you would like to wrap it up (e.g. sharing and discussing with all participants in the node)



