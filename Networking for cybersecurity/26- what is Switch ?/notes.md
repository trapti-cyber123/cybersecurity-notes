# what is Switch ?

  A Switch is a networking device that connects multiple devices (computers, printers, servers, etc.) in a LAN (Local Area Network). It sends data only to the correct destination device.

[*] Switch ek networking device hai jo multiple devices jaise computer, printer, server ko LAN network mein connect karta hai. Ye data ko sirf usi device tak bhejta hai jiske liye data hai.

# Example
  # diagram
  <img width="1536" height="1024" alt="0455c42a-8feb-4d0b-b618-c89038756100" src="https://github.com/user-attachments/assets/9f4efd0c-f251-49db-b41b-7d5c4147a036" />


Maan lo ek office mein 3 computers hain:

        ┌─────────────┐
        
PC 1 ───┤             │

PC 2 ───┤   SWITCH    ├─── Printer

PC 3 ───┤             │

        └─────────────┘

Agar PC 1 → PC 3 ko data bhejta hai, to Switch data ko PC 3 tak forward karega, PC 2 ko nahi.

⚙️ Switch kaise kaam karta hai?

Switch MAC Address ka use karke decide karta hai ki data kis port/device par bhejna hai

Simple flow:

PC 1

  │
  
  │ Data
  
  ▼
  
┌─────────┐

│ SWITCH  │

└─────────┘
  │
  
  └──────────► PC 3
  
            (Destination)

. Switch = Connects devices + Uses MAC Address + Sends data to specific device
