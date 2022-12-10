### Manta M5P Pinout table

<table>
   <tr>
   <td>Peripheral</td><td>Function</td><td>Pin name</td><td>Pin No.</td><td>Comment</td></tr>
   <tr>
   <td rowspan="4">X</td>
   <td>STEP</td><td>PC8</td><td>48</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>DIR</td><td>PC9</td><td>49</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>EN</td><td>PA15</td><td>47</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>CS/UART</td><td>PD9</td><td>41</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td rowspan="4">Y</td>
   <td>STEP</td><td>PA10</td><td>42</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>DIR</td><td>PA14</td><td>46</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>EN</td><td>PA13</td><td>45</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>CS/UART</td><td>PD8</td><td>40</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td rowspan="4">Z</td>
   <td>STEP</td><td>PC6</td><td>38</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>DIR</td><td>PC7</td><td>39</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>EN</td><td>PA9</td><td>37</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>CS/UART</td><td>PB10</td><td>30</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td rowspan="4">E0</td>
   <td>STEP</td><td>PB12</td><td>32</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>DIR</td><td>PB11</td><td>31</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>EN</td><td>PA8</td><td>36</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>CS/UART</td><td>PB2</td><td>29</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td rowspan="4">E1</td>
   <td>STEP</td><td>PB0</td><td>27</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>DIR</td><td>PB1</td><td>28</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>EN</td><td>PC4</td><td>25</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td>CS/UART</td><td>PA6</td><td>23</td><td>M5P is converted to 5V to driver</td></tr>
   <tr>
   <td rowspan="3">TMC SPI (spi2)</td>
   <td>MISO</td><td>PB14</td><td>34</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver,</td></tr>
   <tr>
   <td>MOSI</td><td>PB15</td><td>35</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td>SCK</td><td>PB13</td><td>33</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td rowspan="3">Heater</td>
   <td>E0</td><td>PC5</td><td>26</td><td>is converted to 5V to MOSFET with flyback protection</td></tr>
   <tr>
   <td>E1</td><td>PA7</td><td>24</td><td>is converted to 5V to MOSFET with flyback protection</td></tr>
   <tr>
   <td>HB(heated bed)</td><td>PA5</td><td>22</td><td>is converted to 5V to MOSFET with flyback protection</td></tr>
   <tr><td rowspan="3">Temperature</td>
   <td>TH0</td><td>PA1</td><td>18</td><td>4.7KOhm 0.1% pull up resistor for NTC100K,etc. 2.2KOhm 0.1% pull up resistor for PT1000 by jumper. with thermistor protection circuit</td></tr>
   <tr>
   <td>TH1</td><td>PA2</td><td>19</td><td>4.7KOhm 0.1% pull up resistor for NTC100K,etc. 2.2KOhm 0.1% pull up resistor for PT1000 by jumper. with thermistor protection circuit</td></tr>
   <tr>
   <td>THB</td><td>PA0</td><td>17</td><td>4.7KOhm 0.1% pull up resistor for NTC100K,etc. with thermistor protection circuit</td></tr>
   <tr><td rowspan="4">Endstop</td>
   <td>X-STOP</td><td>PD3</td><td>53</td><td>Share with X-DIAG</td></tr>
   <tr>
   <td>Y-STOP</td><td>PD2</td><td>52</td><td>Share with Y-DIAG</td></tr>
   <tr>
   <td>Z-STOP</td><td>PC3</td><td>16</td><td>Share with Z-DIAG</td></tr>   
   <tr>
   <td>E0-DET</td><td>PC2</td><td>15</td><td>Share with E0-DIAG</td></tr>
   <tr>
   <td rowspan="2">FAN</td>
   <td>FAN0</td><td>PA4</td><td>21</td><td>is converted to 5V to MOSFET with flyback protection</td></tr>
   <tr>
   <td>FAN1</td><td>PA3</td><td>20</td><td>is converted to 5V to MOSFET with flyback protection</td></tr>
   <tr>
   <td rowspan="2">Misc</td>
   <td>RGB1(Neopixel/WS2812)</td><td>PC11</td><td>1</td><td>is converted to 5V</td></tr>
   <tr>
   <td>RGB2(Neopixel/WS2812)</td><td>PC14</td><td>4</td><td>is converted to 5V</td></tr>
   <tr>
   <td rowspan="2">BLTouch</td>
   <td>SERVOS</td><td>PC15</td><td>5</td><td>Share with Proximity switch IO</td></tr>
   <tr>
   <td>PROBE</td><td>PC13</td><td>3</td><td></td></tr>
   <tr>
   <td rowspan="1">Proximity switch</td>
   <td>PROBE</td><td>PC15</td><td>5</td><td>PNP or NPN can be selected by jumper. multiplexing the same IO with BLTouch SERVOS</td></tr>
   <tr>
   <td rowspan="2">FDCAN1</td>
   <td>RX</td><td>PD0</td><td>50</td><td></td></tr>
   <tr>
   <td>TX</td><td>PD1</td><td>51</td><td></td></tr>
   <tr><td rowspan="2">USB-Device</td>
   <td>OTG_FS_DM</td><td>PA11</td><td>43</td><td></td></tr>
   <tr>
   <td>OTG_FS_DP</td><td>PA12</td><td>44</td><td></td></tr>
   <tr><td rowspan="10">EXP1</td>
   <td>5V</td><td>5V</td><td></td><td>Marlin: EXP1_01_PIN, Klipper: EXP1_10</td></tr>
   <tr>
   <td>GND</td><td>GND</td><td></td><td>Marlin: EXP1_02_PIN, Klipper: EXP1_9</td></tr>
   <tr>
   <td>LCD_D7</td><td>PB6</td><td>60</td><td>Marlin: EXP1_03_PIN, Klipper: EXP1_8</td></tr>
   <tr>
   <td>LCD_D6</td><td>PB7</td><td>61</td><td>Marlin: EXP1_04_PIN, Klipper: EXP1_7</td></tr>
   <tr>
   <td>LCD_D5</td><td>PB4</td><td>58</td><td>Marlin: EXP1_05_PIN, Klipper: EXP1_6</td></tr>
   <tr>
   <td>LCD_D4</td><td>PB5</td><td>59</td><td>Marlin: EXP1_06_PIN, Klipper: EXP1_5</td></tr>
   <tr>
   <td>LCD_RS</td><td>PD6</td><td>56</td><td>Marlin: EXP1_07_PIN, Klipper: EXP1_4</td></tr>
   <tr>
   <td>LCD_EN</td><td>PB3</td><td>57</td><td>Marlin: EXP1_08_PIN, Klipper: EXP1_3</td></tr>
   <tr>
   <td>BTN_ENC</td><td>PD4</td><td>54</td><td>Marlin: EXP1_09_PIN, Klipper: EXP1_2</td></tr>
   <tr>
   <td>BEEPER</td><td>PD5</td><td>55</td><td>Marlin: EXP1_10_PIN, Klipper: EXP1_1</td></tr>
   <tr>
   <td rowspan="10">EXP2</td>
   <td>NC</td><td>NC</td><td></td><td>Marlin: EXP2_01_PIN, Klipper: EXP2_10</td></tr>
   <tr>
   <td>GND</td><td>GND</td><td></td><td>Marlin: EXP2_02_PIN, Klipper: EXP2_9</td></tr>
   <tr>
   <td>RESET</td><td>RESET</td><td>12</td><td>Marlin: EXP2_03_PIN, Klipper: EXP2_8</td></tr>
   <tr>
   <td>SD_DETECT</td><td>PC12</td><td>2</td><td>Marlin: EXP2_04_PIN, Klipper: EXP2_7</td></tr>
   <tr>
   <td>MOSI</td><td>PB15</td><td>35</td><td>Marlin: EXP2_05_PIN, Klipper: EXP2_6. EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td>BTN_EN2</td><td>PC10</td><td>64</td><td>Marlin: EXP2_06_PIN, Klipper: EXP2_5</td></tr>
   <tr>
   <td>SD_SS</td><td>PB9</td><td>63</td><td>Marlin: EXP2_07_PIN, Klipper: EXP2_4</td></tr>
   <tr>
   <td>BTN_EN1</td><td>PB8</td><td>62</td><td>Marlin: EXP2_08_PIN, Klipper: EXP2_3</td></tr>
   <tr>
   <td>SCK</td><td>PB13</td><td>33</td><td>Marlin: EXP2_09_PIN, Klipper: EXP2_2. EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td>MISO</td><td>PB14</td><td>34</td><td>Marlin: EXP2_10_PIN, Klipper: EXP2_1. EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td rowspan="4">OnboardSD(spi2)</td>
   <td>SD-CS</td><td>PC1</td><td>14</td><td></td></tr>
   <tr>
   <td>MISO</td><td>PB14</td><td>34</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver,</td></tr>
   <tr>
   <td>MOSI</td><td>PB15</td><td>35</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td>SCK</td><td>PB13</td><td>33</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td rowspan="4">Expansion SPI pin header(spi2)</td>
   <td>SPI2-CS</td><td>PC0</td><td>13</td><td></td></tr>
   <tr>
   <td>MISO</td><td>PB14</td><td>34</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver,</td></tr>
   <tr>
   <td>MOSI</td><td>PB15</td><td>35</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td>SCK</td><td>PB13</td><td>33</td><td>EXP-2 SPI, Onboard MCU SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI2, and is converted to 5V to TMC driver</td></tr>
</table>

# Note
## Here’s BIGTREETECH! For Makers, by makers!
* We appreciate all of your support to BIGTREETECH! To offer an excellent experience of creation to every makers,We’re devoted to design and produce high-quality and durable accessories!

## How to contact:
### If you have any technical issue,please don’t hesitate contact us:
* BIGTREETECH: service004@biqu3d.com

### Follow us on social media to get more news:
* Facebook: https://www.facebook.com/BIGTREETECH/
* Twitter: https://twitter.com/BigTreeTech
* Instagram: https://www.instagram.com/bigtreetech_official/
* Official Site: https://bigtree-tech.com/
