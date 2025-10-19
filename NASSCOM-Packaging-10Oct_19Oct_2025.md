# NASSCOM-Packaging-10Oct_19Oct_2025

<img width="1039" height="583" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/COURSE%20PLAN.jpg" />
<img width="1039" height="583" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/MODULES.jpg" />

# Module 1: Packaging Evolution: From Basics to 3D Integration
L1: Introduction to Semiconductor Packaging
 Semiconductor packaging is the final step in the semiconductor device manufacturing process, where the processed chip (or die) is encased in a protective housing and connected to the external environment, such as a printed circuit board (PCB). This packaging safeguards the chip, enables electrical connections, and facilitates heat dissipation.
 <img width="1032" height="572" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/MODULE1.jpg" />
<img width="1032" height="572" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/0.jpg" />
<img width="1032" height="572" alt="image" src="https://github.com/user-attachments/assets/4ced9073-e23c-4772-b426-54e0992264e4" />

<img width="434" height="159" alt="image" src="https://github.com/user-attachments/assets/0a603af3-f129-4ce6-a2b5-28c9a0b499f8" />

Die is protected by the packaging system as shown in the above Figure
>> Key Functions of Semiconductor Packaging are Protection, Electrical Interface, Thermal Management, Mechanical Support
>> Packaging and Testing Industry
   
   <img width="1047" height="580" alt="image" src="https://github.com/user-attachments/assets/07f382f0-17e0-4848-9ddf-71829b84c1cc" />



Choosing the appropriate semiconductor package is a crucial aspect of electronic system design, as it directly influences performance, cost, thermal efficiency, physical size, and overall reliability.

<img width="1040" height="578" alt="image" src="https://github.com/user-attachments/assets/acfc9935-9187-4478-98d7-ac00a3e88ad9" />

<img width="631" height="329" alt="image" src="https://github.com/user-attachments/assets/9f0ea5fe-195e-4bd3-95d9-e0f6b64f1f38" />

 >> Common Packaging Types:
> >  DIP (Dual In-line Package):	Older style with two rows of pins. Easy to plug into sockets or breadboards.
> > QFP (Quad Flat Package)	:Pins on all four sides. Used in high pin-count ICs
> >  BGA (Ball Grid Array)	:Uses tiny solder balls on the bottom. Good for high performance & density.
> > CSP (Chip Scale Package)	:Very small, almost the same size as the chip itself. Ideal for mobile use.
> > WLCSP (Wafer-Level CSP)	Packaged at wafer level: no separate packaging step. Smallest and cheapest.
> > TSOP (Thin Small Outline Package)	Compact: used in memory ICs like flash or DRAM.

<img width="1044" height="588" alt="image" src="https://github.com/user-attachments/assets/c659fa5d-9741-410b-af9d-b60f02817ea1" />

Advanced/Modern Packaging Trends:
3D Packaging – Multiple dies stacked vertically to save space and increase performance.
System-in-Package (SiP) – Combines several chips and passive components in one package.
Fan-Out Packaging – Redistributes the connection pads to allow more I/Os in a small footprint.
Chiplets – Smaller chips integrated into a single package (popular in AMD and Intel designs).



A typical IC package consists of:

Die: The semiconductor die 
Carrier/ Substrate: The carrier or substrate is the intermediate structure on which the die sits and provides both mechanical support and electrical contact.
Die-to-carrier interconnections: The die is connected to the substrate using bond wires or solder bumps
Carrier-to-Board interconnections: The substrate is often soldered/ connected to the PCB for integration into larger systems using pins, leads balls or lands.

Key Materials:
>> Substrate – Usually a resin-based PCB material or ceramic.
>> Encapsulant – Epoxy resin that protects the chip.
>> Leads/Balls – Metal connections made of copper, tin, gold, or alloys.
>> Thermal Interface Material (TIM) – Enhances heat transfer from the chip to the package or heatsink.
>> 
<img width="1048" height="585" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/TYPICAL%20PACKAGE%20STRUCTURE.jpg" />

<img width="1043" height="578" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/ATONOMY%20OF%20PACKAGE.jpg" />


<img width="2596" height="1096" alt="image" src="https://github.com/user-attachments/assets/666c31cb-01bb-4633-b367-13579a2ee321" />



