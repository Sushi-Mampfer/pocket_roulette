# Pocket roulette
A small roulette/dice/rng.
<img width="1200" height="400" alt="banner" src="https://github.com/user-attachments/assets/692689c9-fc3a-41e5-9a7d-2ace0a327a40" />

It consists of a 555 that ticks very fast and triggers a 4017 which then triggers the leds one after another, once you let go of the button the 555 stops and the leds stop at wherever they're now. You might be able to time it to land in an area, but I'd be surprised if it was possible to consistently land on the same spot.

# PCB
<img width="860" height="852" alt="image" src="https://github.com/user-attachments/assets/f24a3dd7-2713-4ba4-90e7-c8a02736f210" />


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
