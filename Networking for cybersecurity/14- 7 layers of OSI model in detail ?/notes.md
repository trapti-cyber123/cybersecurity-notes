#  7layers of OSI model in detail ?
   🌐 Application Layer — Layer 7

Application Layer OSI Model ki 7th aur sabse upper layer hai 

The Application Layer is the topmost layer of the OSI model. It provides network services directly to applications and users.
   It allows applications like web browsers, email clients, and file-transfer programs to communicate over a network.

[*] Application Layer OSI Model ki sabse upar wali layer hai. Ye user ke applications ko network services provide karti hai.
    Jaise jab hum browser se website open karte hain, email bhejte hain ya FTP se file transfer karte hain, to Application Layer se related protocols ka use
    hota hai.

📌 Main Functions
1.Network services provide karna
   User applications ko network se connect karna.
2.Web browsing
  HTTP/HTTPS ke through websites access karna.
3.Email communication
  SMTP jaise protocols email communication mein use hote hain.
4.File transfer
   FTP jaise protocols files transfer karne mein help karte hain.
5.Name/Address services
  DNS domain name ko IP address mein resolve karta hai.

🔑 Important Protocols
Protocol     	Use
HTTP       	Web pages
HTTPS      	Secure web communication
FTP       	File transfer
SMTP       	Email sending
DNS       	Domain name → IP address
DHCP      	Automatically IP configuration

💡 Simple Example

  Aap browser mein type karte ho:
  www.google.com
   Browser ko website access karne ke liye HTTP/HTTPS jaise Application Layer protocols use hote hain


🌐 Presentation Layer — Layer 6

Presentation Layer OSI Model ki 6th layer hai.
Iska main kaam data ko ek suitable format mein convert, encrypt/decrypt aur compress/decompress karna hai.

 The Presentation Layer is the 6th layer of the OSI model. It is responsible for data translation, encryption/decryption, and compression/decompression.

[*] Presentation Layer sender ke data ko aise format mein convert karti hai jise receiver ka system samajh sake. Ye data ki formatting, encryption aur compression bhi handle karti hai.

📌 Main Functions

1. Translation / Data Formatting
Different systems ke data formats ko convert karti hai.

👉 Example: Character encoding jaise ASCII/Unicode.

 2. Encryption & Decryption 🔐
Data ko secure karne ke liye encryption aur receiver side par decryption ki process hoti hai.

👉 Example: Sensitive information ko readable form se encrypted form mein convert karna.

3. Compression & Decompression 📦
Data ka size reduce karti hai taaki data efficiently transfer ho sake.
 💡 Easy Example

Maan lo aap kisi ko ek image bhejte ho:

Sender:
Image → Format/Encode → Compress → Encrypt → Network

Receiver:
Network → Decrypt → Decompress → Decode → Image


🌐 Session Layer — Layer 5

Session Layer OSI Model ki 5th layer hai.
Iska main kaam do devices/applications ke beech communication session ko establish, manage aur terminate karna hai.

The Session Layer is the 5th layer of the OSI model. It establishes, manages, synchronizes, and terminates communication sessions between two devices 
or applications.

[*]Session Layer do devices ya applications ke beech communication ka session start, maintain aur end karti hai.

📌 Main Functions

1. Session Establishment
Communication session ko start karti hai.

👉 Example: Do applications ke beech communication start hona.

2. Session Management
Communication ko maintain aur control karti hai.

👉 Matlab session ke dauran communication ko properly manage karna.

3. Session Termination
Communication complete hone par session ko close/end karti hai.

4. Synchronization
Long data transfer mein checkpoints maintain karne mein help karti hai.

👉 Agar transfer ke beech problem aa jaye, to communication ko suitable checkpoint se continue karna possible ho sakta hai.


🌐 Transport Layer — Layer 4

Transport Layer OSI Model ki 4th layer hai.
Iska main kaam sender se receiver tak data ki end-to-end delivery karna hai.

The Transport Layer is the 4th layer of the OSI model. It provides end-to-end communication, data delivery, flow control, and error control between 
applications running on different devices.

[*] Transport Layer sender ke computer se receiver ke computer tak data ko properly deliver karne mein help karti hai. Ye data ko chhote parts mein divide
karti hai aur communication ko manage karti hai.

📌 Main Functions

1. Segmentation 📦
Large data ko chhote-chhote parts mein divide karti hai.

Example:

Large Data → Segment 1 + Segment 2 + Segment 3

Receiver side par ye segments dobara arrange kiye ja sakte hain.

2. End-to-End Delivery 🔄
Data ko source application se destination application tak pahunchane mein help karti hai.

3. Error Control ❌
Data delivery mein errors ya missing data ko detect/handle karne mein help karti hai, especially TCP mein.

4. Flow Control ⚖️
Sender ki speed ko receiver ki capacity ke according manage karne mein help karti hai.

👉 Agar sender bahut fast data bhej raha hai, to receiver overload na ho, isliye flow control important hai.

5. Port Numbers 🔢
Transport Layer port numbers ka use karke identify karti hai ki data kis application/service ke liye hai.

Examples:

FTP → Port 21
SSH → Port 22
HTTP → Port 80
HTTPS → Port 443

🔥 Important Protocols
TCP — Transmission Control Protocol

TCP reliable hai.

