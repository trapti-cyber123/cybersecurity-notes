# what is TCP ?
   TCP (Transmission Control Protocol) is a transport-layer protocol used to provide reliable and ordered communication between two devices over a network.

[*] TCP (Transmission Control Protocol) ek Transport Layer protocol hai jo do devices ke beech data ko reliably aur correct order mein deliver karne ka kaam karta hai.

🔹 TCP kaise kaam karta hai?

Maan lo tumhare computer se kisi server ko data bhejna hai.

Computer A                    Server B
    │                            │
    │──── Connection Setup ─────>│
    │                            │
    │──── Data ─────────────────>│
    │<─── Acknowledgement ───────│
    │──── More Data ─────────────>│
    │                            │

TCP pehle connection establish karta hai, phir data transfer karta hai aur receiver se ACK (Acknowledgement) lekar confirm karta hai ki data receive hua.

🔹 TCP ki important features 

1. Connection-Oriented


TCP establishes a connection before sending data.

[*]  TCP data bhejne se pehle connection establish karta hai.

Is process ko Three-Way Handshake kehte hain:

SYN → SYN-ACK → ACK

2. Reliable

TCP ensures that data reaches the destination reliably.


[*]  TCP ensure karta hai ki data properly destination tak pahunch raha hai.

Agar koi segment lost ho jaye, TCP usko retransmit kar sakta hai.


3. Ordered Delivery

TCP delivers data in the correct order.

[*]  Agar data multiple segments mein gaya hai, TCP unhe correct order mein arrange karta hai.

Example:

1 → 2 → 3 → 4

Agar segments kisi different order mein arrive hon, TCP unhe correct sequence mein arrange kar sakta hai.

4. Error Control

TCP uses mechanisms such as checksums and acknowledgements to detect transmission problems.

[*]  TCP checksum aur acknowledgements jaise mechanisms ka use karke transmission problems ko detect karta hai.

5. Flow Control
   TCP controls the amount of data sent so that the receiver is not overwhelmed.

[*]  TCP sender se aane wale data ko control karta hai taaki receiver par too much data ka load na ho.

🔹 TCP ka use kahan hota hai?

TCP ka use un applications mein hota hai jahan reliable communication important hai.

Examples:

🌐 HTTP/HTTPS → Web communication
📁 FTP → File transfer
📧 SMTP → Email sending
🔐 SSH → Secure remote communication
🔹 TCP vs UDP

