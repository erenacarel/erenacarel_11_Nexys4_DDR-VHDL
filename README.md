# erenacarel_11_Nexys4_DDR-VHDL
Vivado VHDL over Nexys4-DDR - Uart Receiver, Pwm Rgb Colour, 7 segment, and VGA monitoring display

TR: Bizim projemizde R, G, B renklerini hex olarak hercules adlı terminalden yolladık. 
Yollanan hex formatların binary karşılığını switch’lerin üzerindeki ledlerde gösterdik. 
Gelen renge göre pwm destekli 2 ledde blink oluşmasını sağladık. Terminalden yollanan 
renkeri de VGA protokolünü kullanarak ekrana yansıttık. Süreçlerden bağımsız olarak 
kronometre de çalışmaktadır. Ayrıca iki tane butonla da kronometre kontrol 
edilebilmektedir. Aşağıdaki görseller uart(3. görsel) ve pwm’de (ilk 2 görsel) gerçekleşen 
simülasyonları göstermektedir.  

ENG: In our project, we sent the R, G, B colors as hex from the terminal called Hercules. 
We displayed the binary equivalent of the sent hex formats on the LEDs on the switches. 
We enabled 2 PWM-supported LEDs to blink according to the incoming color. We also reflected 
the colors sent from the terminal to the screen using the VGA protocol. The stopwatch also works 
independently of the processes. Additionally, the stopwatch can be controlled with two buttons. 
The images below show the simulations taking place in uart (3rd image) and pwm (first 2 images).


LINK: https://youtu.be/aZkpZetGZP8