Connection-oriented
Acknowledgment use karta hai
Lost data ko retransmit kar sakta hai
Reliable delivery

👉 Example: Important data transfer.

UDP — User Datagram Protocol

UDP fast hai, lekin TCP ki tarah delivery guarantee nahi deta.

Connectionless
Faster
Low overhead
No delivery guarantee

👉 Example: Live streaming, online gaming, DNS queries etc.


🌐 Network Layer — Layer 3

Network Layer OSI Model ki 3rd layer hai.
Iska main kaam IP addressing aur routing hai.

The Network Layer is the 3rd layer of the OSI model. It is responsible for logical addressing (IP addresses) and routing packets from the source to the destination.

[*]  Network Layer OSI Model ki 3rd layer hai. Ye data ko destination tak pahunchane ke liye IP address aur best route/path ka use karti hai.

📌 Main Functions

1. IP Addressing 📍

Network Layer devices ko IP address ke through identify karti hai.

Example:

192.168.1.10

Yahan 192.168.1.10 ek IPv4 address hai.

2. Routing 🛣️

Routing ka matlab hai source se destination tak data ke liye suitable path select karna.

Example:

Computer A → Router → Router → Computer B

Router decide karta hai ki packet ko kis direction mein bhejna hai.

3. Packet Forwarding 📦

Network Layer mein data ko packets ke form mein handle kiya jata hai aur routers un packets ko next destination ki taraf forward karte hain.

4. Logical Addressing

MAC address ke alawa Network Layer logical address, mainly IP address, ka use karti hai.

👉 IP = Logical Address
👉 MAC = Physical/Data-Link Address

💡 Simple Example

Aapke computer ka IP:

192.168.1.10

Aur website/server ka IP:

142.x.x.x

Jab aap website open karte ho:

Your Computer → Router → Internet → Destination Server


🌐 Data Link Layer — Layer 2

Data Link Layer OSI Model ki 2nd layer hai.
Iska main kaam directly connected devices ke beech data ko frames ke form mein reliably transfer karna hai.

The Data Link Layer is the 2nd layer of the OSI model. It provides node-to-node delivery, uses MAC addresses, and organizes data into frames.

[*]  Data Link Layer OSI Model ki 2nd layer hai. Ye ek network mein directly connected devices ke beech data transfer karne mein help karti hai. Is layer par data ko Frame kaha jata hai aur MAC Address ka use hota hai.

📌 Main Functions

1. Framing 📦

Network Layer se aaye packet ko Data Link Layer Frame mein convert karti hai.

Packet → Frame

Receiver side par frame se data ko aage process kiya jata hai.

2. MAC Address 🔢

Data Link Layer MAC address ka use karti hai.

Example:

00:1A:2B:3C:4D:5E

👉 MAC Address = Hardware/Physical address

3. Error Detection ❌

Data transfer ke dauran error detect karne mein help karti hai.

👉 Example: CRC (Cyclic Redundancy Check)

4. Node-to-Node Delivery 🔄

Ye ek device/node se next directly connected node tak data delivery provide karti hai.

5. Access Control

Agar multiple devices ek hi communication medium use kar rahe hain, to ye decide karne mein help karti hai
ki medium ko kab access karna hai.

🏗️ Data Link Layer ke 2 Sub-layers

Data Link Layer ko generally do parts mein divide kiya jata hai:

1. LLC — Logical Link Control
Communication aur error/flow-related control functions provide karta hai.

2. MAC — Media Access Control
MAC addressing aur shared medium access se related functions handle karta hai.

💡 Simple Example

Maan lo:

PC A → Switch → PC B

PC A data bhejta hai:

Data → Packet → Frame

Frame mein source aur destination MAC addresses hoti hain.

Switch → Destination MAC ko check karta hai → Frame ko PC B ki taraf forward karta hai.


🌐 Physical Layer — Layer 1

Physical Layer OSI Model ki 1st aur sabse neeche wali layer hai.

The Physical Layer is the 1st layer of the OSI model. It is responsible for transmitting raw bits (0s and 1s) through a physical medium such as cables, fiber, or wireless signals.

[*]  Physical Layer OSI Model ki 1st aur lowest layer hai. Ye data ko 0 aur 1 (bits) ke form mein physical medium ke through transmit karti hai.

📌 Main Functions

1. Transmission of Bits 🔢

Data ko 0s and 1s ke form mein transmit karti hai.

Example:

10110101

Ye bits electrical, optical ya wireless signals mein represent ho sakti hain.

2. Physical Media 🖧

Ye decide/define karti hai ki data kis physical medium se travel karega.

Examples:

🔌 Ethernet cable
💡 Fiber optic cable
📡 Wireless/RF signals

3. Data Rate ⚡

Data kitni speed se transmit hoga, jaise Mbps ya Gbps, physical transmission se related hota hai.

4. Signals 📶

Bits ko appropriate electrical, optical ya radio signals ke form mein transmit kiya jata hai.

5. Physical Devices

Physical Layer se commonly associated devices:

Hub
Repeater
Cables
Connectors
Antennas

💡 Simple Example

Aap computer se doosre computer ko data bhejte ho:

Data → Packet → Frame → Bits

Physical Layer mein:

Bits (0 & 1) → Signals → Cable/Wireless → Receiver

Receiver side par signals ko dobara bits mein interpret kiya jata 














