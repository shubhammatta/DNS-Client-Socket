# DNS-Client-Socket
DNS Client using socket programming.
Along with a Proxy Server.

###**To Clone the Repository:**

	$ git clone https://github.com/shubhammatta/DNS-Client-Socket.git
	
**The DNS request is sent as a raw bytes using the format mentioned in 
[RFC 1035 DNS protocol standards](https://www.ietf.org/rfc/rfc1035.txt
) **

###To run the DNS client :
	$ python DNSC.py 127.0.1.1 53 1
Note : Last Argument is the query type:
1 - A
2 - NS
5 - CNAME
6 - SOA 
15 - MX
**code works for above mentioned query types only**

###The output is printed in the same way nslookup provides output.

#For query type A:
![](/home/jarvis/Pictures/screen.png) 

#For query type NS:
![](/home/jarvis/Pictures/screen1.png) 

#For query type CNAME:
![](/home/jarvis/Pictures/screen2.png) 

#For query type SOA:
![](/home/jarvis/Pictures/screen3.png) 

