# Parts list

Prices are correct as of September 2025.
Metric part numbers are listed but Imperial are also available (remove the `/M` from the ThorLabs product codes).

## 1. Common optomechanical parts
Regardless of how you assemble the components, you will require the following.
| Item | Description | Approx Cost |
| --- | --- | --- |
| [MF252-39](https://www.thorlabs.com/thorproduct.cfm?partnumber=MF525-39) OR [Chroma AT495LP](https://www.chroma.com/products/parts/at495lp) | 25 mm emission filter | 200 GBP |
| [MD498](https://www.thorlabs.com/thorproduct.cfm?partnumber=MD498) | GFP dichoic  (see below)| 200 GBP |
| 2x [AC254-200-A](https://www.thorlabs.com/thorproduct.cfm?partnumber=AC254-200-A) | f=100 mm achromatic lens (objective) | 65 GBP |
| 2x [AC254-100-A](https://www.thorlabs.com/thorproduct.cfm?partnumber=AC254-100-A) OR 2x [AC254-150-A](https://www.thorlabs.com/thorproduct.cfm?partnumber=AC254-150-A) | f=50/f=75 mm achromatic lens (tube lens) | 65 GBP |
| 2x [SM1S2M](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1S2M) | 2 mm spacers for lenses | 7 GBP |
| [SM1A9](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1A9) | C-Mount to SM1 adapter | 16 GBP |

* You need an emission filter before the camera to block direct laser light.
You can either use something like a GFP filter or a low pass filter.
Two options are listed above.
The low-pass filter will work better in dimmer environments. 

* For lasers of different wavelengths, we have different options. 
 - For example, we have used a ZT473_594rpc-UF dichroic from Chroma (custom ordered | 428.32GBP) and [zet488-594nm](https://www.chroma.com/products/parts/zet488-594m) (518.48) emission filter for our 594nm laser. This dichroic and emission filter works with our 450nm laser too. 
 - It is worth noting, filters will be cheaper for single-band transmission

* With Basler a acA1920-40um camera the FOV of a system built with a f=100 mm objective and f=75 mm tube lens will be about 13.5 mm by 9.5 mm. 
This should yield about 7.8 microns/pixel.
Switching to an f=50 mm tube lens gives about 22 mm by 14 mm. Should yield about 11.72 microns/pixel.
The shorter tube lens is recommended to get the whole mouse skull into the FoV at once, but YMMV if you choose a different camera. 

## 2A. Optomechanical parts specific to our machined enclosure
If you are using our custom enclosure, you will need the following components.
| Item | Description | Approx Cost |
| --- | --- | --- |
| 4x [ER025](https://www.thorlabs.com/thorproduct.cfm?partnumber=ER025) | 1/4" cage rods for assembling the enclosure| 14 GBP |
| 2x [ER05-P4](https://www.thorlabs.com/thorproduct.cfm?partnumber=ER05-P4) | 2x packs of 1/2" ER posts for coupling laser to enclosure | 32 GBP |
| [PFR10-P01](https://www.thorlabs.com/thorproduct.cfm?partnumber=PFR10-P01) | 25 x 36 mm camera fold mirror | 75 GBP |
| [SS6MS6](https://www.thorlabs.com/thorproduct.cfm?partnumber=SS6MS6) | 6 mm M6 set screws* to plug adjustment holes | 5 GBP |
| 3x [SM1L10](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1L10) | 1" SM1 lens tubes to house objective lens and tube lens | 12 GBP |
| [SM1L03](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1L05) | 0.3" SM1 lens tube to couple the camera | 11 GBP |
| [SM1CPL10](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1CPL10) | To couple the camera | 30 GBP |
| [WG11010-A](https://www.thorlabs.com/thorproduct.cfm?partnumber=WG11010-A) | 1" BK7 window 1 mm thick |  75 GBP |

*Only four set screws are needed and the pack has 25. So if you are building multiple systems, one pack is likely enough.


**NOTE:** You will also need parts to mount the enclosure within your rig.
These are not included above.
If you need to add focusing ability you can buy ThorLabs [PT1/M](https://www.thorlabs.com/thorproduct.cfm?partnumber=PT1/M).
Alternatively, you might focus by moving the sample up and down. 

## 2B. Optomechanical parts for the general set-up
If you are building the Thorlabs-compatible version with no enclosure, you will need the following parts:

| Item | Description | Approx Cost |
| --- | --- | --- |
| 1x [CM1-DCH/M](https://www.thorlabs.com/thorproduct.cfm?partnumber=CM1-DCH/M) | Cage cube to hold dichroic filter| 14 GBP |
| 12x [ER05-P4](https://www.thorlabs.com/thorproduct.cfm?partnumber=ER05-P4) | 3x packs of 1/2" ER posts for coupling laser to enclosure | 32 GBP |
| 8x [ER025](https://www.thorlabs.com/thorproduct.cfm?partnumber=ER025) | 1/4" cage rods for connecting multiple parts, such as laser adapter to right angled mirror | 32 GBP |
| 2x [PFR10-03-P01](https://www.thorlabs.com/thorproduct.cfm?partnumber=PF10-03-P01) | Ø1" Protected Silver Mirror | 75 GBP |
| 2x [SM1L10](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1L10) | 1" SM1 lens tubes to house objective lens and tube lens | 13 GBP |
| 2x [SM05L03](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM05L03) | 0.3" SM05 lens tube to couple to adapter connecting cage cube and scanners | 12 GBP | 
| [SM1CPL10](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1CPL10) | To couple the camera | 30 GBP |
| [SM1A9](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1A9) | SM1A9 Adapter with threads to couple right angled mirror with lens tube housing tube lens | 18 GBP |
| 2x [SM1T2](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1T2) | SM1T2 Coupler to join cage cube and scanners, and lens tube with camera | 41 GBP |
| [SM2A6](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM2A6) | SM2A6 Threading ring to insert into scanners and to twist 1X SM1T2 into | 25 GBP |
| [SM1EC2B](https://www.thorlabs.com/thorproduct.cfm?partnumber=SM1EC2B) | Snap on cap to block light exiting the cage cube | 10 GBP |
| 2x [CP33T/M](https://www.thorlabs.com/thorproduct.cfm?partnumber=CP33T/M) | SM1-Threaded Cage plates to house emission filter and connect galvos to a right-angled mirror mount | 45 GBP |
| 2x [KCB1/M](https://www.thorlabs.com/thorproduct.cfm?partnumber=kcb1/M) | Right-angled mirror mounts to hold silver mirrors which direct light | 265 GBP |

We also used a translation stage for focusing and mounting, which are coupled to our scanners, by using a custom designed, 3D-printed plate. This does not have to be CNC machined, but you may prefer to do so for your set-up. 

## 3A. Mounting the laser in the custom enclosure
You will need to buy and modify an EO heatsink to make it possible to mount a ThorLabs 30 mm cage system onto it. 
The easiest way is to add 4x 4-40 threaded holes around the opening to attach rods and cages. We coupled the laser in via a single ThorLabs [KCB1/M](https://www.thorlabs.com/thorproduct.cfm?partnumber=KCB1/M#ad-image-0) mirror mount. 

| Item | Description | Approx Cost |
| --- | --- | --- |
| [Heat sink and mount of laser](https://www.edmundoptics.co.uk/p/coherentreg-obistrade-heat-sink-34249/3636/) | This part will require modifications | 180 GBP |

## 3B. Mounting the laser in the general set-up
For mounting the laser, we have chosen to go without the heatsinks but have designed custom adapters to join onto our Thorlabs set-ups. For the Obis laser, we have implemented a heat-sink like design as it is possible for it to shut off if it reaches temperatures above 40 degrees Celsius. All custom adapters are available in our CAD models of our set-ups, as well as individual files. We recommend getting these created by a CNC machining service, we used [HLH](https://www.hlhprototypes.com/cnc-machining/) as they are budget-friendly. For example, our Oxxius adapter was about 60 GBP and Obis adapter plate was about 120 GBP (both excluding shipping). 

These adapter plates were designed with Thorlabs parts in mind, so you should be able to use 1/2" ER posts (included above), M4 locking set screws for the Oxxius plate, and assorted screws that come with the Obis laser for the Obis plate. 


## 4. The expensive parts
All systems will require the following.

### USB Camera
We have been using the [Basler ace acA1920-40um Monochrome USB 3.0 Camera](https://www.edmundoptics.co.uk/p/basler-ace-aca1920-40um-monochrome-usb-30-camera/3421/) which retails at about 550 GBP.
This camera works well.
The sensor is about 11 by 7 mm and our hardware magnifies by a factor of 0.5 so the whole sample is visible.
In principle cameras by other manufacturers will also work, but this is not currently supported by the software.
Adding support is not planned at present, but would involve adding seperate classes for each camera type and modifying the settings system to cope with this. 
It is easier to buy the Basler camera.

### DAQ
The software requires an NI DAQ with four analog output channels.
The existing stimulators in the experiments are currently using an NI USB-6363, which is acceptable in terms of performance and easy to work with.
We have also tested all lasers with a USB-6453, and has been more useful with an analog input section for testing, larger bandwidth on the bus (USB 3) and a bigger FIFO buffer.

This device comes in different formats:
* Model 782259-01 requires two BNC-2090A breakout boxes and associated cables. 3100 GBP
* Model 781443-01 is screw terminal based and so won't require breakout boxes. 3250 GBP
* Model 782258-01 has an integrated breakout box, which is easier to work with than screw terminals, but more expensive. 3800 GBP.
* Model  782257-01 is an OEM board that can potentially be integrated into a custom enclosure along with the scanner control board and associated PSUs.

Finally, there is the *possibility* that a PCIe-based device might perform a little better during the stimulus ramp down.
If you have a spare PCIe slot and do not care about the possibility of making an intergrated enclosure for all the electronics, you can buy a PCIe-6363 (781051-01, 2300 GBP) plus two BNC-2090A breakout boxes and associated cables.

### Laser
So far we have worked exclusively with the [473 nm Obis laser 75 mW](https://coherentinc.force.com/Coherent/1185052?cclcl=en_US).
These units are are quite expensive at 6000 GBP.
We have bought the free space version and directly fed it into the scan head. 
We have not tried fibre-coupling for this application.
The output of 75 mW is more than enough for 2 points with a duty cycle of 50% and can do up to about 20 points with a time-averaged power of 2 mW and good mirror coatings. 
We are using the Obis lasers because they have proven to be reliable, stable, and switch very quickly.

The Obis laser will need one [male SMB to male BNC cable](https://uk.rs-online.com/web/p/coaxial-cable/7600405) to interface with the DAQ. 

We have also tested 
* [Oxxius 450 nm 100 mW](https://www.oxxius.com/products/lbx-405-5/) at about 3100 GBP 
* [Obis 594 nm 100Mw](https://coherentinc.my.site.com/Coherent/lasers/lasers-laser-systems/obis-lx-ls/1285744?cclcl=en_UK) at about 9400 GBP.

Other (untested) options that are slightly different wavelength but much cheaper and in principle should work well include:
* [Oxxius 450 nm 70 mW](https://www.oxxius.com/products/lbx-405-5/) at about 2800 GBP.
* [Oxxius 488 nm](https://www.oxxius.com/products/lbx-488/) With the 40 mW at about 2800 GBP and the 100 mW at about 6400 GBP.
* [Omicron 633 nm 100mW](https://photonlines.co.uk/product/omicron-luxx-compact-laser-diode/) at about 3200 GBP.

All the laser really needs is the ability to control power with an analog input and a linear power/control input response. Bandwidth of about 200,000 kHz or above should be enough. 
Other companies to consider include [Toptica](https://www.toptica.com/products/single-mode-diode-lasers) and [RPMC Lasers](https://www.rpmclasers.com/product/lbx-488-xxx-csb/). 
You can also look into [Changchun Optoelectronics](www.cnilaser.com/blue_laser473.htm) but be cautious as we have tried some of their cheaper lasers in the past and found them to be unstable. 
YMMV, though, and they are reasonably priced so might be worth a look.

### Scanners
The [5 mm Saturn Scanners](https://www.edmundoptics.co.uk/p/5mm-aperture-protected-silver-saturn-5b-dual-axis-galvanometer-scanner/44527/) are generally kept in stock by Edmund and retail for 2900 GBP.
They perform very well are near silent under the conditions that we run them.
Avoid Cambridge Technologies: their lead times are around 1 year and you will need to buy a spare set to insure yourself against potential down time should the scanners fail.
Failures happen and even repairs under warranty can take many months from this vendor.

The scanners come with a controller card but you will also need to buy two PSUs (to generate the +/- 24 V needed).
We are using [Mean Well Switching Power Supply, 24V dc, 4.2A](https://uk.rs-online.com/web/p/switching-power-supplies/8157450), which retail at about 65 GBP each.

Please note these power supplies have exposed screw terminals carrying mains voltage.
Talk to an experienced engineer if you are unsure about wiring and housing them safely.

Other plausible scanner options include [ThorLabs GVS002](https://www.thorlabs.com/thorproduct.cfm?partnumber=GVSK2-EC), which are cheap and easy to mount. 
These scanners have a lower bandwidth than the Saturn scanners and can cope with up to 5 points in a trial, depending on their spacing. These scanners have been tested with all lasers in the manuscript but have not been used experimentally so far. 

## 5. Tools and small parts
The following is a list of small parts and tools needed to build the system.

* Hex keys: 1.5 mm, 2.5 mm, 3/32, 0.05"
* 3x 3 mm grub screws. 5 mm long are fine too
* [SM1 lens tool](https://www.thorlabs.com/thorproduct.cfm?partnumber=SPW602)
 
