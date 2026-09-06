# what is HUB ?

  A Hub is a networking device used to connect multiple computers/devices in a network. It works at the Physical Layer (Layer 1) of the OSI Model.

[*] Hub ek networking device hai jo multiple computers/devices ko ek network mein connect karta hai. Ye OSI Model ki Physical Layer (Layer 1) par kaam karta hai.

🔹 HUB kaise kaam karta hai?

Maan lo 4 computers Hub se connected hain:

        PC 1
          |
          |
       +------+
PC 2 --| HUB  |-- PC 3
       +------+
          |
          |
        PC 4

Agar PC 1 → PC 3 ko data bhejta hai, to Hub data ko sabhi ports par forward/broadcast karega:

PC 1 → HUB → PC 2 ❌
           → PC 3 ✅
           → PC 4 ❌

Isliye Hub ko "broadcast device" bhi kaha ja sakta hai.

🔹 Important Points

. Hub Layer 1 (Physical Layer) par work karta hai.

. Hub MAC address ko understand nahi karta.

. Data ko sabhi connected devices ko bhejta hai.

. Hub mein collision hone ki possibility zyada hoti hai.

. Hub, Switch se less efficient hota hai.
