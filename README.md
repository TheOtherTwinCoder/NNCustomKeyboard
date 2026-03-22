[Sponsored by AIVON](https://aivon.com)

# NNCustomKeyboard
I love keyboards, but they're not all that great - so let me make my own one something custom, so it's mine and something useful, so it's more practical than a traditional one!

## Look here first!

Here's my Github's sitemap:
3D Files - includes 3D file of PCB (STEP and an image), and its case

Production - includes Gerber Files, BOM, AND PNP/CPL files for PCB Fabrication

Projectfiles - includes .kicad_pcb, .kicad_sch, and .kicad_pro files to open PCB in KiCad

Links (MD file) - includes resources to build this project

README (MD file) - includes images of the PCB, the CSV file of BOM, and Assembly Instructions!

Thank you, Hack Club, AMD, Blueprint, and AIVON!

## Onshape Link

https://cad.onshape.com/documents/f36815683b46d8fc882c34f1/w/c2f7f80d4310b2d3346a9409/e/7df84b3fbc8833d7e647c037

## Full Assembly

<img width="1095" height="494" alt="Screenshot 2026-03-22 at 12 18 09 PM" src="https://github.com/user-attachments/assets/d40aabae-cbfe-4f5d-9bc1-2c71eaa69d09" />

## The V2 PCB:

<img width="1258" height="536" alt="image" src="https://github.com/user-attachments/assets/fc3df360-ba9d-43fe-94c4-6e3d9184707a" />

## The PCB Schematic:

<img width="1642" height="868" alt="image" src="https://github.com/user-attachments/assets/6f5e12a3-1a9b-4055-b948-fe93541b01e2" />

## Wiring Schematic

<img width="811" height="547" alt="Screenshot 2026-03-16 at 1 09 35 PM" src="https://github.com/user-attachments/assets/130e8fd6-d89d-4b36-b55a-1272a57da68c" />

## BOM


| Items | Cost | Links | 
| :---: | :---: | :--- |
| Alpha Keys | $2.77 | (https://www.aliexpress.us/item/3256805792312994.html?spm=a2g0o.productlist.main.12.73d47e81v9eLzK&algo_pvid=c15d0a88-20ab-49d7-9c50-cfdaf69e2e98&algo_exp_id=c15d0a88-20ab-49d7-9c50-cfdaf69e2e98-11&pdp_ext_f=%7B%22order%22%3A%22592%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2132.73%217.77%21%21%21224.15%2153.17%21%402101dedf17741192468633377e1610%2112000035146888338%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ad098110%3Bm03_new_user%3A-29895%3BpisId%3A5000000197827646&curPageLogUid=56gUHibOIKh2&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005978627746%7C_p_origin_prod%3A) |
| PCB | $39 | Order using Gerber Files in the production folder :), this is a JLCPCB estimate, not including shipping. |
| Nice-Nano | $25 | https://typeractive.xyz/products/nice-nano?utm_source=nicekeyboards&utm_medium=referral&utm_campaign=find-a-store |
| Battery | $8 | https://t.ly/81SML |
| Switches | $30 | https://mechanicalkeyboards.com/checkouts/cn/hWNA2r5NHFXzy1tke3oyGLrU/en/information?_r=AQABIg-5BnWXsXSk4_bNypzt72TOds3C857VtIc9BUQPFP0&auto_redirect=false&edge_redirect=true&skip_shop_pay=true|
| Stabilizers | $1 | https://www.keychron.com/products/keychron-gold-plated-pcb-mounted-stabilizer-set?variant=40142423162969&country=US&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOopGC2sEL_ogdcSOZLuLDr0binjVVVFys3JigTozS6elob_414EHnZQ |
| Grand Total | $138 | Submitting for review on Mar 21st!!! :) |

## Assembly

1. Since PCBA already assembled the diodes, we can skip this step. However, if no PCBA, solder on the diodes manually.
2. Solder on the AliExpress switches (found in the BOM).
3. Solder on Nice!Nano (BOM), and solder battery (BOM) to B+ and B- pins.
4. 3D Print the Case, located in STEP3D
5. Take the assembled PCB and slot it into the case
6. Solder on the rgb controller to the nice!nano, and the light strip to the controller.
7. Follow the instructions in [this video](https://www.youtube.com/watch?v=O_urj-rF3bQ)
8. That's it :)
