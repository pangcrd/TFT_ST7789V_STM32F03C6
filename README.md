# TFT ST7789V 2.4" 240x320
- I'm using STM32 BluePill (STM32F103C6T6)
- ST7789V library: https://github.com/deirvlon/ST7789v-Arduino
- Above library work ok with TFT LCD 240x240 square and round screen or 2.0" TFT LCD 240x320. But for 2.4" LCD may be not work correctly with res 240x320. So i make some change in library" ST7789v-Arduino" to work with 2.4"screen.  
---
# Wring on STM32F03C6 i'm using SPI1

TFT_CS   PA4 // some board RS 

TFT_RST  PB12  

TFT_DC   PA3 // Data command  

TFT_MOSI PA7  // Data out maybe SDI  

TFT_SCLK PA5  // Clock out maybe SCK  

***

# Issue with 2.4" LCD TFT

<table>
  <tr>
    <td><img src="https://ik.imagekit.io/chipucu/photo_2024-09-25_14-07-59.jpg" alt="Image 1" width="500"/></td>
  </tr>
</table>
___

# Final test
___
<table>
  <tr>
    <td><img src="https://github.com/pangcrd/TFT_ST7789V_STM32F03C6/blob/main/image/photo_2024-09-25_15-34-14.jpg" alt="Image 1" width="500"/></td>
    <td><img src="https://github.com/pangcrd/TFT_ST7789V_STM32F03C6/blob/main/image/photo_2024-09-25_15-34-17.jpg" alt="Image 2" width="500"/></td>
  </tr>
</table>
