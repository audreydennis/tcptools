# Ping

**What were the min/avg/max/stddev statistics for each?**

Amazon:
1. min/avg/max/stddev = 12.248/16.487/20.249/2.991 ms
2. min/avg/max/stddev = 5.477/10.702/16.520/4.765 ms
3. min/avg/max/stddev = 10.432/14.636/22.926/3.896 ms

Google:
1. min/avg/max/stddev = 5.552/13.164/17.712/3.849 ms
2. min/avg/max/stddev = 8.206/12.384/15.802/3.049 ms
3. min/avg/max/stddev = 12.977/15.044/16.760/1.441 ms

Microsoft:
1. min/avg/max/stddev = 8.549/12.481/15.369/1.853 ms
2. min/avg/max/stddev = 5.256/12.815/15.720/3.740 ms
3. min/avg/max/stddev = 6.285/14.032/16.235/3.494 ms


**Was there any packet loss on any of the pings?**

There was no packet loss on any of the pings.

**Did the IP address change for a given website between pings?**

Amazon:
The IP address for amazon was different on the first ping from the second two. The first ping to amazon was to (18.65.233.187) while the second two were to (18.172.169.208).

Google:
The IP address remained the same for all pings to google at (172.217.14.228).

Microsoft: 
The IP address remained the same for all pings to microsoft at (23.36.249.251).

# Tracert

**What was the target server's IP address?**

Amazon:
target server IP address: (18.172.169.208)

Google:
target server IP address: (172.217.14.196)

Microsoft:
target server IP address: (23.45.229.117)

**How many hops were needed to reach the target?**

Amazon:

Google:
10 hops

Microsoft:
8 hops

**Can you identify your ISP from the intermediate server DNS names?**

Comcast is my ISP. seattle.wa.seattle.comcast.net is identified in most hops.

**Identify the "class" of IP address for each major step in the trip**

Amazon:
 1. 10.0.0.1 
 3. 100.92.123.66 
 3-9. (ISP) comcast IP addresses **class A** 
 10  66.208.216.222 **class A** 
 11-13. request timed out  (* * *) 
 14  15.230.247.1 class A 
 15  * 15.230.247.1 (15.230.247.1)  14.351 ms * 
 16-64. request timed out  (* * *) 

Google:
 1. 10.0.0.1  class A, router 
 3. 100.92.123.67 class A
 3-7. (ISP) comcast IP addresses class A
 8. 50.222.176.218 class A
 9. 142.251.48.212 class B
10. 172.217.14.196 class B, target Google IP address

Microsoft:
  1. 10.0.0.1 class A, router 
  2  100.92.123.67 class A 
  3-7. (ISP) comcast IP addresses class A 
  8  23.45.229.117 class A, target micosoft IP Address
