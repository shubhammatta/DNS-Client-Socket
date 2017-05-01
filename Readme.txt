To run just the dns client

$ python DNSC.py 127.0.1.1 53 [query type(1,2,5,6,15)]

To run along with DNS proxy server:

First run the server:
$ python server.py

Now run the client with localhost and  port 12001 as argument 

$ python DNSC.py 127.0.0.1 12001 [querytype(1,2,5,6,15)]
