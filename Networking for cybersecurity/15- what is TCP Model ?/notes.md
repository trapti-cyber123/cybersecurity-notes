#  what is TCP/IP model ?
   TCP/IP Model is a network communication model that explains how data is transmitted from one computer to another over a network or the Internet.

  [*]   TCP/IP Model ek network communication model hai jo batata hai ki computer network mein data ek device se doosre device tak kaise travel karta hai.

  TCP = Transmission Control Protocol
  IP = Internet Protocol

  TCP/IP Model mein generally 4 layers hoti hain:


   Layer                 	Main kaam                     	      Examples
4️⃣ Application    	User ki network services	            HTTP, FTP, DNS, SMTP
3️⃣ Transport     	Reliable data delivery	                TCP, UDP
2️⃣ Internet	      IP addressing & routing               	IP, ICMP
1️⃣ Network        Access	Actual data transmission	      Ethernet, Wi-Fi



1️⃣ Application Layer
     Ye user ke sabse close hoti hai.
   Kaam: Network applications ko services provide karna.
  Examples:
      . HTTP/HTTPS → Websites
      . FTP → File transfer
      . DNS → Domain name ko IP mein convert karna
      .  SMTP → Email

👉 Example: Tum browser mein google.com open karti ho.


2️⃣ Transport Layer
    Ye decide karti hai ki data properly aur kis process/application tak pahunchana hai.

Main protocols:
      TCP → Reliable delivery
      UDP → Fast but less reliable

TCP ke important kaam:

.Data ko segments mein divide karna
.Error checking
.Flow control
.Reliable delivery
.Port numbers ka use

👉 Example: Port 80 = HTTP, Port 443 = HTTPS.



3️⃣ Internet Layer
      Iska main kaam hai IP addressing aur routing.

Protocols:

.IP
.ICMP
.ARP (often associated with network access/link functions depending on the TCP/IP version)

👉 Router isi level par IP address dekhkar packet ko next network ki taraf forward karta hai.

Example:
     192.168.1.10 → 8.8.8.8



   4️⃣ Network Access Layer
         Ye data ko actual network medium par transmit karne ka kaam karti hai.

Examples:

.Ethernet
.Wi-Fi
.MAC Address
.Network cables

👉 Yaani data cable ya wireless signal ke through travel karta hai.


🔄 Easy Example
    Agar tum browser mein website open karti ho:

.Application → Website request banati hai
   ⬇️
.Transport → TCP data ko reliably deliver karta hai
   ⬇️
.Internet → IP address ke basis par route choose hota hai
  ⬇️
.Network Access → Data Wi-Fi/Ethernet se transmit hota hai
