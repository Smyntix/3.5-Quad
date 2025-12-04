#  3.5" Freestyle Quad Build

This is a **Hack Club project** documenting the build of a **3.5-inch analog freestyle quadcopter**.

The build can run on both **4S or 6S**, and you can choose your own protocol.
My personal build will be **4S + ELRS**, using **1804 3500KV motors** and an **ELRS 2.4GHz receiver**.

---

## 🔧 Specs Overview

* **Quad size:** 3.5"
* **Video system:** Analog
* **Battery:** 4S or 6S (user choice)
* **Control link:** ELRS / other protocols supported
* **Build goal:** best price/performance, durable, freestyle-oriented

---

## 🧩 Components

### Frame

* **FlyFishRC Volador VX3.5**

### Motors

Based on the lipos you're gonna use:

* **4S:** 1804 – 3500KV
* **6S:** 1804 – 2450KV

> Tip: As prices have skyrocketed, choose the cheapest reliable brand you can find.

### VTX (Video Transmitter)

* **SpeedyBee TX800 – 800mW**

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

## 🧰 Tools & Miscellaneus You'll Need

* **Soldering iron** with fine and wide tips (I use a TS100 as you can run it on lipos, but there are much cheaper alternatives)
* **Good leaded solder + flux**
* **Blue Threadlocker**
* **Heatshrink**
* **XT30 / XT60 connectors** (depending on batteries)
* **12–14 AWG wire** for battery leads
* **Capacitor** (often included with FC/ESC)
* **Small zip ties**
* **Computer with Betaflight**

  > Any OS and specs work. Some FCs support Bluetooth so you can even use your phone.

---

## 📌 Notes

* Most FC stacks include: battery leads, capacitor, and sometimes XT connectors.
* Always double-check polarity before soldering your XT connector.
* Match your antenna polarization with your goggle antennas.

---

## ✅ Planned Build (My Configuration)

* 4S battery
* 1804 – 3500KV motors
* ELRS 2.4GHz
* Analog video
* 3.5" Freestyle setup

## Total Cost 

* the total should come out to around 200-250€ depending on the brands you buy and the website you use.
  
  I've obversed that in the last period aliexpress prices have rose so much that some parts (for example the frame and the vtx) cost more on aliexpress
  that on the local store i use, while arriving 2 weeks later, so i reccomend just buying from your local shop as the price difference is minimal.
---

Feel free to fork, modify, or improve this build.
If you have any tips on how to improve this build, or have some Betaflight tunes you made and want to share with the community, feel free to do so!
