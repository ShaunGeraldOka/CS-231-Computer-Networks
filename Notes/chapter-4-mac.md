# Chapter 4 MAC Sublayer
- **MAC** or medium access control
    - sublayer of data link layer
    - has protocols that determine who goes next in a multiaccess channel

## 4.1 Channel Allocation Problem
- use single channel 
    - for all users to connect with each other
    - but a user who wants to use the channel can interfere with other users
- static allocation
- dynamic allocation

## 4.2 Multiple Access Protocols
- algorithms for allocation

### Collision prone  protocols
1. ALOHA
- Pure ALOHA
    - collisions are frequent because transmission is anytime user want
- Slotted ALOHA
    - time slot exists so not all the time a user can send only when a time slot has started
2. CSMA
- **persistence in listening and sending after**

### Collision-Free protocols
1. Bit Map Protocol
2. Token Passing
3. Binary Countdown

### Wireless LAN Protocols

- MACA
    - rts
    - cts

# END OF MODULE 4
# EXTRA INFO
## 4.3 ETHERNET
- IEEE 802.3
- real system using channel allocation
- classic Ethernet
    - uses principles in chapter 4.2
    - 3 to 10 Mbps
    - very old
- switched Ethernet
    - uses switches to connect computers
    - what we use today
    - 100, 1 000, 10 000, 40 000, 100 000 Mbps
        - fast, gigabit, 10-gigabit, 40-gigabit, 100-gigabit Ethernet 