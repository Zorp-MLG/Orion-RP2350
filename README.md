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
