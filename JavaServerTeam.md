# intro

The firstTacoma hackathon was a really interesting experience because the majority of hackathons are primarily attended by intermediate to expert level developers. This hackathan was less of competition 
but more of a learning experience. What Darius, Omar and I learned was the process of creating a server to do data processing from nothing. You can learn a ton in a class room, but how to apply those concepts to build software in the real
world is a completely different story, and is something that I feel hackathons like this one are extremely beneficial for. 

At first we did our own individual research and learned a little about building a java server that
can do data processing. Our first real task was to turn on the local server in our computer. To do that 
we had to learn to use Wamp Server for Windows and theterminal in Mac. We had to add and remove certain lines
of code in the system to get our localhost to point to an html file we created. At first we ran into problems but by going through the terminal and wamp server line by line we were able to turn our computers into our own server.

Once we had achieved that, our objective was to incorporate the Spring framework so that we didn't have to build
the server we created from scratch to actually do data processing. In order to install the Spring framework we had to learn
how to use Gradle which is a thrid party framework development kit. We struggled with it for about a few hours until Kevia showed us Homebrew, which took care of installing Gradle for us. Then the issue was getting Gradle to work with Java. Unfortunately we exhausted the limits of our understanding (and patience) because writing and understanding the Unix code in the terminal is so different than writing in from a normal java IDE.

If we could fully build Gradle and set up the Spring framework, then we'd be in the position to process the data and make sense of it using a language like R. Unfortunately we didn't get to that step since the Gradle step took so much time. But luckily 
our Java server is not necessary to develop the Minimum Viable Product. Our goal was a secondary one and is not nessasary for the actual functioning of the app. As of now it looks like Gradle is having trouble finding a main to run with, but the rest of the app (both front end and back end) are coming along nicely.
 
