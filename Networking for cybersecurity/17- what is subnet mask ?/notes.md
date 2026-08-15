# what is subnet mask ?
  A Subnet Mask is a 32-bit number used with an IPv4 address to identify which part of the IP address represents 
  the network and which part represents the host/device.

  [*] Subnet Mask ek 32-bit number hota hai jo IPv4 address mein ye identify karta hai ki IP address ka kaunsa part network ko represent karta hai
  aur kaunsa part host/device ko. 

  🔹 Subnet Mask ka main kaam
1. Network aur Host ko identify karna

 It separates the network portion from the host portion.

[*] Ye IP address ke network aur host parts ko separate karta hai.

2. Same Network Check karna

 It helps determine whether two devices belong to the same subnet.

[*] Ye determine karne mein help karta hai ki do devices same network/subnet mein hain ya nahi.

3. Subnetting

 It is used to divide a large network into smaller subnets.

[*] Iska use bade network ko chhote subnets mein divide karne ke liye hota hai.


📌 Common Subnet Masks
CIDR	       Subnet Mask      	Usable Hosts*
/8         	255.0.0.0         	16,777,214
/16       	255.255.0.0        	65,534
/24	        255.255.255.0	        254
/25       	255.255.255.128     	126
/26        	255.255.255.192      	62
/27        	255.255.255.224      	30
/28       	255.255.255.240      	14



.

🧠 Easy Trick

IP Address = Device ka address
Subnet Mask = Network aur Host ki boundary

Example:

IP: 192.168.1.10
Mask: 255.255.255.0

👉 192.168.1 = Network
👉 10 = Host

*Traditional IPv4 subnet calculation: network address aur broadcast address ko usable host addresses mein
