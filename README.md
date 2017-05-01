DNS-Client-Socket

DNS Client using socket programming. Along with a Proxy Server.

### **To Clone the Repository:**

	$ git clone https://github.com/shubhammatta/DNS-Client-Socket.git
**The DNS request is sent as a raw bytes using the format mentioned in 
[RFC 1035 DNS protocol standards](https://www.ietf.org/rfc/rfc1035.txt
)**

### To run the DNS client : 
	$ python DNSC.py 127.0.1.1 53 1 

**Note : Last Argument is the query type: 1 - A 2 - NS 5 - CNAME 6 - SOA 15 - MX code works for above mentioned query types only**

### **The output is printed in the same way nslookup provides output.**

# For query type A: 

![](http://i.imgur.com/nhaRAQy.png)


# For query type NS: 
![](http://i.imgur.com/v38EDbD.png)

# For query type CNAME: 

![](http://i.imgur.com/rTpAZey.png)
 
# For query type SOA: 

![](http://i.imgur.com/OeGMe6S.png)