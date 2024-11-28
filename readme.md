Values should be fairly obvious (330 for the lower resistors, 10k for the upper ones near the transistors, any NPN transistor should work - tested with 2N3904 and BC547C).
Needs 3 wires, GND, VCC and Switch (High = 7.0, Low = 3.5).
7-Segment display should be "common anode". Tested with LiteOn LTD-6710R.
Tested with Pentagon 1024SL 2.2, Compact 256 Turbo, Scorpion 256 Turbo+

Minor issue: CMOS (ACT in my case) get rather toasty due to unused inputs not being tied to GND/VCC, TTL families (LS/ALS) recommended.
