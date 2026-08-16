# what is UDP ?
  UDP (User Datagram Protocol) is a Transport Layer protocol used to send data quickly over a network without first establishing a connection.

[*]  UDP (User Datagram Protocol) ek Transport Layer protocol hai jo bina connection establish kiye network par fast data transmission karta hai.

🔹 UDP kaise kaam karta hai?

TCP mein pehle connection establish hota hai, lekin UDP mein aisa nahi hota.

Sender                    Receiver
  │                          │
  │──── Data Packet ────────>│
  │──── Data Packet ────────>│
  │──── Data Packet ────────>│

UDP directly data packets bhej deta hai.

👉 Receiver ko har packet ke liye acknowledgement (ACK) nahi bhejna padta.


🔹 UDP ki Important Features
1️⃣ Connectionless

UDP does not establish a connection before sending data.

[*]  UDP data bhejne se pehle connection establish nahi karta.

2️⃣ Fast

UDP has low overhead, so it can transmit data quickly.


[*]  UDP mein overhead kam hota hai, isliye ye fast communication provide karta hai.

3️⃣ No Guaranteed Delivery

UDP does not guarantee that every packet will reach the destination.

[*]  UDP guarantee nahi karta ki har packet destination tak zaroor pahunchga.

4️⃣ No Guaranteed Ordering

UDP does not guarantee that packets will arrive in the same order they were sent.

[*]  UDP ye guarantee nahi karta ki packets same order mein receive honge.

Example:

Sent:     1 → 2 → 3 → 4


Received: 1 → 3 → 4 → 2
5️⃣ No Retransmission

UDP generally does not retransmit lost packets.

[*]   Agar UDP ka koi packet lost ho jaye, UDP normally us packet ko dobara send nahi karta.

🔹 UDP ka use kahan hota hai?
      
  UDP un situations mein useful hai jahan speed aur low delay important hota hai.

Examples:

🌐 DNS queries
🎮 Online gaming
📹 Live streaming
📞 Voice/Video communication
📡 DHCP
🔹 UDP Port Numbers

UDP bhi port numbers ka use karta hai.

Examples:

DNS → Port 53
DHCP Server → Port 67
DHCP Client → Port 68


⚔️ TCP vs UDP
TCP                                     	UDP
Connection-oriented                	Connectionless
Reliable delivery                 	No guaranteed delivery
Ordered delivery                  	No guaranteed ordering
Retransmission possible            	No TCP-style retransmission
More overhead                      	Less overhead
Generally slower                  	Generally faster
Example: HTTPS, FTP, SSH          	Example: DNS, DHCP, gaming


🧠 Easy Trick

TCP = Reliable 📦
UDP = Fast 🚀

Socho:

TCP: “Pehle connection banao, data check karo, confirmation lo.”
UDP: “Data bhejo aur jaldi aage badho.” 😄



Hindi:

UDP ek connectionless Transport Layer protocol hai jo low overhead ke saath fast communication provide karta hai, lekin reliable aur ordered delivery ki guarantee nahi deta.
