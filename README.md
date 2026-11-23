# Orion-RP2350 (1)
Custom microcontroller board


<img width="2000" height="2000" alt="ORION" src="https://github.com/user-attachments/assets/eceb433e-61c8-4fb5-85f8-bb986c6e3b4e" />



Made by Mustafa Berisha.


The orion(1) is powered by the raspberry pi chip rp2350, its a great MCU with its
duel Processor able to hit 150mhz, 520kb SRAM, and 16MBS of storage!


# pictures
<img width="591" height="651" alt="PCB FRONT" src="https://github.com/user-attachments/assets/3a05eac0-2ffc-4e17-8498-81a3666f13b4" />

<img width="327" height="498" alt="PCB BACK" src="https://github.com/user-attachments/assets/efe25f61-36a7-4d7a-a71a-7ee8d914f756" />

<img width="4049" height="2860" alt="Schematic_Orion-RP2350-(phantom)_2026-09-25" src="https://github.com/user-attachments/assets/1bef8b7a-a771-4d73-b803-4fc91bd7c17d" />

# How to build this 

1. fabricate the pcb any way(online pcb fabs or you might have your own cnc).
2. buy modules/chips/semiconductors
3. solder everything
4. make custom software or download it somewhere
6.send the data thru on the chip via the usb C finish!

# Firmware:
You are able to download the official Raspberry pi Firmware on it via the USB 





# Example firmware:

```
void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  
  delay(1000);                      
  digitalWrite(LED_BUILTIN, LOW);   
  delay(1000);                      
}
```
# BOM

| Item | Quantity | Unit Price (USD) | Total (USD) | Link |
| :--- | :---: | :---: | :---: | :--- |
| 100nF | 1 | $0.021 | $0.021 | [LCSC (C56476)](https://www.lcsc.com/product-detail/C56476.html?s_z=n_q_t_100nF%2520TDK) |
| 100nF | 12 | $0.003 | $0.036 | [LCSC (C14663)](https://www.lcsc.com/product-detail/C14663.html) |
| 4.7uF | 2 | $0.052 | $0.104 | [LCSC (C167656)](https://www.lcsc.com/product-detail/C167656.html) |
| 06033C104JAZ2A | 1 | $0.010 | $0.010 | [Mouser](https://www.mouser.com/ProductDetail/KYOCERA-AVX/06033C104JAZ2A?qs=ZBeOGGPQgEF3HuLfD2k6PQ%3D%3D) |
| 15pF | 1 | $0.089 | $0.089 | [LCSC (C106997)](https://www.lcsc.com/product-detail/C106997.html) |
| 10103594-0001LF | 1 | $0.429 | $0.429 | [DigiKey](https://www.digikey.com/en/products/detail/amphenol-cs-fci/10103594-0001LF/2350351) |
| 3.3uH | 1 | $0.242 | $0.242 | [LCSC (C285742)](https://www.lcsc.com/product-detail/C285742.html) |
| 0Ω | 1 | $0.001 | $0.001 | [LCSC (C881153)](https://www.lcsc.com/product-detail/C881153.html) |
| 1kΩ | 1 | $0.001 | $0.001 | [LCSC (C106235)](https://www.lcsc.com/product-detail/C106235.html) |
| 27Ω | 2 | $0.005 | $0.010 | [LCSC (C25100)](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Uniroyal-Elec-0402WGF270JTCE_C25100.html) |
| 1kΩ | 1 | $0.034 | $0.034 | [LCSC (C11702)](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0402WGF1001TCE_C11702.html) |
| 1Ω | 1 | $0.007 | $0.007 | [LCSC (C185446)](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_1R-1R00-1_C185446.html) |
| 434133025816 | 2 | $0.350 | $0.700 | [LCSC (C914216)](https://www.lcsc.com/product-detail/C914216.html) |
| RP2350A | 1 | $4.800 | $4.800 | [LCSC (C969152)](https://www.lcsc.com/product-detail/C969152.html) |
| FTS-105-01-L-D-P | 4 | $1.200 | $4.800 | [Mouser](https://www.mouser.fr/ProductDetail/Samtec/FTS-105-01-L-D-P?qs=Cqqh%252BS766wmXh%2FxfxY38TA%3D%3D) |
| W25Q128JVSIQ | 1 | $2.706 | $2.706 | [LCSC (C97769)](https://www.lcsc.com/product-detail/C97769.html) |
| NCP1117ST33T3G | 1 | $0.205 | $0.205 | [LCSC (C182397)](https://www.lcsc.com/product-detail/C182397.html) |
| 10uF | 2 | $0.089 | $0.178 | [LCSC (C163694)](https://www.lcsc.com/product-detail/C163694.html) |
| P70-2200045 | 3 | $1.713 | $5.139 | [Mouser](https://www.mouser.com/en/ProductDetail/Harwin/P70-2200045?qs=k41KVqW3ymoBGVx637VSuQ%3D%3D) |
| ABM8-272-T3 | 1 | $0.650 | $0.650 | [LCSC (C121731)](https://www.lcsc.com/product-detail/C121731.html) |
| **Total** | | | **$20.16** | |

