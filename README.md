# Beerbox

## BOM
| Component | Amount | Price (kr) |
| --- | --- | --- |
| [Heat sink ](https://www.amazon.se/Aluminiumchipset-kylfl%C3%A4ns-silver-komponent-kalolary/dp/B07FXP35FW/ref=sr_1_12?crid=1P99J35CH5JA1&keywords=kylfl%C3%A4ns%2B40x40&qid=1659534734&sprefix=kylfl%C3%A4ns%2B40x4%2Caps%2C160&sr=8-12&th=1) | 2 | 100 |
| [Cooling element - Peltier](https://www.amazon.se/ZHITING-TEC1-12706-kylfl%C3%A4ns-halvledarkylare-termoelektrisk/dp/B08GM1YTQW/ref=asc_df_B08GM1YTQW/?tag=shpngadsglede-21&linkCode=df0&hvadid=476526388315&hvpos=&hvnetw=g&hvrand=2625410695669262005&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1012442&hvtargid=pla-1353381197748&psc=1) | 2 | 100 |
| [Heat element - PTC](https://www.amazon.se/PTC-v%C3%A4rmeelement-termostatisk-aluminiumskal-v%C3%A4rmeplatta-temperaturv%C3%A4rmare/dp/B07Y5DY1HJ/ref=sr_1_54?crid=16O7R4Q5AJGNL&keywords=v%C3%A4rmeelement&qid=1659605875&refinements=p_85%3A20692917031&rnid=20692916031&rps=1&sprefix=v%C3%A4reme%2Belement%2Caps%2C76&sr=8-54&th=1) | 1 | 81 |
| [Fan](https://www.electrokit.com/produkt/flakt-70x70x15mm-12v-180ma-3200rpm/) | 2 | 52 |
| [Foam](https://www.byggmax.se/cellplast-s80-eps?gclid=Cj0KCQjwuaiXBhCCARIsAKZLt3lo6dcp9Jl1qeO5kbia00nlGY3HbbSIcILkOVgeIny8gzmbRetWZC8aAtbSEALw_wcB#1257=54622) | 1 | 23 |
| [Heat paste](https://www.amazon.se/Cooler-Master-IC-Essential-v%C3%A4rmeledningsf%C3%B6rm%C3%A5ga-RG-ICE1-TG15-R1/dp/B007W82ABK/ref=sr_1_37?crid=26UG2HU9LBOJI&keywords=heat+paste&qid=1659603660&refinements=p_85%3A20692917031&rnid=20692916031&rps=1&sprefix=heat+past%2Caps%2C93&sr=8-37) | 1 | 49 |
| [Power supply 12V 10A](https://www.amazon.se/V-TAC-VT-20122-120W-smal-str%C3%B6mf%C3%B6rs%C3%B6rjning/dp/B077SQBYZ9/ref=asc_df_B077SQBYZ9/?tag=shpngadsglede-21&linkCode=df0&hvadid=476583498437&hvpos=&hvnetw=g&hvrand=11417481118606867287&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9062391&hvtargid=pla-469124206940&psc=1) | 1 | 78 |

### Control box
| Component | Amount | Price (kr) |
| --- | --- | --- |
| [OLED 0.96](https://www.amazon.se/cart/smart-wagonnewItems=Ca592deca-49b4-446e-a125-338a08f7d3bb,1) | 1 | 69 |
| [Rotary encoder](https://www.amazon.se/gp/product/B07D356LRH/ref=ox_sc_act_title_2?smid=A3NVULWWT1VZI8&psc=1) | 1 | 25kr |
| IRLZ44N N-mosfet | 3 | - |
| LEDS | 2 | - |
| [Power terminal](https://www.amazon.se/YIXISI-Universal-Terminal-Connector-Arduino/dp/B087RN8FDZ/ref=sr_1_4?keywords=nylon+pcb+terminal+block&qid=1659605293&refinements=p_85%3A20692917031&rnid=20692916031&rps=1&sr=8-4) | 1 | 116 (for 100 pcs) |

## Power
| Component | Voltage (V) | Current (A) | Power (Watts) |
| --- | --- | --- | --- |
| Fan * 2| 12 | 0.18 | 2.16 * 2 = 4.32 |
| Cooling elemennt - Peltier | 12 | 6 | 60*2 = 120 |
| Heating elemennt - PTC | 12 | 0.83 | 10 |
| ESP32, OLED & LEDS | 3.3 | 0.5 | 1.65 |
| Total | | | ~136 |


## Datasheets
- [Rotary encoder](https://www.epitran.it/ebayDrive/datasheet/25.pdf)

## Blog
- 04-08-2022, Ordered parts from amazon. Started design on PCB
- 05-08-2022, Ordered PCB from jlcpcb.