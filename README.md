# Sofle Keyboard Tutorial

[Original Github](https://github.com/josefadamcik/SofleKeyboard)
I got Sofle_v1.1 because I like the original layout more.

For reference: [Sofle Keyboard - build guide](https://josefadamcik.github.io/SofleKeyboard/build_guide.html)

Reference video: [Sofle V2 Build Guid](https://www.youtube.com/watch?v=_3pe236--hA)

## Parts
Below are my parts for reference:

| Component                                 | Qty  | Link                                                                                                          | Note                                                                                                  |
|-------------------------------------------|------|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| PCBs                                      | 2    | need to be fabricated, see github for gerber file                                                             |                                                                                                       |
| Top plates                                | 2    | need to be fabricated, see github for gerber file                                                             |                                                                                                       |
| RP2040 Pro Micro Development Board 16M    | 2    | https://www.aliexpress.com/item/1005009890367599.html?spm=a2g0o.order_list.order_list_main.110.467718022lLcKc |                                                                                                       |
| TRRS 3.5 MM Audio Jack Connector          | 2    | https://www.aliexpress.com/item/33029465106.html?spm=a2g0o.order_list.order_list_main.130.467718022lLcKc      |                                                                                                       |
| 0.91 Inch I2C SSD1306 OLED Display Module | 1    | https://www.aliexpress.com/item/1005006365845676.html?spm=a2g0o.order_list.order_list_main.155.467718022lLcKc |                                                                                                       |
| Rotary Encoder EC11                       | 2    | https://www.aliexpress.com/item/1005005983134515.html?spm=a2g0o.order_list.order_list_main.319.79891802CVSZHc |                                                                                                       |
| Tactile buttons                           | 2    | https://www.aliexpress.com/item/1005009739698023.html?spm=a2g0o.order_list.order_list_main.284.79891802CVSZHc |                                                                                                       |
| Led strip Connector                       | 52   | https://www.aliexpress.com/item/1005004194804142.html?spm=a2g0o.order_list.order_list_main.35.467718022lLcKc  | Optional for hot-swap microcontroller and LED display Just need 52 pins in total (e.g. 13x4pins)      |
| Pin header                                | 52   | https://www.aliexpress.com/item/1005007476809536.html?spm=a2g0o.order_list.order_list_main.4.79891802CVSZHc   | Optional for hot-swap microcontroller and LED display Just need at least 52 pins in total (e.g. 12x5) |
| Outemu Silent V3 Switch Lubed             | 58   | https://www.aliexpress.com/item/1005006905361113.html?spm=a2g0o.order_list.order_list_main.29.467718022lLcKc  |                                                                                                       |
| Kailh Hot-swappable Socket                | 58   | https://www.aliexpress.com/item/1005007232040760.html?spm=a2g0o.order_list.order_list_main.55.467718022lLcKc  |                                                                                                       |
| 1N4148W Diodes (T4 1N4148 IN4148 SOD-123) | 60   | https://www.aliexpress.com/item/1005007160279747.html?spm=a2g0o.order_list.order_list_main.49.467718022lLcKc  | Get few more just in case                                                                             |
| TRRS to TRRS keyboard                     | 1    | https://www.amazon.co.uk/dp/B0FLQGNTH3?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_1&th=1                      | Don't get TRS!                                                                                        |
| Rotary encoders EC11                      | 2    | https://www.aliexpress.com/item/1005005983134515.html?spm=a2g0o.order_list.order_list_main.319.79891802CVSZHc |                                                                                                       |
| M2 Standoff & Screws                      | 1    | https://www.aliexpress.com/item/1005012300971294.html?spm=a2g0o.order_list.order_list_main.15.467718022lLcKc  |                                                                                                       |
| M2 Screws 4mm                             | 30   | https://www.aliexpress.com/item/1005006674812661.html?spm=a2g0o.order_list.order_list_main.90.467718022lLcKc  |                                                                                                       |
| M2 Standoff 8mm                           | 4    | https://www.aliexpress.com/item/1005006060540257.html?spm=a2g0o.order_list.order_list_main.65.467718022lLcKc  |                                                                                                       |
| Keycap set                                | 1    | https://www.aliexpress.com/item/1005008642568026.html?spm=a2g0o.order_list.order_list_main.10.467718022lLcKc  |                                                                                                       |
| Rubber feet                               | 8-10 | https://www.aliexpress.com/item/1005006382486165.html?spm=a2g0o.order_list.order_list_main.414.79891802CVSZHc |                                                                                                       |
| USB cable                                 |      |                                                                                                               | To connect keyboard to computer                                                                       |

## Firmware
QMK firmware, [my config included](https://github.com/sjl-03/Sofle-keyboard-guide/tree/main/sofle_firmware_promicro_rp2040)

## Case
May still have some small issues, can modify them or just sand them down
