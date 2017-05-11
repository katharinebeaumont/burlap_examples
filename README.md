# burlap_examples
This code is [forked from the example code](https://github.com/jmacglashan/burlap_examples) for BURLAP (http://burlap.cs.brown.edu).

For more information on using BURLAP, see the [website](http://burlap.cs.brown.edu) or the original example [BURLAP repository](https://github.com/jmacglashan/burlap_examples).

For simplicity, other examples have been removed and code and comments have been changed in QLTutorial.java.
 
# Devoxx UK workshop

If you do not have Maven, [install it](https://maven.apache.org/install.html).

Run `mvn install`.

Go to edu.brown.cs.burlap.tutorials.QLTutorial. 
Run it.
The agent (grey dot) is trying to learn how to get from the bottom left of the screen to the top right in as few steps as possible.

Look in the file for //DEVOXXUK.
Look at the effects of changing gamma, epsilon and the number of episodes.
How quickly can you get the agent to optimise the route through the environment?