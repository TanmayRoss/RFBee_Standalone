# RFBee_Standalone
Modified Existing RFBee Firmware to implement a static Time Division Multiple Access Protocol

You can find the original firmware at https://github.com/Seeed-Studio/RFBee

In my firmware, I eliminated the need of any external hardware to send and receive data.
Features:
1. Works as a Standalone Arduino. Can use to read sensor values, access RFBee GPIOs etc.
2. 2-Way Communication Enabled. 
3. Static TDMA Enabled. 1 RFBee Receiver broadcasts "Hello" packet identifier and after receiving, the sender RFBee replies as programmed.
4. Can send data at a highfast interval of upto 250ms [Tested for Many-to-One with Buffer Overflow error;Working on it One-to-One at no error].

