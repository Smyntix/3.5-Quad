# Custom 3.5" FPV drone Build

This is a **Hack Club project** documenting the build of a **3.5-inch analog freestyle quadcopter**.

The build can run on both **4S or 6S**, and you can choose your own protocol.
My personal build will be **4S + ELRS**, using **1804 3500KV motors** and an **ELRS 2.4GHz receiver**.

---

##  Specs 

* **Quad size:** 3.5"
* **Video protocol:** 2.4 GHz Analog
* **Battery:** 4S or 6S (user choice)
* **Radio Protocol:** 2.4 GHz ELRS, but other protocols are supported
* **Build goals:** Custom made frame, Custom Vtx PCB, custom Flight system, Custom betaflight FC firmware, Custom esc BHeli firmware

---

##  Components

### Frame

* **Diy 3.5" deadcat frame cut from 2.5/3.5mm carbon fiber/3d printed with CF-filled filament**

### Motors

Based on the lipos you're gonna use:

* **4S:** 1804 – 3500KV
* **6S:** 1804 – 2450KV

> Tip: As prices have skyrocketed, choose the cheapest reliable brand you can find.

### VTX (Video Transmitter)

* **Diy 800mw/1W vtx using OpenVTX source firmware**

### Flight Controller (FC) + ESC Stack

Requirements:

* **Minimum 30A**
* **Size:** 20x20 mm or 25x25 mm
* **USB-C preferred**
* From a **reputable brand**

Examples:

* GOKU GN405 – 30A
* SpeedyBee F405 Mini BLs – 35A

### Receiver (if needed)

* **SpeedyBee ELRS 2.4GHz Nano Receiver**
  
  note that your FC might include an onboard 2.4ghz ELRS receiver

### FPV Camera

* **Recommended:** Runcam Phoenix 2
* **Cheaper alternative:** Runcam Robin 3

  > Note: Lower image quality and poor low-light performance

### Antenna

* **Short SMA VTX antenna**
* Match polarization with your goggles: **RHCP or LHCP**

---

##  Notes

* Most FC stacks include: battery leads, capacitor, and sometimes XT connectors.
* Always double-check polarity before soldering your XT connector.
* Match your antenna polarization with your goggle antennas.


## Total Cost 

* the total should come out to around 200-250€ depending on the materials you use to fabricate the different components and the brands you choose to buy for the rest.
  
  I've obversed that in the last period aliexpress prices have rose so much that some parts (for example the Motors and the Fc) cost more on aliexpress
  that on the local store i use, while arriving 2 weeks later, so i reccomend just buying from your local shop as the price difference is minimal.


Feel free to fork, modify, or improve this build.
If you have any tips on how to improve this build, or have some Betaflight tunes you made and want to share with the community, feel free to do so!

---

# Frame details

## Materials - manufacturing

*  If you're CNC cutting it, you should cut the frame from **high-quality 2.5mm and 3.5mm carbon fiber** sheets:

  * **3.5mm** for the arms
  * **2.5mm** for everything else

* If you’re 3D printing it:

  * Use a material with **very high tensile strength** (like **CF-infused ASA** or **CF-infused PETG**)
  * Use **100% infill**
  * Make sure the layers bond well between each other (for example you could use **0.1mm layer height**)
  * Use **thin washers** for bolts and standoffs that need a bit more torque than the rest
    *(don't use threadlocker or it will destroy the print)*

---

## Hardware

* You should only need a mix of **M2 and M3 bolts**
* You need some **20mm / 25mm standoffs**
  I’ll upload a **detailed BOM and full parts list** as soon as I get the funding and actually build it

---

## Compatibility

The frame supports:

* **15x15mm and 20x20mm cameras** (including digital)
* **20x20mm and 25x25mm mounting holes** for:

  * FC & ESC stacks
  * VTX

It’s also designed to:

* Give the VTX **better airflow** for cooling VTX's that need to dissipate more head (like the O4)
* Let you 3D print accessories for:

  * Any antenna you want to mount (ex. double antennas for digital)
  * Any action cam
* Mount **bigger LiPos on the bottom**, thanks to the strap holes i added on the bottom plate

---

## Files

You can find the **full CAD file** for the frame (along with renders and everything else) in this GitHub repo and on the **Hack Club** page for this project

Feel free to **modify**, **test**, or **improve** the design if you want to.