<img width="1043" height="595" alt="image" src="https://github.com/user-attachments/assets/4cdb498f-8786-4e35-9236-20eac20ae039" />

Figure above shows the anatomy of some of the commonly used leadframe and laminate based packages and advanced substrates

Advanced Substrates are

      2D: Dies placed side-by-side on the same substrate
      2.1D: Adds RDL for better routing
      2.3D: Uses organic interposers
      2.5D: Silicon interposer for high-speed interconnects (e.g.: CoWoS)

 Interposers, RDLs And 2.5D/3D Packaging Approaches

    Interposers in Semiconductor Packaging
          An interposer is a substrate or intermediate layer used in semiconductor packaging to electrically connect and mechanically support one or more dies (chips) with each other or with a package substrate or PCB. Think of it as a “bridge” that helps route signals between high-density components in advanced packaging solutions.
    Key Functions of an Interposer:
        Signal Routing – Provides fine-pitch connections between chips and the main board.

        I/O Fan-Out – Spreads the densely packed I/Os of a die over a larger area.

        Heterogeneous Integration – Enables integration of different chip types (logic, memory, analog, etc.).

        Thermal & Power Distribution – Assists in heat dissipation and distributes power efficiently.
        Passive vs. Active Interposers:
                     Passive: No logic, just routing and vias
                     Active: Includes power delivery, clocking, or even memory logic

>> Types of Interposers:

        | Type                   | Material                 | Use Case/Advantages                                             |
     | ---------------------- | ------------------------ | --------------------------------------------------------------- |
     | **Silicon Interposer** | High-resistivity silicon | Precise, high-density routing; commonly used in 2.5D packaging. |
     | **Organic Interposer** | PCB-like materials       | Lower cost, good for less complex designs.                      |
     | **Glass Interposer**   | Glass substrate          | Promising for RF and optical applications; still emerging.      |

 
    >> Interposers- Allows for greater integration without the yield and cost penalties of large monolithic chips, Supports high-speed, short-length interconnects, reducing signal loss and power consumption, Enables custom or modular chiplet architectures in AI, HPC, and data center applications. Types: Silicon, Organic, Glass

    >> Redistribution Layers (RDL): RDL, or Redistribution Layer, is a crucial metal interconnect layer added during the packaging process to re-route the I/O pads of a semiconductor die to new locations. This is especially important in advanced packaging techniques like Fan-Out Wafer-Level Packaging (FO-WLP) or Flip-Chip. It is used to:
    Repositions I/O pads to enable better spacing and routing.
    Expands connection area for external interconnects (e.g., solder balls or microbumps).
    Facilitates higher I/O density without increasing die size.
    Supports custom routing for heterogeneous integration or multi-die systems.

    >> Original I/O pads on the die are placed in a dense array (usually near the edges). RDL traces are created using photolithography and metallization to fan out these I/Os to a wider pitch or different pattern. Solder balls or microbumps are then attached to the new RDL pads, ready for mounting onto a substrate or interposer.
    

>>      "2.5D/3D Integration" typically refers to the process of combining 2.5D and 3D elements in digital design, development, or manufacturing workflows. The meaning varies depending on the context (e.g., gaming, animation, chip design, or PCB manufacturing).
>>     Combining 2D sprites with 3D environments (e.g., characters in 2D moving in a 3D space), Camera manipulation in a 3D environment to give the illusion of depth in 2D assets, Lighting and shading applied to 2D elements to match 3D surroundings.

>>     2.5D: Dies are connected laterally on an interposer using micro-bumps.
>>     3D: Stacked dies interconnected vertically using Through-Silicon Vias (TSVs).
>> 
<img width="1042" height="587" alt="image" src="https://github.com/user-attachments/assets/19fd3bf4-ebd7-4db5-ba38-63bfbd625111" />

COB- Chip on Board


Comaparison
Selecting the right semiconductor packaging depends on multiple criteria across performance, reliability, form factor and cost.

<img width="1038" height="584" alt="image" src="https://github.com/user-attachments/assets/a0e03481-22d1-47b2-bd94-6dc984e28c0e" />

