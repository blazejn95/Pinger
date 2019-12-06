DO NOT RUN THIS PROGRAM IF YOU DON'T UNDERSTAND IT
1st the program tries to figure out your default gateway. Then you can run a pinger on a number of threads that you want. Pinger swarms the interface with empty ICMP messages if you remove lines 38-35 the ICMP messages will have HELLO text inside them. The whole thing is basically a ping flood on your gateway.
