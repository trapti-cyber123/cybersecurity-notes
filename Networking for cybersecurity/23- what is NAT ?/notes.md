#  what is NAT ?
   NAT (Network Address Translation) 
   
   NAT stands for Network Address Translation. It is a technique used by a router/firewall to translate private IP addresses into a public IP address, and vice versa.

  [*]  NAT ek technique hai jisme private IP address ko public IP address mein translate kiya jata hai, taaki devices Internet se communicate kar saken.

🧠 Simple Formula:

  Private IP → NAT → Public IP → Internet

  🔹 Example

Maan lo ghar mein 3 devices hain:

  .Laptop → 192.168.1.10
  
  .Mobile → 192.168.1.11
  
  .PC → 192.168.1.12

Ye sab private IP addresses hain.

Router ke paas ek public IP hai, maan lo:

103.25.10.5

Jab laptop Internet par request bhejta hai:

Laptop: 192.168.1.10
⬇️
Router NAT: Private IP ko Public IP mein translate karta hai
⬇️
Internet: 103.25.10.5

Is tarah multiple devices ek public IP ko share karke Internet use kar sakte hain.

🔹 NAT ka main kaam

  1. Private IP ko Private IP mein translate karna.
     
  2. Public IP ko Private IP mein translate karna.
     
  3. Public IPv4 addresses save karna.
     
  4. Internal/private network ko Internet se directly expose hone se reduce karna.
     
🔹 NAT ke Types

1. Static NAT

One Private IP ↔ One Public IP

Example:
192.168.1.10 ↔ 103.25.10.5

Usually jab kisi internal server ko fixed public address dena ho.

2. Dynamic NAT

Private IPs ↔ Public IPs ka pool

Public IPs available pool mein se dynamically assign hote hain.

3. PAT (Port Address Translation)

Many Private IPs → One Public IP

Ye commonly home/office networks mein use hota hai.

Example:

192.168.1.10

192.168.1.11

192.168.1.12

⬇️

PAT/NAT Router

⬇️

103.25.10.5

PAT ports ka use karke multiple devices ko ek public IP share karne deta hai.

🧠 Yaad rakhne ki trick:

NAT = Private IP ko Public IP se “Translate” karna.
