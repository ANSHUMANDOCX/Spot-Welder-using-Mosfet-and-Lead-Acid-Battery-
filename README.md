# Spot-Welder-using-Mosfet-and-Lead-Acid-Battery
## Plan
This board is designed for spot welding 18650 batteries with a 12v 7ah battery since these battery have a short circuit current of >300A so it can be used to spot weld nickel strips by delivering shot pulses of high current.
## Why i made this 
here in india good spot welders are very expensive and designing it myself allowed me to learn about gates and high current applications.
## How to use 
Its pretty simple to use we just need to connect the battery to the board using some high guage wires around 12-10AWG and connect them to 12AWG single core copper wire for putting the welding spots.
Also the timing of the circuit can be adjusted by changing the C11.
## Parts Requried 
- 12v 7Ah Lead acid battery
- IRLB4132 Mosfet
- NE555 timer IC 

## PCB and Schematic
<img width="1280" height="894" alt="Screenshot 2026-01-23 202702" src="https://github.com/user-attachments/assets/1c6112cd-b687-4d26-bb15-f9a18fc48589" />
<img width="1090" height="662" alt="Screenshot 2026-01-24 132355" src="https://github.com/user-attachments/assets/f71a1557-7d0a-483d-96aa-3e1e66a323ee" />
<img width="614" height="388" alt="Screenshot 2026-01-24 161041" src="https://github.com/user-attachments/assets/471aac6a-f142-47e4-99b3-16317ff1b462" />

# BOM 


| Name                                      | Qty | Vendor | Price ($) | Links |
|-------------------------------------------|-----|--------|-----------|-------|
| ALL BOM parts mosfet, resistor, capacitors etc |     | LCSC   | 14        |       |
| Wires 12awg and 12 awg solid core         | 1   | Robu   | 5         | [Link 1](https://robu.in/product/sps-61t-250-jst-quick-terminal-rohs/)<br>[Link 2](https://robu.in/product/12awg-solid-core-insulated-wire-silicone-black/)<br>[Link 3](https://robu.in/product/high-quality-ultra-flexible-12awg-silicone-wire-black/)<br>[Link 4](https://robu.in/product/high-quality-ultra-flexible-12awg-silicone-wire-red/) |
| Lead acid Battery AMARON 12v 7ah          | 1   | Amazon | 15        |https://www.amazon.in/Amaron-Quanta-12-AL-007/dp/B01D1JQO3I?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A20KWYYO0T79V8       |
| PCB                                       |     | JLCPCB | 5         |       |
| **Total**                                 |     |        | **40**    |       |