# Module 2: From Wafer to Package: Assembly and Manufacturing Essential
     Semiconductor packaging is the final phase of semiconductor manufacturing, where chips (dies) are encased in a protective material and made ready for integration into electronic devices. This supply chain is complex, global, and involves several highly specialized processes and companies.
           ATMP – Assembly, Testing, Marking, and Packaging
<img width="1038" height="584" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/MODULE2.jpg" />
<img width="1038" height="584" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/5.jpg" />
    1. Wafer Fabrication (Upstream)
      Performed by IDMs (Integrated Device Manufacturers) or foundries like TSMC, Samsung, or Intel.
      Output: Bare silicon wafers with integrated circuits.

    2. Wafer Testing
       Electrical tests performed before dicing to identify good dies.

       Tools: Automated Test Equipment (ATE).

       
     3. Dicing and Die Attach
      Wafers are cut into individual dies.

       Dies are placed on substrates using adhesives or solders.

     4. Semiconductor Packaging
       Protects chips from physical damage and ensures electrical connectivity.

    Types: Wire bonding, Flip chip, Fan-out / fan-in WLP, 2.5D/3D IC packaging

    Players: 
     OSATs (Outsourced Semiconductor Assembly and Test):ASE, Amkor, JCET, Powertech, UTAC

     IDMs (in-house packaging): Intel, Samsung

    5. Package Testing
       Post-packaging test to ensure functionality.

     Reliability tests under heat, stress, and electrical load.

     6. Substrate & Materials Supply
       Substrates: High-density interconnect (HDI) materials that sit between the chip and PCB.

        Materials: Epoxy resins, underfills, solder balls, bonding wires.

     7. Final Assembly / System Integration
       Packaged chips are mounted on PCBs and integrated into systems (e.g., smartphones, servers). EMS (Electronics Manufacturing Services) firms may handle this

<img width="1036" height="583" alt="image" src="https://github.com/user-attachments/assets/72663590-4a61-46be-8f9d-2de84ccff303" />



>>  Introduction to a Package Manufacturing Unit (ATMP):
>> ATMP is a key part of the back-end of semiconductor manufacturing. It refers to the set of processes that take a silicon wafer—after front-end fabrication—and prepare it for shipment and integration into electronic systems.
 
    The ATMP process involves four core activities: 
     Assembly, Testing, Marking, and Packaging. 
     The ATMPs could be OSATs (like ASE, Amkor, TATA etc.) or in-house ATMPs of IDMs (like Intel, Samsung, Micron) or Foundries (like TSMC, Samsung Foundry)

     
  <img width="1034" height="586" alt="image" src="https://github.com/user-attachments/assets/51cfd335-3665-402b-ba5e-6df3eecfd1d6" />


     
   <img width="1032" height="324" alt="image" src="https://github.com/user-attachments/assets/79330031-6f0f-497b-8a05-1caa07938e97" />
>> ATMP: 
     1. Assembly
                Goal: Physically attach the die to a package or substrate.

                 Includes: Die attach (using epoxy, solder), Wire bonding or flip chip connections, Encapsulation with molding compounds
                 Advanced forms: System-in-Package (SiP), 2.5D/3D packaging, Fan-Out WLP

   2. Testing
              Electrical testing of the packaged chip to ensure it meets performance specifications.

          Burn-in testing: Accelerated aging under stress conditions.

          Final Test: Confirms correct operation before shipment.

          Test equipment: Supplied by Teradyne, Advantest, National Instruments

   3. Marking
          Laser or inkjet identification codes, batch numbers, and traceability info are printed on the package.

          Includes: Branding (logos, part numbers) Traceability (lot numbers, QR codes)

 4. Packaging
           Final form factor is completed:

        Plastic encapsulated packaging (e.g., QFN, BGA, CSP)

        Advanced packages (e.g., FOWLP, CoWoS, EMIB)

        Protection against:Moisture, Mechanical shock, Corrosion

    >> Wafer Pre-Preparation - Grinding And Dicing
    >> Clean room: wafer preparation process inside an ISO Class 7 cleanroom of an ATMP
    
    <img width="1048" height="583" alt="image" src="https://github.com/user-attachments/assets/dff1d2ed-b919-4e10-9574-f6b91b898555" />

    
