# Lab 1
1. List 3 different protocols that appear in the protocol column in the unfiltered packet-listing window in step 7 above.
```
1. TCP
2. MDNS
3. TLS
```

2. How long did it take from when the HTTP GET message was sent until the HTTP OK reply was received?
```
0.093198
```

3. What is the Internet address of the gaia.cs.umass.edu (also known as www- net.cs.umass.edu)? What is the Internet address of your computer?
```
128.119.245.12
10.3.8.53
```

4. Print the two HTTP messages (GET and OK) referred to in question 2 above. To do so, select Print from the Wireshark File command menu, and select the “Selected Packet Only” and “Print as displayed” radial buttons, and then click OK.
```
No.     Time           Source                Destination           Protocol Length Info
   1408 5.517805       10.3.8.52             128.119.245.12        HTTP     473    GET /wireshark-
labs/INTRO-wireshark-file1.html HTTP/1.1
Frame 1408: 473 bytes on wire (3784 bits), 473 bytes captured (3784 bits) on interface en0, id 0
Ethernet II, Src: Apple_13:f5:99 (f0:2f:4b:13:f5:99), Dst: Ubiquiti_9f:e1:ad (24:5a:4c:9f:e1:ad)
Internet Protocol Version 4, Src: 10.3.8.52, Dst: 128.119.245.12
Transmission Control Protocol, Src Port: 56924, Dst Port: 80, Seq: 1, Ack: 1, Len: 407
Hypertext Transfer Protocol
    GET /wireshark-labs/INTRO-wireshark-file1.html HTTP/1.1\r\n
    Host: gaia.cs.umass.edu\r\n
    Upgrade-Insecure-Requests: 1\r\n
    Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8\r\n
    User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like
Gecko) Version/15.5 Safari/605.1.15\r\n
    Accept-Language: en-US,en;q=0.9\r\n
    Accept-Encoding: gzip, deflate\r\n
    Connection: keep-alive\r\n
    \r\n
    [Full request URI: http://gaia.cs.umass.edu/wireshark-labs/INTRO-wireshark-file1.html]
    [HTTP request 1/1]
    [Response in frame: 1411]
No.
   1411 5.611003       128.119.245.12        10.3.8.52             HTTP     504    HTTP/1.1 200 OK
Time           Source                Destination           Protocol Length Info
(text/html)
Frame 1411: 504 bytes on wire (4032 bits), 504 bytes captured (4032 bits) on interface en0, id 0
Ethernet II, Src: Ubiquiti_9f:e1:ad (24:5a:4c:9f:e1:ad), Dst: Apple_13:f5:99 (f0:2f:4b:13:f5:99)
Internet Protocol Version 4, Src: 128.119.245.12, Dst: 10.3.8.52
Transmission Control Protocol, Src Port: 80, Dst Port: 56924, Seq: 1, Ack: 408, Len: 438
Hypertext Transfer Protocol
    HTTP/1.1 200 OK\r\n
    Date: Sat, 16 Apr 2022 22:18:11 GMT\r\n
    Server: Apache/2.4.6 (CentOS) OpenSSL/1.0.2k-fips PHP/7.4.28 mod_perl/2.0.11 Perl/v5.16.3\r\n
    Last-Modified: Sat, 16 Apr 2022 05:59:01 GMT\r\n
    ETag: "51-5dcbf39485167"\r\n
    Accept-Ranges: bytes\r\n
    Content-Length: 81\r\n
    Keep-Alive: timeout=5, max=100\r\n
    Connection: Keep-Alive\r\n
    Content-Type: text/html; charset=UTF-8\r\n
    \r\n
    [HTTP response 1/1]
    [Time since request: 0.093198000 seconds]
    [Request in frame: 1408]
    [Request URI: http://gaia.cs.umass.edu/wireshark-labs/INTRO-wireshark-file1.html]
    File Data: 81 bytes
Line-based text data: text/html (3 lines)
```
