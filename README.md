# LahmpPCB
This is my first attempt at designing a PCB using KiCad software and a CNC machine. The final outline does not necessarily read as a lamp persay, so I have aptly called it a llahmpuh, or lahmp for short.

<img width="373" height="445" alt="LampPCB" src="https://github.com/user-attachments/assets/1bfc80c1-85cc-4c30-820d-96de525dd0be" />

## Instructions
My instructions will be a rough overview of the development process, but for a detailed look at every step Miles has provided a really amazing tutorial that [you can follow here.](https://github.com/Barnard-PL-Labs/PCB-Milling-Project-for-Creative-Embedded-Systems/blob/main/README.md)

First, the files that contain the circuit schematic and PCB traces are in the 555timerCES folder and the file that contains the PCB outline is the SVG file called Lahmp.svg. The KiCad files should be sufficient on their own, but I also provided the SVG because future iterations should probably make adjustments in order to decrease the likelyhood of cutting off traces and increase the general readability of the final design.

You then need to convert the KiCad files to an SVG format that can be read by the CNC machine you are using. If you choose to manufacture your PCB through more traditional methods, you can simply upload the KiCad files to your manufacturing platform.

Assuming you are using the CNC, you then go step by step starting with the soldering holes, then the traces, and finally cutting the final outline in order to end up with your final PCB!
