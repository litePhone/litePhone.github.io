Learn how to utilize Electronic Design Automation (EDA) software like EasyEDA to design your custom PCB and use JLCPCB’s SMT (Surface-Mount Technology) manufacturing service to fabricate your board.

**Objective:**

Gain hands-on experience with EDA tools by designing, validating, and preparing a PCB specifically tailored for your litePhone project. Additionally, familiarize yourself with the industrial manufacturing process by submitting your design to JLCPCB for professional fabrication and assembly.

___

<iframe title="EasyEDA Full TUTORIAL + Create Component + TIPS" width="500" height="281" src="https://www.youtube.com/embed/utBQqcuOt9U?feature=oembed" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen=""></iframe>

## Part 1 – PCB Design using EasyEDA

___

Use [EasyEDA](https://easyeda.com/), a user-friendly, browser-based EDA tool to create your custom PCB design tailored for your ESP32-based litePhone.

Requirements:

Your PCB must include:

-   ESP32 footprint for the selected ESP32S3 MCU
-   Footprints for necessary components: GSM module (e.g., SIMCom A7670G), battery management circuit, SIM card slot, audio components (speaker, microphone), TFT connector, and USB interface
-   Proper schematic capture clearly showing connections between components
-   PCB layout following best practices:
    -   Adequate spacing for SMT assembly
    -   Clear silkscreen labels
    -   Appropriate power and ground plane utilization
    -   Mounting holes and connectors clearly defined

> 🏆 Challenge
> 
> Optimize your PCB layout to minimize signal interference and improve power efficiency. Document the considerations taken.

## Part 2 – Preparing Gerber Files and BOM for JLCPCB

___

Export the following files necessary for manufacturing:

-   Gerber files (used by JLCPCB to manufacture your PCB)
-   Bill of Materials (BOM) file, formatted for JLCPCB’s SMT assembly service
-   Component Placement File (Pick and Place)

Steps:

-   Verify design rules using EasyEDA’s Design Rule Check (DRC)
-   Export Gerber files, BOM, and Pick and Place files directly from EasyEDA
-   Cross-verify each file for accuracy and completeness

> 🏆 Challenge
> 
> Review JLCPCB’s SMT library beforehand. Select components readily available in their library to ensure smooth assembly.

## Part 3 – Ordering from JLCPCB

___

Steps:

-   Visit the [JLCPCB website](https://jlcpcb.com/) and create an account
-   Upload your Gerber files and confirm preview accuracy
-   Upload BOM and Pick and Place files for the SMT assembly process
-   Select board parameters (PCB thickness, color, surface finish, etc.)
-   Confirm assembly details, including component orientation and placements
-   Submit your order for manufacturing

Submit the following:

-   EasyEDA Project Files (.json, schematic, PCB layout)
-   Gerber files (.zip)
-   BOM and Pick and Place Files
-   Short report (1–2 pages) including:
    -   Overview of your PCB design
    -   Design decisions and trade-offs (component placements, routing choices)
    -   Iterations and revisions
    -   SMT Assembly experience and quality assessment
    -   Lessons learned

## Grading (100 Points)

___

-   PCB schematic clarity and accuracy (20 Points)
-   PCB layout quality and design rules adherence (20 Points)
-   Proper Gerber file, BOM, and Pick and Place preparation (20 Points)
-   Lab Report comprehensiveness and insights (40 Points)