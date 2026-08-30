# NFC Hacker Card 
This is  Design of my NFC Bussiness Card or You can call it a Hacker Card as well. I was starting out the Hardware and found this thing as a cool project and Let me know the basics so I build this Thing.

### Project function
This is a NFC card mean it can read and write the NFC commands and exectue them as well. It uses NT3H2111W0FHKH IC for the NFC handeling and a 25x48 antenna , a LED light , a 47Ω Resistor and 220nF Capacitor. The led Will blink whenever the antenna harvests the energy.

# NFC Business Card - Bill of Materials
 
An NFC-powered business card. The NT3H2111W0FHKH handles NFC communication and harvests energy from the phone to light up an LED — no battery needed. The antenna is engraved directly on the PCB.
 
## Components
 
- **NT3H2111W0FHKH** - NFC chip, the main component of the card. Handles NFC functionality and harvests energy from the phone to light up the LED.
- **~2V LED** - using C2296 (also known as 17-21SUYC/TR8), but any similar 2V LED works.
- **47Ω resistor**
- **220nF capacitor**
- **NFC antenna** - engraved on the PCB itself, no separate part needed.
- 
## Bill of Materials
 
| No. | Quantity | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier |
|---|---|---|---|---|---|---|---|---|---|
| 1 | 1 | 220nF | C1 | C0603 | | CL10B224KA8NNNC | SAMSUNG | C21120 | [LCSC](https://www.lcsc.com/product-detail/C21120.html?s_z=n_q_CL10B224KA8NNNC&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFJSRFRbVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4MCAlJGBEaDgsIBA%3D%3D) |
| 2 | 1 | 17-21SUYC/TR8 | LED1 | LED0805-R-RD | | KT-0805 Yellow LED | KENTO | C2296 | [LCSC](https://www.lcsc.com/product-detail/C2296.html?s_z=n_q_KT-0805%2520Yellow%2520LED&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFNVRVdeUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVBfVVRIHxUDCw%3D%3D) |
| 3 | 1 | 47Ω | R1 | R0603 | | 0603WAF470JT5E | UNI-ROYAL | C23182 | [LCSC](https://www.lcsc.com/product-detail/C23182.html?s_z=s_p_0603WAF470JT5E&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFNfTlVXUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 4 | 1 | NT3H2111W0FHKH | U1 | XQFN-8_L1.6-W1.6-P0.50-BL_NT3H2111W0FHKH | | NT3H2111W0FHKH | NXP | C710403 | [LCSC](https://www.lcsc.com/product-detail/C710403.html?s_z=n_q_NT3H2111W0FHKH&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFxVRVFbVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVJfX1ZIHxUDCw%3D%3D) |
 
## PCB & Shipping
 
| Type | Item | Description | Qty | Build Time | Price |
|---|---|---|---|---|---|
| PCB | Gerber_Bussiness_card_Y9 | PCB prototype: Y9-13163216A, Black, 1.6 Thickness, HASL(with lead) | 5 pcs | 24 hours | $4.00 |
| PCBA | Gerber_Bussiness_card_Y9 | Economic PCBA: SMT026082762821-13163216A, Assemble top side | 2 pcs | 1 - 2 days | $15.78 |
 
| | |
|---|---|
| **PCB (Merchandise)** | $19.78 |
| Shipping | $16.01 |
| **Subtotal** | **$35.79** |
## Cart
<img width="1503" height="526" alt="image" src="https://github.com/user-attachments/assets/5413c07c-2ee8-4c98-a577-ab922a57309d" />
<img width="1094" height="756" alt="image" src="https://github.com/user-attachments/assets/e601b26a-d7da-4463-8535-7e1c582c671c" />
<img width="634" height="264" alt="image" src="https://github.com/user-attachments/assets/76e6d237-32ef-483d-8658-1ba8bacc9f43" />




### NOTE 

THE NFC ANTENNA USED IN THE SCHEMATIC IS FROM THE USER CONTRIBUTED LIBRARY FROM THE EASYEDA SO YOU MIGHT NEED TO GET THE PCB OR YOU CAN USE ANY ANTENNA THAT WORKS FOR NFC AND SUPPORTS NT3H2111W0FHKH IC. I AM USING A 25X48 FOOTPRINT AND IT IS ENGRAVED ON THE COPPER LAYER OF THE PCB.

# Schematics
<img width="1169" height="827" alt="Schematic_Business-Card_2026-07-28" src="https://github.com/user-attachments/assets/dd4e9dce-12a1-4539-8868-afb03fb726c8" />

# Boardview
<img width="403" height="259" alt="PCB_PCB_Business-Card_2026-07-28" src="https://github.com/user-attachments/assets/24f07b3a-f300-4db1-afcb-8763a4abe829" />

# 3D View 
<img width="1079" height="633" alt="image" src="https://github.com/user-attachments/assets/dfd59000-e37e-4cb8-a2f1-7018c9146786" />
<img width="1068" height="696" alt="image" src="https://github.com/user-attachments/assets/77b9d475-5e16-4c02-beea-79c715785dd6" />

### Author - Arsukie