Link: https://youtu.be/hR5orrmpoeE

>> Wire bond packaging:

<img width="1039" height="364" alt="image" src="https://github.com/user-attachments/assets/e06f1667-5560-4c4d-baab-a62c9be6256a" />

https://youtu.be/jliiUV0vDic

<img width="910" height="519" alt="image" src="https://github.com/user-attachments/assets/3d73ff55-4a91-40db-9628-d128f23aec9d" />


<img width="1040" height="338" alt="image" src="https://github.com/user-attachments/assets/68901b48-216d-4c80-9d41-ce5ccc5d18d3" />

<img width="912" height="577" alt="image" src="https://github.com/user-attachments/assets/1bbacd62-1055-42ab-ace7-6019d0a7c328" />

Wire bonding is a critical process used in microelectronics to create electrical interconnections between a semiconductor device (e.g., a chip) and its packaging or between two semiconductor devices. Here’s a general wire bonding procedure, typically for gold ball bonding or aluminum wedge bonding, which are the most common types.

>> Steps:
                 1. Die Attach (Die Bonding)-
                                     Apply adhesive to the die pad or leadframe, Pick-and-place die from the wafer to the substrate, Cure the adhesive using heat (e.g., 150–200°C for 1–2 hours, depending on material).
                  2. Die Attach Cure (Bake)
                  3. Wire Bonding
                  4. Wire Bond Inspection
                  5. Molding (Encapsulation)
                  6. Post-Mold Cure (PMC)

<img width="1031" height="541" alt="image" src="https://github.com/user-attachments/assets/53ee318a-0faa-47bf-ac6b-e28be2d17d21" />

<img width="1047" height="469" alt="image" src="https://github.com/user-attachments/assets/e1745b4c-1759-41f8-b133-40efe6cdd00a" />

<img width="710" height="565" alt="image" src="https://github.com/user-attachments/assets/77fefff7-f101-45c6-80cd-7a528b7b6e78" />

<img width="1030" height="584" alt="image" src="https://github.com/user-attachments/assets/3e05adc3-6f5a-40d6-85ac-97bcc1bdcb87" />

>> Flip Chip Assembly - Bump Formation And Underfill

     Flip chip packaging improves electrical performance and increases I/O density by mounting the semiconductor die face-down directly onto the substrate, enabling shorter interconnect paths and more efficient use of space.


>>      In flip chip assembly, bump formation and underfill are two critical steps that enable robust electrical and mechanical connections between the semiconductor die and the substrate. Bump formation involves creating small conductive bumps—typically made of solder (e.g., SnAgCu) or copper—on the die's bond pads using techniques like electroplating, solder paste printing, or stud bumping. These bumps serve as the connection interface between the die and the package or PCB. Once the die is flipped and aligned onto the substrate, it is reflowed to create solid metallurgical joints. After reflow, underfill is applied—an epoxy resin dispensed into the gap between the die and substrate. The underfill material flows by capillary action and is then cured thermally. This process enhances the mechanical strength, improves thermal cycling reliability, and protects solder joints from stress due to differences in thermal expansion between the die and the substrate. Together, bump formation and underfill ensure the electrical integrity and durability of flip chip assemblies.

   <img width="1051" height="591" alt="image" src="https://github.com/user-attachments/assets/12457060-b429-439a-9569-8be56027b1fa" />

>> Wafer Level Packaging And Conclusion
<img width="1037" height="303" alt="image" src="https://github.com/user-attachments/assets/7bd9adde-daa7-453f-8620-f5a43e87a231" />
<img width="1037" height="580" alt="image" src="https://github.com/user-attachments/assets/5df3a052-e7ef-41dd-8f5c-1a2173c6dd9b" />
<img width="1037" height="582" alt="image" src="https://github.com/user-attachments/assets/47b9a39a-0c07-42ae-9364-df706e8d3796" />

<img width="1042" height="594" alt="image" src="https://github.com/user-attachments/assets/a8f8aa70-5fed-4382-8255-3fce515fcea4" />



# Module 3: Lab 1: Thermal simulation of Semiconductor Packages with ANSYS
Tool - ANSYS 
simulator module- Icepak
Package selected: FlipChip package

<img width="1042" height="594" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/MODULE3.jpg" />

