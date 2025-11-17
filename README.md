
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**
![WhatsApp Image 2025-11-17 at 21 56 08_02f3e8c0](https://github.com/user-attachments/assets/35e14a6b-b25e-42b6-8635-13afacc25747)


---

## Graphs

<img width="1912" height="1100" alt="513039598-566a99a6-5102-48bc-9e9a-da70cd664c39" src="https://github.com/user-attachments/assets/a9ed59e3-1f16-4dcf-805b-cdc4b239997c" />
<img width="1909" height="975" alt="513040432-c07e2dac-efe7-420a-9ce3-c07f8af41f87" src="https://github.com/user-attachments/assets/8c3b67a1-f017-407f-8923-eeea830e727c" />
<img width="1919" height="980" alt="513040666-e25a0844-1a26-4026-aad6-9584f15d2a96" src="https://github.com/user-attachments/assets/09112fc7-349f-44c3-b072-592d807d98b2" />

## RESULT

The optical communication system was successfully simulated using OptiPerformer. As the fiber length increased from 50 km to 150 km, the following trends were observed:

Received optical power decreased due to fiber attenuation.
Q-factor gradually decreased, indicating signal quality degradation.
Bit Error Rate (BER) increased with distance, showing higher error probability.
The eye diagram became more closed at longer fiber lengths, confirming dispersion and noise effects.
Hence, the simulation verified that optical signal performance deteriorates with increasing fiber length due to attenuation and dispersion losses.
