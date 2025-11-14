Learn how to use simple Computer Aided Design (CAD) and Computer Aided Manufacturing (CAM) software to design and FDM print a simple enclosure for your litePhone.

**Objective:**

Gain hands-on experience with **Computer-Aided Design (CAD)** and **Computer-Aided Manufacturing (CAM)** by designing, slicing, and 3D printing a **functional enclosure** for your **litePhone** project. This lab bridges the gap between software/hardware integration and physical product design—a crucial aspect of embedded systems development.

___

<iframe title="Day 1 of Learn Fusion 360 in 30 Days for Complete Beginners! - 2023 EDITION" width="500" height="281" src="https://www.youtube.com/embed/d3qGQ2utl2A?feature=oembed" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen=""></iframe>

## Part 1 – CAD Modeling

___

You will use a beginner-friendly CAD tool like **Tinkercad**, **Fusion 360**, or **FreeCAD** to design a case for your ESP32-based litePhone. Your design must consider the size and layout of your hardware.

### Requirements:

-   Dimensions must match your **TFT screen**, **ESP32 DevKit**, and any other mounted modules (buttons, battery, SIM card slot, speaker, etc.).
-   The enclosure must:
    -   Be a **two-part shell** (top and bottom)
    -   Include **slots** to secure components
    -   Have cutouts for the **screen**, **USB port**, **power/reset buttons**, and **ventilation** if needed
    -   Be printable on an FDM printer

> 🏆 Challenge
> 
> Research how to design snap-fit mechanisms or friction-fit lids. Try to implement one in your design!

## Part 2 – CAM Workflow

___

Use a slicer like **PrusaSlicer**, **Ultimaker Cura**, or **Bambu Studio** to prepare your STL for FDM printing.

### Steps:

1.  Export your model from the CAD tool as an `.STL` file
2.  Import into your slicer of choice
3.  Preview and export the **G-code**
4.  Print using the lab’s 3D printer or submit the file for instructor printing

> 🏆 Challenge
> 
> If supports are needed for overhangs, try modifying your model to eliminate them instead. Document your reasoning.

## Part 3 – Assembly and Testing

___

Once printed:

-   Test the fit of each component
-   Identify any tolerance issues
-   If the screen or USB doesn’t align, **revise and reprint**
-   You should aim for **snug** but **non-damaging** fits

Submit the following:

1.  **CAD File (.f3d, .step, or equivalent)**
2.  **G-code/Slicer File**
3.  Photos of:
    -   Assembled Enclosure
    -   Internal View (open shell with components)
4.  Short report (1–2 pages) including:
    -   Overview of your design
    -   Design decisions (cutouts, fastening, part placement)
    -   Any iterations and what changed
    -   Lessons learned

## Grading (100 Points)

___

-   CAD Design matches hardware (accurate dimensions, cutouts) (20 Points)
-   Printability and slicer setup (20 Points)
-   Physical print quality and usability (20 Points)
-   Functional fit of components (20 Points)
-   Lab Report comprehensiveness and insights(20 Points)