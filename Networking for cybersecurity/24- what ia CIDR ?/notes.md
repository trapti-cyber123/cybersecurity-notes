#  what is CIDR ? 
   CIDR = Classless Inter-Domain Routing

   CIDR is a method of allocating IP addresses and routing networks using a prefix length, instead of traditional Class A, B, C system.

[*] CIDR ek technique hai jisme IP addresses ko Class A, B, C ke fixed rules ke bina, requirement ke according network mein divide kiya jata hai.


CIDR ka format

CIDR mein IP address ke baad /number likha hota hai.

Example:

192.168.1.0/24

Example:

192.168.1.0/24

Yahan:

. 192.168.1.0 = Network IP

. /24 = 24 bits network portion ke liye

. Remaining 8 bits host ke liye

IPv4 mein total 32 bits hote hain.

32 − 24 = 8 host bits

Isliye:

2⁸ = 256 total addresses


/24 ko samjho

Subnet mask:

255.255.255.0

Binary:

11111111.11111111.11111111.00000000

24 ones → Network bits
8 zeros → Host bits

Example:

192.168.1.0/24

Range:

192.168.1.0 → Network Address
192.168.1.1 → First usable IP
192.168.1.254 → Last usable IP
192.168.1.255 → Broadcast Address

Usable hosts = 256 − 2 = 254

CIDR ka main benefit

Traditional class system mein network sizes fixed hote the:

Class A → very large
Class B → medium
Class C → small

CIDR mein requirement ke according size choose kar sakte hain.

For example:

192.168.1.0/24 → 256 addresses

192.168.1.0/25 → 128 addresses

192.168.1.0/26 → 64 addresses

192.168.1.0/27 → 32 addresses

Jaise / number increase hota hai, host addresses decrease hote hain.

Easy trick 🧠

/24 → 8 host bits → 256 addresses

/25 → 7 host bits → 128 addresses

/26 → 6 host bits → 64 addresses

/27 → 5 host bits → 32 addresses

Formula:

Total IP addresses = 2^(32 − CIDR prefix)

Usable hosts = Total addresses − 2

(general IPv4 subnetting mein)
