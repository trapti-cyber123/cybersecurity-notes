#  what is Router ?
   A router is a networking device that connects two or more different networks and forwards data packets to the correct destination.

   [*] Router ek networking device hai jo do ya do se zyada different networks ko connect karta hai aur data packet ko sahi destination tak pahunchata hai.
  

 # Example
  # diagram 
  <img width="1536" height="1024" alt="e692cc92-90ef-4ed5-9bdc-27ae4b251e72" src="https://github.com/user-attachments/assets/071f2afe-44db-4f52-b514-2f75ecc31dc5" />

Maan lo:

        Internet
           |
        [Router]
        /      \
       /        \
   PC/Laptop   Mobile
    Network     Network

Aapke ghar mein router local network (LAN) ko Internet/WAN se connect karta hai.

🔹 Router kaise kaam karta hai?

Device data packet bhejta hai.

Router packet ka destination IP address check karta hai.

Router apni routing table dekhta hai.

Best route choose karta hai.

Packet ko next network/device ki taraf forward karta hai.

PC

 |
 
 | Data Packet
 
 v
 
[ ROUTER ] -----> Internet -----> Server

   |
   
   | Checks Destination IP
   
   v
   
Chooses Best Route

🔹 Router ke main functions

. Network connectivity – different networks ko connect karta hai.

. Routing – data ke liye best path choose karta hai.

. Packet forwarding – packets ko destination ki taraf bhejta hai.

. IP address handling – source/destination IP addresses ke basis par decision leta hai.

. Home routers often NAT, DHCP aur basic firewall bhi provide karte hain.


# types of router 

Router ko mainly routing method aur use ke basis par different types mein divide kiya jaata hai.

# Static Router

[*]  Isme network administrator manually routing paths configure karta hai.

  A static router uses manually configured routes.

Example: Small network jahan routes rarely change hote hain.

# Dynamic Router

[*] Ye routing protocols ki help se automatically best route find aur update karta hai.

 A dynamic router automatically learns and updates routes using routing protocols.

Examples: RIP, OSPF, EIGRP, BGP.

# Wired Router

[*]  Ye devices ko Ethernet cables ke through connect karta hai.

   A wired router connects devices using network cables.

PC ───┐

PC ───┼── [Wired Router] ── Internet

PC ───┘
 
   # Wireless Router

[*]  Ye Wi-Fi ke through devices ko network/Internet se connect karta hai.

 A wireless router provides network connectivity using Wi-Fi.

 Phone )))
 
 Laptop ))) [Wi-Fi Router] ── Internet
 
 Tablet )))
 
# Core Router

[*] Ye large networks ke central/backbone part mein high-speed data forwarding karta hai.

   A core router handles high-speed traffic in the backbone of large networks.

# Edge Router

[*] Ye organization ke internal network aur external network/Internet ke boundary par kaam karta hai.

   An edge router operates at the boundary between an internal network and an external network.

# Virtual Router

[*] Ye physical device ke bajay software/virtual environment mein router ka kaam karta hai.

   A virtual router performs routing functions through software rather than requiring a dedicated physical router.





