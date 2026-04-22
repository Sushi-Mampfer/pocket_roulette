# Pocket roulette
A small roulette/dice/rng.
<img width="1200" height="400" alt="banner" src="https://github.com/user-attachments/assets/53ceac9a-68c8-47a6-a97c-01f69d2ac51f" />

It consists of a 555 that ticks very fast and triggers a 4017 which then triggers the leds one after another, once you let go of the button the 555 stops and the leds stop at wherever they're now. You might be able to time it to land in an area, but I'd be surprised if it was possible to consistently land on the same spot.

# PCB
<img width="801" height="799" alt="image" src="https://github.com/user-attachments/assets/04e85151-5191-42dc-874f-755c43266481" />

# Schematic
<img width="1003" height="501" alt="image" src="https://github.com/user-attachments/assets/12ed4ffe-088d-4827-8c74-9c6053772f2f" />


# Bom
| Reference | Qty | Value |
|----------|-----|-------|
| C2 | 1 | 10u |
| D1-D10 | 10 | LED |
| J1 | 1 | USB_A |
| R1 | 1 | 477 |
| R2 | 1 | 1k |
| R3,R4 | 2 | 500 |
| R5 | 1 | 10k |
| SW1 | 1 | SW_Push |
| U1 | 1 | NE555P |
| U2 | 1 | 4017 |
