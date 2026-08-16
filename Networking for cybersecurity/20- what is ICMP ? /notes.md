# what is ICMP ?
   ICMP stands for Internet Control Message Protocol. It is a Network Layer protocol used by network devices like routers and computers to send error messages, control messages, and diagnostic information.

[*]    ICMP ka full form Internet Control Message Protocol hai. Ye Network Layer ka protocol hai, jo computers aur routers ke beech error, control aur network ki information bhejne ke liye use hota hai.

🔹 Simple Example

Aapka computer kisi server ko message bhejta hai:

Computer → Router → Internet → Server

Agar server available nahi hai ya destination tak packet nahi pahunch sakta, to ICMP ek message bhej sakta hai:

"Destination Unreachable"

Yaani ICMP mainly batata hai ki network mein packet ke saath kya problem hui.

🔹 ICMP ke main uses
.Error Reporting – Network errors ki information dena.
.Network Diagnostics – Network connection check karna.
.Ping – Device reachable hai ya nahi check karna.
.Traceroute/Tracert – Packet kis-kis router se hokar ja raha hai, ye identify karna.

🔹 Ping mein ICMP kaise kaam karta hai?

Jab hum command chalate hain:

ping google.com

Computer ICMP Echo Request bhejta hai.

Agar destination reachable hai, to wo ICMP Echo Reply bhejta hai.

Computer → Echo Request → Server
Computer ← Echo Reply ← Server

Isliye Ping command ICMP ka famous example hai.

🔹 Important ICMP Messages

ICMP Message                          	Meaning
Echo Request                      	Ping request bhejna
Echo Reply                        	Ping ka response
Destination Unreachable            	Destination tak packet nahi pahunch saka
Time Exceeded	                      Packet ka TTL expire ho gaya
Redirect                          	Better route ki information


Yaad rakho:
👉 ICMP = Error + Control + Diagnostic
👉 Ping = ICMP ka common example