>> Introduction And Getting Started With ANSYS Electronics Desktop

>>     ANSYS Electronics Desktop (AEDT) is an integrated multi-physics simulation platform that unifies electromagnetic, signal integrity, thermal, and electro-mechanical analysis tools. It is extensively used for the design and evaluation of high-speed electronic circuits and complex systems.

     FLIPCHIP BGA PACKAGE
      Step 1 : Open AEDT and launch Icepak

      
<img width="1845" height="971" alt="f1" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1786).png" />
<img width="1845" height="971" alt="f1" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1787).png" />

>>      Select Flipchip BGA Package: Icepak -> Toolkit -> Geometry -> Packages -> Flipchip_BGA
<img width="821" height="601" alt="image" src="https://github.com/user-attachments/assets/7ab561a8-57c7-49d8-8f87-bf017783561d" />


>>       Package Configuration window opens up -Configure the dimensions and other aspects of the package, substrate, die, die underfill and the solder balls based on the datasheet.Once configured, click OK to generate the package model.





<img width="1034" height="564" alt="f4" src="https://github.com/user-attachments/assets/fe620e60-aef8-4101-b632-0dd5681a2df8" />


<img width="1024" height="567" alt="f5" src="https://github.com/user-attachments/assets/db174d05-f102-4d2d-b412-9c369ea248c5" />


<img width="1015" height="554" alt="f6" src="https://github.com/user-attachments/assets/2b2ff4ec-8d82-4eb5-b505-398ad3b2648d" />


>>      Package generated in Icepak


<img width="1824" height="950" alt="f8" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1788).png" />


>>      3D Package Model Structure in Icepak
>> 
<img width="1850" height="911" alt="f9" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1789).png" />


<img width="1551" height="691" alt="f10" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1790).png" />



<img width="1720" height="979" alt="f11" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1791).png" />


>>      Material Definitions And Thermal Power Sources
>>               Review and modify the material and definition types for the different components of the model.
>>               Add/ Assign Source Thermal Model for Die
                          >>     "Project Manager" sub-window, expand Thermal section and open the BGA1_die_source and configure the thermal condition
>>               Add/ Assign Source Thermal Model for Substrate
>>                               Models -> Flipchip_BGA1_Group -> Solids and assign a Thermal Source
>>              Set the thermal condition on the substrate to Fixed Temperatue and the temperature as Ambient.
>>                    Add Thermal monitors for the different components- right click on the Flipchip_BGA1_substrate under Models -> Flipchip_BGA1_Group -> Solids and then choose Assign Monitor -> Point
>>                In the sub-window that appears, select Temperature
                       Repeat the same to add thermal monitors for the die and the die-underfill

                       

<img width="1648" height="908" alt="f12" src="https://github.com/user-attachments/assets/e3642e22-b885-428d-a8ae-8b743c285978" />

<img width="1874" height="778" alt="f2" src="https://github.com/user-attachments/assets/1da39119-9ed5-43d8-9f99-35d49f6279a2" />

<img width="1920" height="1080" alt="f16" src="https://github.com/user-attachments/assets/fa5511a0-d21c-4610-a276-c9d584880735" />

<img width="1119" height="647" alt="f17" src="https://github.com/user-attachments/assets/e1b290e4-42df-412b-b9ea-789be6adfa21" />

<img width="1920" height="1080" alt="f18" src="https://github.com/user-attachments/assets/d3b6ff6e-a031-44b1-9a58-ae957b7049e9" />

<img width="1251" height="727" alt="f19" src="https://github.com/user-attachments/assets/d3b66a64-6839-4d96-b385-5721f048c8e2" />


>> Meshing And Running The Thermal Analysis
>>
>>      Generate Mesh
           Go to the Simulation tab and click on Generate Mesh
               Save the project  and wait for the mesh generation to get completed.
                  - ignore/ take steps to debug & fix the issue(s) as required.
>>      Review Mesh Quality metrics
>>           Once the mesh is generated, review the quality metrics of the generated mesh such as Face Alignment, Skewness and Volume.

<img width="1920" height="1080" alt="f20" src="https://github.com/user-attachments/assets/302a12c6-093d-49c5-9736-6152c6f81be6" />

