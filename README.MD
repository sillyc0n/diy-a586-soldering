# Intro

Welcome to the build log for DIY-A586-v1.9, a project by piotr_go. This repository serves as a journal of DIY-A586-v1.9 build. Please note that the information provided here is based on the project's current state and may be subject to updates and improvements.

It is important to understand that the information and instructions provided in this document are intended for my own reference only. As of the time of writing, the build has not been completed, which means that the accuracy and correctness of the information cannot be guaranteed. Therefore, it is crucial to exercise caution if you decide to use information provided here in your own build.

This will be my first SMD soldering project. I take no responsibility for any of the information provided. Use at your own risk!

Latest version of my build log can always be found here: [https://github.com/sillyc0n/diy-a586-v1.9-soldering](https://github.com/sillyc0n/diy-a586-v1.9-soldering)

# Purpose

As I find myself in my forties, reminiscing about the charm of retro computing, one machine that continues to captivate my imagination is the Amiga. The Amiga holds a special place in the hearts of enthusiasts like me.

With a collection of old-school machines already in my possession, it feels like the perfect time to add an Amiga to my ensemble. However, this endeavor is about more than just acquiring another machine. It serves as a crucial stepping stone towards my ultimate goal—owning a real Amiga.

To accomplish this, I have chosen to embark on this project, building FPGA Amiga from scratch and teaching myself SMD soldering for the first time. An important step, before I attempt to build a truly real Amiga I need to get needed skills and confidence. 

And what better way to make the journey even more meaningful than involving my children in the process? By doing so, I hope to instill in them a passion for electronics and provide an invaluable hands-on learning experience.  As we solder each component together, my children will discover the magic of circuitry. It's about the journey of building something together and the lasting memories we'll create along the way.

Moreover, this DIY project serves as a gateway, reintroducing me to the world of Amiga computing in 2023. It allows me to reacquaint myself with the beloved machine and immerse myself in the vibrant Amiga community, where like-minded enthusiasts come together to appreciate its unique capabilities and artistic potential.

This shall serve as a testament to my dedication, determination, and unwavering passion for the retro computing era.

So, let us embark on this exhilarating journey together, using this project as yet another adventure in our lives.

# License

I hold no rights to the DIY-A584 board design. Therefore, always check and adhere to [DIY-A586 by Piotr Gozdur <piotr_go>](https://github.com/piotr-go/DIY-A586/tree/master#diy-a586-by-piotr-gozdur-piotr_go) for license information.

# Important links

You will find more information on [https://www.elektroda.pl/rtvforum/topic3891155-30.html](https://www.elektroda.pl/rtvforum/topic3891155-30.html).

# Build

## PCBs (2023-06-21):
I used piotr_go's gerber files from [https://github.com/piotr-go/DIY-A586/blob/master/v1.9/pcb/v1.9/gerbers.tar.gz](https://github.com/piotr-go/DIY-A586/blob/master/v1.9/pcb/v1.9/gerbers.tar.gz) as a source. Repacked as a zip and ordered boards from JLCPCB.

Following parameters were used:

- Layers: 2
- Dimension: 100 mm * 100 mm
- Product Type: Industrial/Consumer electronics
- Different Design: 1
- Delivery Format: Single PCB
- PCB Thickness: 1.6
- Impedance Control: no
- PCB Color: Black
- Silkscreen: White
- Via Covering: Tented
- Surface Finish: ENIG
- Gold Thickness: 1 U"
- Deburring/Edge rounding: No
- Outer Copper Weight: 1 oz
- Gold Fingers: No
- Flying Probe Test: Fully Test
- Castellated Holes: no
- Remove Order Number: No
- 4-Wire Kelvin Test: No
- Paper between PCBs: No
- Appearance Quality: IPC Class 2 Standard
- Confirm Production file: No
- Silkscreen Technology: Ink-jet/Screen Printing Silkscreen
- Package Box: With JLCPCB logo
- Board Outline Tolerance: ±0.2mm (Regular)

1. Why ENIG for a prototype boards designs: 
- because it was not much more expensive than a regular board

## Parts ordered (2023-06-24)
To acquire all the necessary components for the DIY-A586-v1.9 board, I made the following purchases:

1. **Bulk Order from LCSC:**
    - I placed a bulk order from LCSC, a reliable electronics components supplier, to obtain the majority of the required parts. I exported BOM file from LCSC to [LCSC_Exported__20230624_151154.csv](LCSC_Exported__20230624_151154.csv). This file contains most of the components needed. As a precautionary measure I ordered additional components and BOM should allow to assemble 3 boards. 

2. **1N4148 Diodes from eBay:**
    - I purchased the 1N4148 diodes from eBay using the following link: [https://www.ebay.co.uk/itm/115574778107](https://www.ebay.co.uk/itm/115574778107).

3. **PS2 Ports from AliExpress:**
    - To acquire the necessary PS2 ports, I placed an order through AliExpress using the provided link: [https://www.aliexpress.com/item/1005005368783447.html](https://www.aliexpress.com/item/1005005368783447.html) for **L 6Pin Straight Feet** and **K 6Pin Green**

4. **Tactile Switches from AliExpress:**
    - Lastly, I obtained the required tactile switches by making a purchase from AliExpress. I followed the link: [https://www.aliexpress.com/item/1005005274168459.html](https://www.aliexpress.com/item/1005005274168459.html) for **Type 3, 6x6x5mm switches**.
    
## Soldering equipment (2023-06-24):

To ensure a smooth soldering process, it is recommended to have the following tools and materials readily available:

- **Soldering Iron:** An inexpensive soldering iron can (hopefully?) be used for the task. You can find suitable options at [https://www.aliexpress.com/item/1005005368783447.html](https://www.aliexpress.com/item/1005005368783447.html).

- **Soldering Tips:** It is advisable to have a variety of soldering tips and accessories on hand. I will be using [https://www.aliexpress.com/item/1005003390702660.html](https://www.aliexpress.com/item/1005003390702660.html).

- **Soldering Wire:** For optimal results, I will use **WELLER Solder ROSIN CORE FLEX Wire WSWSACLO Sn3.0AG05CU 0.5mm 50gr LeadFree RoHS**.

- **PCB Circuit Board Holder:** To simplify the soldering process and ensure stability, I will utilise a PCB circuit board holder from [https://www.ebay.co.uk/itm/155581423064](https://www.ebay.co.uk/itm/155581423064).

- **Flux:** Soldering wire has flux core, so hopefully additional flux will not be needed but if required I will be using RELIFE RL-422 and Topnik TK-83.

## Soldering process
### Planning

### TBD

## Credits

Board designed by piotr_go. Thank you for answering my questions on Elektroda [DIY-A586 v1.9 by piotr_go](https://www.elektroda.pl/rtvforum/topic3891155-30.html).
