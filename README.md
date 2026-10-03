<img width="3163" height="300" alt="blindspotsd" src="https://github.com/user-attachments/assets/96a3bda7-0b53-4bb3-8f0a-7218cdf6b704" />  

<img width="1300" height="320" alt="pcbwide" src="https://github.com/user-attachments/assets/9638d867-23e8-4a98-93ec-8973905cdd89" />


## What it is
BLINDSPOT is a custom project made for logging keys. It is designed to be as easy to use as possible.  It is made so one can log what's going on between their computer and keyboard, mouse or other peripherals.  
The intended purpose is to use it for either seeing whether your own computer has been used in your absence, or security testing a team on whether they identify and take action against unknown USB devices.  
> The use of it for surveilling others or gathering data without their consent is not endorsed.  

## How to assemble 
 
 1. Solder each component to it's respective pads (reference the BOM)
    <img width="500"  alt="assemblyguide" src="https://github.com/user-attachments/assets/78b92735-21ae-4c9e-85c8-c480c8f9e740" />

 2. Put the pcb in the bottom half of the case.  
    <img width="500" alt="image" src="https://github.com/user-attachments/assets/235b9ec0-b368-448b-bfdf-1a742a2084f4" />

3. Screw it to the case using 2x M2x4mm screws at these points.  
    <img width="500" alt="image" src="https://github.com/user-attachments/assets/c04ec208-9d9e-4912-aab5-dd2a75dda262" />

4. Cover it with the top half of the case, making sure the extrusions insert nicely into the slots.  
    <img width="500"  alt="image" src="https://github.com/user-attachments/assets/798cc83e-d24b-4ead-8704-095b820af48f" />

5. Secure the assembly together with a M2x8mm screw at the bottom  
   <img width="500" alt="image" src="https://github.com/user-attachments/assets/2514e6ce-0b99-48a9-8bfa-6702832668e7" />


**!! FLASHING INSTRUCTIONS NOT INCLUDED AS THE FIRMWARE IS NOT FINISHED.**


## Software

[ WIP ]


## Pictures

<img width="900"  alt="image" src="https://github.com/user-attachments/assets/4245d97a-8732-448b-aca3-d2135e012fea" />
<img width="900" alt="image" src="https://github.com/user-attachments/assets/a3d14af0-d57d-4705-b78c-8c426d821bf0" />



## Bom
|Reference|Qty| Value | Size | 
|--|--|--|--|
|C1, C2, C11, C15, C16, C17, C18, C19, C20, C21, C22, C23, C24|13|100nF|0603
|C3, C4, C5, C6, C12, C25, C26|7|1uF|0603
|C7, C8, C9, C10|4|27pF|0603
|C27|1|10uF|0805
|D1|1|Orange LED|0603
|D2|1|Blue LED|0603
|J2|1|480370001|-
|J3|1|292303-5|-
|R1, R2|2|33R|0603
|R3, R4|2|27R|0603
|R5, R6|2|10k|0603
|U1|1|RP2040|QFN-56_7X7
|U2|1|W25Q32JVSS|SOIC-8
|U3|1|AP2112K-3.3|SOT-23-5
|U4, U6|2|USBLC6-2SC6|SOT-23-6
|U5|1|MAX3421EETJ_|32-WFQFN-EP
|Y1, Y2|2|12MHz|5032-2

### Notes:
> The W25Q32JVSS (U2) can be substituted with any SOIC-8 flash memory chip of the same lineup (W25Q__JV) with a maximum of 128MiB space usable.


