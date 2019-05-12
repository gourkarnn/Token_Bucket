# Token_Bucket
Implementation of Token Bucket using thread in java and Swing to display animation of token Bucket concept.

TOKEN  BUCKET LOGIC:

1.	In token bucket the packets to be sent on network are only possible if the required amount of tokens are present inside the bucket.
2.	For one packet to send on network one token should be charged.
3.	There are two threads inside the main thread which is looking after the process.
4.	One thread generates the tokens inside the bucket whereas another thread requests for the packets which is to be sent in network randomly.
5.	The class Bucket is made so that is a variable sharing between the two threads.
6.	Inside the bucket class there are two methods which are synchronized for the variable sharing mechanism in synchronization.
7.	The timer is used to evaluate the time required for sending the packets on network.



The swing drag and drop of netbeans is used to design the frame for simulation
1.  The arraylist is maintained to store the integers corresponding to the state of token at that particular instance.
2.  The arraylist is traversed in the order in which the integers were stored to get the actual animation.
