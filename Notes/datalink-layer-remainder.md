# Data Link Layer Remainder
## Elementary Data Link Protocol
- Independent Processes
- **exchanging** messages
- network interface card connects physical and operating system
- all our devices has cards and also motherboard they are embedded as chips
- computer card allows hardware to function
- **Basic Transmission and Receipt**
## Utopia
- no error correction or flow control
> **unimaginable**
## Flow Control
- **Stop-and-wait**
## Error Correction
- **Sequence Numbers and ARQ**
## Bidirectional Transmission
- **Piggybacking**
## Sliding Window Protocols
1. One-Bit Sliding Window
exactly like the stop and wait but when error occurs it will resend all the errors which may stop the system from working since the receiver wont be able to handle all frames that will be resent.
2. Go-Back-N
if it notices that a certain frame was not acknowledged, it will *go back* to that frame and start from there again
3. Selective Repeat
if it notices that a frame was negatively acknowledged, it will resend that frame only and still continue the current sequence.