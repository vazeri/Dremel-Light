# 10min DIY Light for Dremel work station

### Tired of never getting to see what are you drilling with your Dremel work station?

### Do you have a free afternoon to DIY and fix the problem?

![alt text](https://github.com/vazeri/Dremel-Light/raw/master/Pictures/2015-01-11%2023.03.59.jpg)

Just print out this home-made PCB on a laser printer, unsolder a couple of LEDs and resistances, 
plug in a 5v power supply and you are almost done! 

What do you need?


| Qty           | Component           |
| ------------- |:-------------:|
| 6      | LED 5050 form any led light strip |
| 6      | 470 Ohm SMD resistors (from the same led light strip)   |
| 1 | 5v DC 350mA power supply    |    
| 1 | Super Glue    |    

and a bit of basic soldering skills

![alt text](https://github.com/vazeri/Dremel-Light/raw/master/Pictures/2015-01-11%2023.04.37.jpg)
 
 # Why didn’t you use professional CAD PCB Software?
 
This is intended to be a beginner project into led lighting and electronics, I used adobe illustrator
to make a "quick" revised version of a
 project published at http://www.instructables.com/id/Make-your-own-LED-ring-for-dremel/ in 2015  

I will leave the vectorized PCB here, WITH NO INTENTIONS to make it a schematic nor Gerber files it’s supposed to be 
a useful but 10 min project, so no advanced engineering software is involved, feel free to fork it, share 
it or change anything you don’t like

This is a really god project for electronic hobbyists 


# How did you do this?

Using a heat gun, I desoldered the SMD leds and resistors from a 5050 led light 
strip, these 5050 leds have 3 diodes inside, the total current 
is 350mA for all the circuit (9 leds), and the input voltage is 5v and each 
resistor is 470 ohms, a bit or ironing the PCB and some drilling and sanding with my Dremel and I was done.

  # How do I Print this with no GERBER files?
 
Just use Windows integrated print capabilities, you can print 
easily using windows and selecting the “pocket” size, remember to check the 
reframe image”

![alt text](https://github.com/vazeri/Dremel-Light/raw/master/How%20to%20print.JPG)
 
 also make sure to 
 
1. Print out your design on a LASER Printer, an inkjet will not work, Glossy paper is the best to use 

2. Place your Board design on your copper clad board & iron it on the hottest temperature for about five minutes, 
just to be sure all the toner has been transferred. 

3. Place your board in cool water for a few minutes, then rub the paper off. You should be left with the design on 
the copper clad board. 

4. Etch the board. I use one part of hydrochloric acid diluted in five of hydrogen peroxide. it takes about 5 minutes to etch. 

5. Once your board is etched, remove the left-over toner. There are a few methods to do this. I use a mixture of steel wool (To get the toner off to a rough standard) then clean the board up with acetone to ensure there are no bits of toner on the board.

# Can you explain me how does it work?
 
All the LEDs are in parallel, this way each one needs to have a separate current limiting resistor for each. 

Otherwise you'll drastically reduce the lifespan of whichever of the nine LEDs happens to have the lowest
forward voltage. 

If you put them all in series, you can get away with a single resistor, but then you're working with fairly high voltages. 

A good compromise may be to make strands of three LEDs in series with a resistor, and then to put three of those strands in parallel.


 
---

If you have any questions you can send me a message on my webpage vazeri.github.io and I´ll answer as soon as I can. 
This work is an open source, non-profit project under the MIT License
