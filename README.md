DIY: External rechargeable power pack for Wildlife Acoustics Song Meter
===
&ensp;&ensp;Song Meter SM3 and SM4 families made by [Wildlife Acoustics](https://www.wildlifeacoustics.com/) are very good schedulable recorders for monitoring the acoustic and ultrasonic soundscape. But when we used the internal battery bay with 4 high capacity D size disposable alkaline batteries ([Panasonic Pro Power D](https://www.panasonic-batteries.com/en/alkaline/pro-power/pro-power-d)), the SM4 recorder will work no more than 4 weeks when it was scheduled to 1 minute on and 2 minutes off for 24 hours every day. If the batteries were replaced with NiMH rechargeable batteries, it can work less than two weeks. And when using external power cable and a 12V lead–acid batter for SM4BAT-FS, we always got the problems of incomplete recordings. 
&ensp;&ensp;So, we made a external, replaceable, waterproof, and all-weather battery pack with rechargeable 18650 Li-ion batteries. It can be used for more than one month with the schedule we needed and can be recharged for more than 1000 times.

# Overview
1. There are 3 parts of this external power pack: A [waterproof box](#box), with a [battery pack](#battery-pack) inside, and a [quick-connect cable](#connect-cable) that can connect the Song Meter with the battery box.
2. By using this pack, we can prepare the power packs in the office, then replace the old power pack with a new one quickly in a field.
3. The Song Meter SM3 and SM4 families can accept external power with voltages from 5-17 volts DC, so you can use any rechargeable battery pack in this limit with a suitable size of waterproof box.
4. For the purpose of preventing the over-discharge of batteries, we should set a minimum external battery voltage ("Battery Cutoff" in the recorder setup) to a suitable value. Ex: using four 18650 batteries in series, the working voltage for each battery is from 3.2-4.2, so the minimum voltage should be setted to 3.2*4=12.8 volts.
![](images/DSC_0325.JPG)

# Materials
1. [SM3/SM4 External Power Cable SM3CABPWR](https://www.wildlifeacoustics.com/shop) * 1
2. [Panasonic 3350mAh 18650 Li-ion Battery](https://voltaplex.com/panasonic-b-18650-battery-ncr18650b) * 8
3. [4S 18650 Battery Holder Case Box for 4X 18650 ~15V output](https://www.amazon.com/Battery-Holder-Li-Ion-Envistia-Mall/dp/B07N51QLDK) * 2
4. [2-Pin JST SM Connector](https://www.pcboard.ca/jst-sm-2-pin-connector-set) * 1 set
5. [SP13 2 pin Waterproof Connector](https://www.aliexpr+ess.com/i/32831082544.html) * 1 set
![](images/DSC_0310.JPG)
6. [115x90x55 PC IP65 waterproof Box](https://www.enika.eu/elbox-115x90x55-pc-ip65-g212_z183/) * 1
7. [Heat-shrink tubing 2mm](https://www.aliexpress.com/i/32782752536.html): 1cm * 2
8. [Heat-shrink tubing 3mm](https://www.aliexpress.com/i/32782752536.html): 3cm * 2

# <a id="battery-pack">DIY Step 1： Battery Pack</a>
1. Use hot glue guns or other adhesives to bond 2 battery holders together back to back.
![](images/DSC_0279.JPG)
2. Slide 3mm tubings onto the two wires of male JST SM connector.
![](images/DSC_0281.JPG)
3. Wrap and tie the 3 wires, 2 from battery holders and 1 from connector, together for each of black (negative) and red (positive) wires and solder them.
![](images/DSC_0283.JPG)
4. Slide the tubings onto the soldered wires.
![](images/DSC_0284.JPG)
![](images/DSC_0285.JPG)
5. Use a lighter or heat gun to shrink the tubings.
![](images/DSC_0286.JPG)
![](images/DSC_0287.JPG)
6. Use a multimeter to check the 2 holders are connected completely for each of positive and negative terminals.
![](images/DSC_0290.JPG)

# <a id="connect-cable">DIY Step 2: Quick-connect Cable</a>
1. Cut the battery end out of power cable.
![](images/DSC_0313.JPG)
2. Strip the cable for 10 mm then you can see 3 wires. 
![](images/DSC_0314.JPG)
3. Cut out the bare wire and strip the brown and white wires for 5 mm in length. Then pass it through the shell parts of SP13 male connector.
![](images/DSC_0315.JPG)
4. Solder the white wire (negative) to contact no. 1 and brown wire (positive) to contact no. 2 of connect head of SP13 male connector.
![](images/DSC_0319a.JPG)
5. Slide 2mm tubings onto the two wires of female JST SM connector.
![](images/DSC_0318a.JPG)
6. Solder the female JST SM connector to SP13 rear mount. White wire (negative) to contact no. 1 and red wire (positive) to contact no. 2.
![](images/DSC_0319b.JPG)
7. Slide the tubings onto the soldered contacts and shrink the tubings.
![](images/DSC_0321.JPG)

# <a id="box">DIY Step 3: Quick-connect Waterproof Box</a>
1. Drill a 13 mm diameter hole in the center of shorter side of the box.
![](images/DSC_0308.JPG)
![](images/DSC_0309.JPG)
2. Set the SP13 rear mount in the hole firmly.
![](images/DSC_0322.JPG)

# Usage
1. Install the full charged batteries in the battery holder and connect the JST SM connector.
![](images/DSC_0323.JPG)
2. Put the battery holder inside the waterproof box and close the box firmly.
![](images/DSC_0324.JPG)
3. Connet the cable with box and recorder at each end.
![](images/DSC_0326.JPG)
4. Slide the power switch of recorder up to "EXT".
![](images/DSC_0325.JPG)

# Battery Life
1. Testing parameters
    * Song Meter SM4BAT-FS
    * 1 minute on and 2 minutes off from 16:00 to 08:00
    * 384kHz sample rates, 16-bit PCM .wav files
    * Panasonic 3350mAh 18650 Li-ion Battery * 8
2. Results
16.2 volts at day 0 and 11.9 volts at day 31 and all recordings are complete.
![](images/batterylife.png)