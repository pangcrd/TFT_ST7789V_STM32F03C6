# TFT ST7789V 2.4" 240x320
- I'm using STM32 BluePill (STM32F103C6T6)
- ST7789V libary: https://github.com/deirvlon/ST7789v-Arduino
- Above libary work ok with TFT 240x240 square or round screen. ( tft.int(240x320) may be not work correctly). So i make some change in libary to work with 240x320 screen.  
---
# Wring on STM32F03C6 i'm ussing SPI1

TFT_CS   PA4 // some board RS 

TFT_RST  PB12  

TFT_DC   PA3 // Data command  

TFT_MOSI PA7  // Data out maybe SDI  

TFT_SCLK PA5  // Clock out maybe SCK  

***
# Final test
___
<table>
  <tr>
    <td><img src="https://github.com/pangcrd/TFT_ST7789V_STM32F03C6/blob/main/image/photo_2024-09-25_15-34-14.jpg" alt="Image 1" width="200"/></td>
    <td><img src="https://github.com/pangcrd/TFT_ST7789V_STM32F03C6/blob/main/image/photo_2024-09-25_15-34-17.jpg" alt="Image 2" width="200"/></td>
  </tr>
</table>
