# NFC Hacker Card 
This is  Design of my NFC Bussiness Card or You can call it a Hacker Card as well. I was starting out the Hardware and found this thing as a cool project and Let me know the basics so I build this Thing.

### Project function
This is a NFC card mean it can read and write the NFC commands and exectue them as well. It uses NT3H2111W0FHKH IC for the NFC handeling and a 25x48 antenna , a LED light , a 47Ω Resistor and 220nF Capacitor. The led Will blink whenever the antenna harvests the energy.

# BOM 

- A NT3H2111W0FHKH NFC Chip: this will be the main component of our card -- it both handles the NFC functionality as well as harvests energy from the phone to light up the LED
- An ~2V LED. I'm using C2296, but feel free to pick a different version (note: this part may also be called 17-21SUYC/TR8)
- A 47Ω resistor
- A 220nF capacitor
- A NFC antenna That works well but It is engraved on the PCB 

| No. | Quantity | Comment       | Designator | Footprint                                   | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier |
|-----|----------|---------------|-------------|---------------------------------------------|-------|-------------------|--------------|---------------|----------|
| 1 | 1 | 220nF | C1 | C0603 |  | CL10B224KA8NNNC | SAMSUNG | C21120 | [LCSC](https://www.lcsc.com/product-detail/C21120.html?s_z=n_q_CL10B224KA8NNNC&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFJSRFRbVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4MCAlJGBEaDgsIBA%3D%3D) |
| 2 | 1 | 17-21SUYC/TR8 | LED1 | LED0805-R-RD |  | KT-0805 Yellow LED | KENTO | C2296 | [LCSC](https://www.lcsc.com/product-detail/C2296.html?s_z=n_q_KT-0805%2520Yellow%2520LED&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFNVRVdeUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVBfVVRIHxUDCw%3D%3D) |
| 3 | 1 | 47Ω | R1 | R0603 |  | 0603WAF470JT5E | UNI-ROYAL | C23182 | [LCSC](https://www.lcsc.com/product-detail/C23182.html?s_z=s_p_0603WAF470JT5E&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFNfTlVXUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| 4 | 1 | NT3H2111W0FHKH | U1 | XQFN-8_L1.6-W1.6-P0.50-BL_NT3H2111W0FHKH |  | NT3H2111W0FHKH | NXP | C710403 | [LCSC](https://www.lcsc.com/product-detail/C710403.html?s_z=n_q_NT3H2111W0FHKH&spm=wm.fly.bg.0.xh&lcsc_vid=EgdXVwICRgMMUQdTT1AKU1ZfQgRfUVFSEVRcXldUEQIxVlNeQlNdVFxVRVFbVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVJfX1ZIHxUDCw%3D%3D) |


<img width="1091" height="757" alt="image" src="https://github.com/user-attachments/assets/840e336a-caae-4123-8a75-1486d4122b41" />

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
