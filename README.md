# 433MHzGPSTracker System
Most of the commercial GPS trackers require a SIM card. 
The system here described consists of two components:
- Sender
  This is a small device that collect GPS information and sends it as ASK moduled on 433 MHz.
  It also has a WiFi access point, so that when in reachable distance can be directly interrogated through embedded WebUI.

(Sender)[hardware/sender.png]


- Receiver
  As well a small device that receive the message from the sender and provides the same UI as embedded in the sender.
(Sender)[hardware/receiver.png]
