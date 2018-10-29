Honeypot Attacks GIF Walkthrough: ![](https://github.com/ConnorCason/CodePath-Week-9/blob/master/attacks.gif)

Honeypot: 35.196.27.141

Summary: At the time of this writing, the honeypot above collected information about ~35 attacks. These attacks primarily consisted of pcap protocl, but also included SipCall and SipSession protocols. The most attacks by a good margin came from within the U.S, but a significant number of attacks also came from France and China.

Issues: 
-In order to download the correct MHN instance, we had to find the working fork of the RedolentSun repository  
-Had to connect through insecure HTTP to access MHN admin console via browser  
-Using gcloud compute (still in beta) over AWS  