<img width="1920" height="1080" alt="f21" src="https://github.com/user-attachments/assets/e807104d-482a-4d6e-835a-0458ad3859da" />

<img width="601" height="865" alt="f22" src="https://github.com/user-attachments/assets/829f7d89-8ddf-4f88-a297-84f63c9f822e" />

<img width="589" height="820" alt="f23" src="https://github.com/user-attachments/assets/7df401d4-21c0-4e88-ac68-dd5326a4e89a" />

<img width="603" height="814" alt="f24" src="https://github.com/user-attachments/assets/6bcdafa4-9e60-4b0a-bbc1-addd15ef284d" />


>> Add Thermal Analysis
           >>  Under Project Manager, right click on Analysis and then,
           >> select Add Analysis Setup and configure the solver settings as required.


<img width="1920" height="1080" alt="f25" src="https://github.com/user-attachments/assets/a47531a7-14c4-438f-8050-4978e8a97c41" />

<img width="1319" height="746" alt="f26" src="https://github.com/user-attachments/assets/e9a4aebb-421f-4a40-a72a-077a271acdce" />

>> Analysing Results And Exploring Other Package Types
>> 
    >>                 Run the simulation and plot the temperature map
                            Click on Analyze All button in the top ribbon
                            Wait for the simulation to get completed successfully. 
                           
            Once the simulation is completed, select the complete FC-BGA package in the 3D view by drawing a selection rectangle using the left-mouse button.
            Right click and then select Plot Fields -> Temperature -> Temperature
              Configure the different plot options:
                                                       Specify Name, Folder
                                                       Plot on Surface only
                                                       Surface Smoothing -> Enable Gaussian Smoothing

<img width="1920" height="1080" alt="f29" src="https://github.com/user-attachments/assets/36d87a58-100d-4703-85ae-ba5048b6a471" />
<img width="1920" height="1080" alt="f28" src="https://github.com/user-attachments/assets/fe3dfe55-05dd-4733-88a2-0b7b9c7b7ccd" />
<img width="1920" height="1080" alt="f27" src="https://github.com/user-attachments/assets/257218a9-7f68-48be-ab43-737a4d233b2a" />
<img width="1723" height="838" alt="f36" src="https://github.com/user-attachments/assets/0266b841-57cc-4997-b531-24abc853c8cd" />
<img width="1566" height="787" alt="f35" src="https://github.com/user-attachments/assets/7c963b12-be56-49a7-9ac1-dbfc9190efbc" />
<img width="1797" height="619" alt="f34" src="https://github.com/user-attachments/assets/9e765eb1-a6e7-4da1-83a6-11c70d9e0e14" />
<img width="772" height="565" alt="f33" src="https://github.com/user-attachments/assets/7dbe84df-eae2-409b-a8bb-092e0c961d03" />
<img width="742" height="539" alt="f32" src="https://github.com/user-attachments/assets/e2360783-d364-4176-9ffa-5470f700556c" />
<img width="1920" height="1080" alt="f31" src="https://github.com/user-attachments/assets/706ddeaf-09a4-49b0-a85d-a4dc9d33974e" />
<img width="1876" height="981" alt="f30" src="https://github.com/user-attachments/assets/98f49896-435a-416e-9745-13725b7ec920" />





>> Package: QFN Package
<img width="1920" height="1080" alt="f31" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1779).png" />
<img width="1876" height="981" alt="f30" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1780).png" />



# Module 4: Ensuring Package reliability: Testing and Performance Validation

<img width="1040" height="575" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/MODULE4.jpg" />
<img width="1040" height="575" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/15.jpg" />
>>   Introduction to Package Testing and Electrical Functionality Checks
>>       Integrated circuits (ICs) undergo testing at various stages of the manufacturing process to verify their performance, reliability, and functionality. These tests are conducted both at the semiconductor foundry and at outsourced semiconductor assembly and test (OSAT) facilities.

<img width="1040" height="575" alt="image" src="https://github.com/user-attachments/assets/996e2366-015c-4b78-aac1-191a7a664795" />

>> Foundry Testing Stages

<img width="1085" height="599" alt="image" src="https://github.com/user-attachments/assets/4e83fefb-62ab-433e-b84b-0ad06401c673" />

