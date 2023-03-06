# Microcontroller_Business_Card
A cheap simple business card with an embedded microcontroller

# Why?
I saw some really cool business cards with embedded projects and got jealous. I started this project with the aim of creating the cheapest (utilizing widely availiable parts) business card with an embedded microcontroller

# Part choices:
Capacitors and resistors:
I used 0402 capacitors and resistors to acheive a balance easy and cheap to source yet easily solderable by hand.  The only departure from this was the 0805 capacitor connected to the 3.3V supply, as the higher capacitance capacitors don't typically come in a 0402 package.

RP2040:
I used a RP2040 microcontroller due to its low cost and widespread availiability as well as its ubiquitous software. As the current silicon supply issues impact IC procurement I wanted to use a chip that could be ordered at any time.

FLash memory:
The W25Q128JVSIQ memory was chosen primarily as it was the suggested memory in the RP2040 datasheet, but also due to it's low cost and ubitquitous nature.

LEDs:
I selected these LEDs as they are extremely cheap individually addressable LEDs with a widely supported standard for interfacing (NEOPIXELS) when sourced from LCSC the individual cost per LED goes down to $0.014, while still allowing individual LED adressability. The final benefit of these LED's is that they only take up one pin of the microcontroller so are a no-brainer to include.

# Schematic: 
![Schematic_Business Card_2023-02-22](https://user-images.githubusercontent.com/87808632/220504306-95833c88-469a-4197-89e8-628704732c90.png)


# V1.0 PCB
Below are prototypes of the business card with basic layout and sub-optimal font/design:

- ![PXL_20230302_072053540](https://user-images.githubusercontent.com/87808632/223000269-8d1550bf-e352-4d35-8aa5-759158c50401.jpg)
- ![PXL_20230302_072237025](https://user-images.githubusercontent.com/87808632/223000271-c9dbdf17-92ad-4ffd-a155-f68f6b269bcc.jpg)
- ![PXL_20230302_072205421_2](https://user-images.githubusercontent.com/87808632/223000260-496599bd-e7b4-4e50-b132-2a7805a77b1a.jpg)
