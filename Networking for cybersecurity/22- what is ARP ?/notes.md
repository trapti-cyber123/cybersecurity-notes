# what is ARP ?

  ARP = Address Resolution Protocol
  
 ARP stands for Address Resolution Protocol. It is used to find the MAC address of a device when its IP address is known.

[*] ARP ek networking protocol hai jo IP address se us device ka MAC address find karta hai.

🧠 Simple formula:

IP Address → ARP → MAC Address

🔹 ARP ki zarurat kyu hoti hai?

Network mein kisi device ko data bhejne ke liye IP address se destination device identify hota hai, lekin local network par actual delivery ke liye MAC address ki zarurat hoti hai.

Example:

Maan lo:

PC-A IP = 192.168.1.10
PC-B IP = 192.168.1.20

🔹 ARP ke 2 main messages

1. ARP Request

[*] MAC address poochta hai.
    It asks which device owns a particular IP address.

2. ARP Reply

[*] MAC address ka answer deta hai.
    It provides the MAC address associated with that IP.

🔹 ARP Table / Cache

Computer recently learned IP + MAC mappings ko temporarily store karta hai. Isse baar-baar ARP request bhejne ki zarurat nahi padti.

Example:

IP Address             	MAC Address

192.168.1.20        	AA:BB:CC:DD:EE:FF

192.168.1.30	        11:22:33:44:55:66
  
  
     
