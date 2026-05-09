# LoRa_board-myway
For this project, I'll be designing the schematic and a custom PCB from that schematic based on the Stasis Meshtastic LoRa Board starter guide. The difference between mine and the guide's board is that mine adds the PCB to be able to charge from a simple LiPo battery  (and don't forget the silkscreen art on the PCB!!)

# Overview
In short, I'll be using the guide from Hack Club Stasis starter projects ( [https://stasis.hackclub.com/starter-projects/devboard](https://stasis.hackclub.com/starter-projects/meshtastic-lora) ), of which I'll be using the same ESP32 WROOM-1 chip, which is the same chip used in most ESP32-based boards, and would act as the main thing in the build + an S1262 radio chip to be able to communicate and send data using the Meshtastic system. By using this guide, I made my own basic LoRa board and added extra functionality to it!!!!


# 🛠️ Design & Components 
In my design, I have used:


<img width="753" height="548" alt="Footprints_2" src="https://github.com/user-attachments/assets/0b56d3a9-562f-4a05-8fab-1769bc2cbdff" />

<img width="760" height="574" alt="Footprints_1" src="https://github.com/user-attachments/assets/6533ffe9-30af-4e0d-b2a9-18ef7ac51699" />
# ⚙️ Tools & Process
Using the base guide on stasis, I created a schematic template for my devboard. After which I added my own things to the devboard, including a fully functional battery module to the PCB using a TP4056 and an AMS1117-3.3 module to make the connection a JST pin header to connect it to the battery itself. And also added silkscreen to make the project feel more alive in a way (idk).

# 📈 Progress
After the schematic was completed, the project entered the PCB stage. This was quite difficult at first, trying to cram all of this into such a small profile, so the prototype model of the PCB did not look that great. Knowing this would not be sufficient for submition i did a complete re-work of the PCB and learnt a few things doing it, that the storage decoupling capacitors and the crystal oscillator should be really close to not cause errors in their own cases. After all of that horror of a long time spend trying to figure things out I think the project overall went ok. Heres a few photos of how the final project looks:

<img width="718" height="579" alt="PCB_lora(3d)" src="https://github.com/user-attachments/assets/572b6c07-3139-4999-83ad-479d2be67a21" />
<img width="1366" height="727" alt="PCB_lora(3d-back)" src="https://github.com/user-attachments/assets/f3056c85-225e-4547-86e9-6929310f6159" />



# 💭 Final Thoughts + Conclusion
Overall, this project was unexpectedly difficult, but it was fun understanding how a radio board like this worked, and it was quite interesting to learn how the Meshtastic system connections worked. Can't wait to actually see my final built project!!!