<img width="1064" height="578" alt="image" src="https://github.com/user-attachments/assets/a2ad14a7-c1c4-4593-b9af-94c42466592a" />

<img width="1042" height="575" alt="image" src="https://github.com/user-attachments/assets/5d14b47c-0537-4f46-b627-c0b9eb522fee" />

<img width="1059" height="587" alt="image" src="https://github.com/user-attachments/assets/1d5e57db-7b4e-42ad-a8b8-a493c952fe77" />


<img width="1039" height="583" alt="image" src="https://github.com/user-attachments/assets/820496b7-9946-4209-9c52-8a7b71fbd627" />


<img width="1055" height="581" alt="image" src="https://github.com/user-attachments/assets/28a3fc0a-09a1-43e6-8bc1-9747da509ed5" />

Summary 

<img width="849" height="439" alt="image" src="https://github.com/user-attachments/assets/4d943615-9d76-42f0-908d-e872935ab2a6" />


<img width="856" height="444" alt="image" src="https://github.com/user-attachments/assets/216d2a06-3b2e-4300-82d6-2cadbef3b0f9" />

<img width="835" height="438" alt="image" src="https://github.com/user-attachments/assets/0ccde6be-5ad3-46eb-a326-d6c8991861c6" />




# Module 5: Lab 2: Package Design and Modeling- Building a Semiconductor Package from Scratch
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/MODULE5.jpg" />
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/17.jpg" />


>> Package Design and Modelling
              Simulator module: Q3D design
>> 
>>           this lab exercise is to build the complete cross-section of a wire bond package, including die, substrate, bonding wires, and mold compound, rather than performing any simulation or analyses
>>
>>             Package Specifications:
>>                 Die - Material : Silicon
                   Dimensions : 3mm x 3mm
                   Die Height : 200 micron
                   
>>                  Substrate - Material : FR4
                            Dimensions : 5mm x 5mm
                            Height : 500 micron

  >>                 Die Attach -  Material : Modified Epoxy
                            Dimensions : 3mm x 3mm
                            Thickness : 100 micron

  >>              Die Bond Pads -Material : Copper
                              Dimensions : 0.2mm x 0.2mm
                              Thickness : 5 micron

   >>                  Substrate Bond Pads- Material : Copper
                                  Dimensions : 0.2mm x 0.2mm
                                  Thickness : 10 micron
                                  
   >>                     Bond Wire   - Material : Gold wire
                                   Type: JEDEC 4-point

  >>                 Mold Compound- Material : Epoxy
                               Thickness : 1.2mm
                                  
>> Launch AEDT and select Q3D
>> Creating the Die and Substrate in AEDT- Define the working unit
                Modeler -> Units...
                Choose mm or um as the working unit for creating the model.

<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1826).png" />
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1827).png" />

>>      Create the Die Geometry- Select the rectangle tool from the ribbon or using the Menus (Draw -> Rectangle) to draw a rectangle
                                   double click on CreateRectangle Model -> Rectangle1 to open up its Properties Dialog box.
                                     Specify the position with one corner at the origin (0, 0, 0) and the dimensions as 3mm x 3mm
                                             Select Model -> Rectangle1 and from the menu bar: Modeler -> Surface -> Thicken Sheet
                                                        ->  set the thickness to 200 microns (0.2mm)   
   >>     Assign Material Properties
                      Open -> Properties Dialog box either by double clicking on Model -> Rectangle1
                               Rename the geometry to Die
                                    Choose Silicon as the material from the Material Library

<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1828).png" />
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1829).png" />
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1830).png" />
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1831).png" />
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1832).png" />
<img width="835" height="438" alt="image" src="https://github.com/naga0381/NASSCOM-Packaging-10Oct_19Oct_2025/blob/main/Screenshot%20(1833).png" />
>>     Create the Substrate Geometry
>>               Draw another rectangle for the substrate (5mm x 5mm) and position (-1, -1, 0) it such that the die is at the center.
                 Set the thickness as -0.5mm -> the substrate lie beneath the die
                 
                 Adjust the substrate position along Z-axis to account for the die attach thickness -> (-1, -1, -0.1)

