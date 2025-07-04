# Session Notes - 4th June 2025

## Overview
A technical session covering software installation and a project case study focused on mitigating energy loss at Multimedia University of Kenya.

## Agenda
- Software Installation & Configuration  
- Introduction to SLD and MLD diagrams  
- Case Study Discussion: Energy Loss Mitigation  
- Custom Device Symbols and Engineering Concepts

## Key Topics
1. **Software Installation:**  
   - [Steps to install](https://github.com/plochoidysis-ojwege/Industrial-Panel-Design/tree/main/Documentation/Software%20setup)  
   - The property window- after a successful installation, launch the application to take you to the property window.
     When an object (e.g., a symbol, a device, a page) is selected, this window displays all its editable properties. This includes technical data, display settings, cross-references, e.t.c. 
Other key UIs were also discussed e.g., Page Navigator, Device Navigator, Graphic Editor, Symbol Selector, Project Explorer, Message Management and more , but for this , the main focus was on the property window.
2. **Project Case Study:**
At this point ,a proposal was made for a sample project. That was inspired by the fact that there is always power loss in certain scenarios where consumers might leave some sockets or extensions ON when they are not at use . This leads to power loss.Specifically , the focus was on Multimedia University of Kenya - where students are ignorant and do not care to switch off the switches and even forget to switch off the lights during day time (if so , things aught to be automatic to save the energy, to save the cost of electricity and invest on more mordern labs instead)
   - Objective: Design a project to mitigate energy loss through automatic lighting control panel - This aims to ensure lights are only active when and where needed, based on occupancy and ambient light levels.
   - Key elements:
     -   Panel Design: Creating detailed schematics for the control panels housing relays, contactors, and control circuitry.
     - Use of CTs and their importance: Their primary role would be for measurement and verification of the energy savings
     - Device Selection: Specifying energy-efficient lighting fixtures (e.g., LED luminaires) and appropriate control gear (e.g., dimmable drivers, smart relays)

4. **Diagrams & Schematics:**  
   - Sample SLD Diagram:  
     ![sld](https://github.com/plochoidysis-ojwege/Industrial-Panel-Design/blob/main/Documentation/images%20for%20the%20session%20notes/sld.png)

   - Sample MLD Diagram:  
   ![mld](https://github.com/plochoidysis-ojwege/Industrial-Panel-Design/blob/main/Documentation/images%20for%20the%20session%20notes/mld.jpg)

5. **Technical Discussions:** 
   
  - # Differences Between MCB and MCCB

Miniature Circuit Breakers (MCBs) and Molded Case Circuit Breakers (MCCBs) are switches .Their workings are very similar, but they do have several differences.

---

## Difference Between MCB and MCCB
![Miniature Circuit Breaker](https://github.com/plochoidysis-ojwege/Industrial-Panel-Design/blob/main/Documentation/images%20for%20the%20session%20notes/difference%20between%20MCCB%20and%20MCB.webp)
.*

| **Point of Difference**       | **MCB**                                                                 | **MCCB**                                                                 |
|-------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **Full Form**                 | Miniature Circuit Breaker                                              | Moulded Case Circuit Breaker                                           |
| **Definition**                | An automatic electrical switch designed to protect low-voltage circuits and appliances from overcurrent and short circuits | A circuit breaker that protects higher current circuits from electrical overloads and short circuits |
| **Current Rating**            | Usually up to 125A                                                    | Typically ranges from 16A to 1600A                                     |
| **Short Circuit Time**        | Faster turn-around time (milliseconds)                                | Slower turn-around time (milliseconds to seconds)                      |
| **Short Circuit Current Rating** | Lower short circuit current ratings, up to 15kA                     | Higher short circuit current ratings, often up to 100kA                |
| **Remote Operation**          | Usually not equipped with remote operation capabilities               | May have remote operation options for opening and closing the circuit breaker |
| **Interrupting Current Rating** | Lower interrupting capacity compared to MCCBs, often up to 1800A      | Higher interrupting capacity, suitable for more demanding applications, often going up to 200kA |
| **Number of Poles**           | Usually 1, 2, or 3-poles                                              | Typically 3-poles (some models may have 4-poles)                       |
| **Trip Circuit**              | Fixed tripping circuits                                               | Movable tripping circuits                                              |
| **Trip Characteristics**      | Fixed, non-adjustable trip characteristics, generally suitable for general-purpose applications | Adjustable or fixed trip characteristics, suitable for various applications and coordination needs |
| **Applications**              | Residential, commercial, and light industrial applications that require lower current requirements | Industrial, commercial, and heavy-duty applications that require higher current ratings and better protection capabilities |

---

## Working Mechanism

### MCB
MCB automatically turns off during abnormal conditions, like electrical surges and extremely high voltage conditions. When the amount of electricity flowing through the live circuit is high, it disconnects the circuit to stop the flow of electricity. It can also detect short circuits and breaks the circuit, thereby stopping an electrical surge to appliances and preventing electrocutions.

### MCCB
MCCBs, on the other hand, prevent overloading and overheating of the electrical circuit. It contains **bimetallic components** which expand and contract as a response to overloading within a circuit. Under normal conditions, the MCCB allows an open flow of electricity, but an overload in the circuit heats the MCCB. This causes the bimetallic components to prevent the flow of electricity until the overload subsides, allowing the MCCB to cool down.

Unlike MCBs, MCCBs can be remotely operated by shunt wires.

---



   - What makes motors rotate (or not) in two phases
   - Generator ratings in kVA and conversion using [rapid tables](https://www.rapidtables.com/calc/electric/kVA_to_Amp_Calculator.html) 
   - [Summary of key engineering standards](https://github.com/plochoidysis-ojwege/Industrial-Panel-Design/tree/main/Resources/Standards_Excerpts)
