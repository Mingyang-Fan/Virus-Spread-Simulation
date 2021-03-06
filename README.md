# Virus-Spread-Simulation

This is a project made with Java that simulates the spread of a virus like [Coronavirus](https://en.wikipedia.org/wiki/Coronavirus) in a city. Theoretically. In reality, things are much more complicated than this. I made this simulation mainly so I can push out a video encouraging people to be socially distant and stay isolated. 

This is an [Eclipse](https://www.eclipse.org/downloads/) project.

*__DISCLAIMER__*: I am not a doctor nor am I a physician or a nurse. However, I still encourge watching the video:

[Click here to see my YouTube video on this simulation.](https://www.youtube.com/watch?v=cPVoEWtszag&t=)\
[Click here to see a much better video about a related project.](https://www.youtube.com/watch?v=gxAaO2rsdIs&t)

___

Instructions:
* Green circles represent healthy people, Red represents sick people and blue, recovered people.
* Press the 'r' key to restart the simulation.
* Resize window if you want to increase distance between people.
* To activate walls in order to simulate quarantine. Just set the *quarantine* property in the *Location.java* file equal to *true*. like so:
  
  ```java
    private boolean quarantine = true;
  ``` 
* To change the number of people in the city. Just set the *pSIZE* constant in the *Location.java* file equal to any number you want, like so:
  
  ```java
    private final int pSIZE = 75;
  ``` 
___

This is how *quick* a virus can spread if the population is not practicing any preventative measures:

*__VERY QUICK SPREAD__*

![](regular.gif)

___

This is how the virus spreads when people are socially distant:

*__MUCH SLOWER SPREAD__*

![](social_dist.gif)

___

This is what happens when people are self-isolated:

*__ONLY SPREADS TO QUARANTINE PARTNERS. VIRUS IS ISOLATED AND DISAPPEARS QUICKLY__*

![](quarantine.gif)