![WhatsApp Image 2025-07-10 at 4 42 37 PM (10)](https://github.com/user-attachments/assets/4a530a1d-a521-4197-9b7f-86715fe98e6f)

![WhatsApp Image 2025-07-10 at 4 42 37 PM (8)](https://github.com/user-attachments/assets/687679d0-ebc3-421b-9a44-aed46141955a)

![WhatsApp Image 2025-07-10 at 4 42 37 PM (7)](https://github.com/user-attachments/assets/a5ad8e28-dd5b-4259-9275-ce554a5dcf5e)

![WhatsApp Image 2025-07-10 at 4 42 37 PM (6)](https://github.com/user-attachments/assets/835cb817-d11a-4d79-b004-65e85c2d44e0)

![WhatsApp Image 2025-07-10 at 4 42 37 PM (5)](https://github.com/user-attachments/assets/de936e1b-fa13-494f-b45f-d195b22aac18)

>> Adding Die Attach Material and Bond Pads
>>
>>      Create the Die Attach Material: Draw a rectangle of the same size as that of the die (3mm x 3mm) and at the same co-ordinates (0, 0, 0).
             Set the thickness to -0.1mm as the die attach lies beneath the die and the substrate
         Assign the material to Modified Eopxy



![WhatsApp Image 2025-07-10 at 4 42 37 PM (4)](https://github.com/user-attachments/assets/e54b552d-3739-4c61-b686-4e152e03d629)


![WhatsApp Image 2025-07-10 at 4 42 37 PM (3)](https://github.com/user-attachments/assets/cc5e5c61-d133-40f2-b7e9-eb75f17aaa7b)

>>      Create Bond pads on Die and Substrate
          Draw a small rectangle and configure its size to to that of the die pad (0.2mm x 0.2mm) -> place the first Die Pad at the co-ordinates (0.2, 0.2, 0.2) so that it sits on top of the die and is at one of the edges. Set the thickness to  0.005mm

     Draw a small rectangle and configure its size to to that of the substrate bond pad (0.2mm x 0.2mm). Place this Substrate Bond Pad at the co-ordinates (0.2, -0.7, -0.1) so that it sits aligned to the Die bond pad created in the previous step, and also on top of the substrate. Set the substrate bond pad thickness to 10 microns (0.010mm)

  >>      Wire Bond Creation and Material Assignment
          To Create Bond Wires-> Use the Bondwire tool under: Draw -> Bondwire
            Connect the centre of the Die Bond pad to the centre of the Substrate Bond Pad
             
             Select the Bondwire type as JEDEC 4-point-> Assign gold as the Bondwire material
             repeat this  to create and connect all the die and substrate bond pads using bondwires

  >>      Applying Mold Compound and Finalizing the Package Model
>  >      Build the mold compound around the die-> Create a rectangular enclosure around the die and wires (5mm x 5mm, 1.2mm thickness)
                                                   Position at (-1, -1, -0.1) covering the top side of the substrate.
                                                   Set the thickness to 1.2mm so that it covers the die and the bondwires, while also leaving margin for any laser marking processes

![WhatsApp Image 2025-07-10 at 4 42 37 PM (2)](https://github.com/user-attachments/assets/480fd0b2-16c0-4f9b-b18a-a205e8022692)

![WhatsApp Image 2025<img width="1920" height="1080" alt="p1" src="https://github.com/user-attachments/assets/05758841-684f-4895-8205-a47e1c647fe8" />

<img width="1920" height="1080" alt="p1" src="https://github.com/user-attachments/assets/998b7cb5-69dd-42fe-883d-160bbff8037f" />

<img width="1920" height="1080" alt="p2" src="https://github.com/user-attachments/assets/bc199462-bd7d-4fb6-b0ec-b14b8770d189" />

<img width="1920" height="1080" alt="p3" src="https://github.com/user-attachments/assets/11e29b19-b58c-4c5c-af0c-14bc1c98fec9" />





>> Do the Thermal simulation as in Lab 1 using IcePak tool

>> Reference: https://www.vlsisystemdesign.com/packaging/
              https://github.com/arunkpv/Semiconductor-Packaging

# Acknowledgement

Mr. Kunal Ghosh, VSD

Prof.Tarun Agarwal, Professor-IIT Gandhinagar


