# Pocket roulette

A small roulette/dice/rng.

<img width="1065" height="1015" alt="image" src="https://github.com/user-attachments/assets/67486038-85d0-4aac-84cf-73c283689d58" />

It consists of a 555 that ticks very fast and triggers a 4017 which then triggers the leds one after another, once you let go of the button the 555 stops and the leds stop at wherever they're now. You might be able to time it to land in an area, but I'd be surprised if it was possible to consistently land on the same spot.

# PCB
<img width="519" height="510" alt="image" src="https://github.com/user-attachments/assets/083c03ee-0ff1-452f-94f2-5645646e146b" />

# Schematic
<img width="1586" height="784" alt="image" src="https://github.com/user-attachments/assets/40a4a1d1-ab53-4e84-8582-ccda4c34a59b" />

# Bom
| Reference | Qty | Value |
|----------|-----|-------|
| C2 | 1 | 10u |
| D1-D10 | 10 | LED |
| J1 | 1 | USB_A |
| R1 | 1 | 477 |
| R2 | 1 | 1k |
| R3-R12 | 10 | 500 |
| R13,R14 | 2 | 10k |
| SW1 | 1 | SW_Push |
| U1 | 1 | NE555P |
| U2 | 1 | 4017 |
