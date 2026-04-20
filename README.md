## bioimpedance-adulteration-detection
Milk Adulteration Detection Simulation-based milk adulteration detection using electrical bioimpedance. Models milk as an RC biocell and extracts Cole–Cole parameters (R₀, R∞, τ, α) to classify pure vs adulterated samples (water, urea, starch) in a non-destructive, low-cost way.

---

## Overview

Milk adulteration is a major food safety issue. Traditional detection methods are:
- Time-consuming  
- Expensive  
- Laboratory-dependent  

This project provides a **non-destructive, low-cost simulation approach** to detect adulteration using electrical properties of milk.

---

## Methodology

1. **Modeling**
   - Milk is represented as an **RC biocell equivalent circuit**

2. **Frequency Analysis**
   - AC signal applied across multiple frequencies

3. **Impedance Calculation**
   - Complex impedance computed from voltage/current

4. **Cole–Cole Modeling**
   - Extract key parameters:
     - R₀ → Low-frequency resistance  
     - R∞ → High-frequency resistance  
     - τ → Relaxation time constant  
     - α → Dispersion coefficient  

5. **Classification**
   - Compare parameters to identify:
     - Pure milk  
     - Water adulteration  
     - Urea adulteration  
     - Starch adulteration  

---

## Key Features

- Non-destructive testing  
- No chemical reagents required  
- Simulation-based (MATLAB/Simulink)  
- Distinct electrical signatures for each adulterant  
- Scalable for hardware implementation  

---

## Results

- Pure milk shows stable impedance behavior  
- Water increases resistance (dilution effect)  
- Urea decreases resistance (higher conductivity)  
- Starch increases relaxation time (structural complexity)  

Each adulterant produces a **unique impedance signature**, enabling reliable classification.

---

## Tools & Technologies

- MATLAB  
- Simulink  
- Electrical Bioimpedance Modeling  
- Cole–Cole Analysis  

---

## Future Scope

- Hardware implementation using sensors  
- Real-time embedded systems  
- Integration with machine learning  
- Expansion to other food products  

---

## Project Structure


 bioimpedance-adulteration-detection
┣  images
┣  README.md
┣  simulation_files
┗  results


---

## Authors

- Abhinav Racha Battuni  
- Sanjana Aathreya  
- Kashvi Sharma  
- Praveen Kumar Gupta  

---

## Institution

RV College of Engineering (RVCE)  
Visvesvaraya Technological University (VTU)

---

## References

1. Schwan, “Electrical properties of tissue,” 1957  
2. Peres et al., IEEE Sensors Journal, 2016  
3. Lee et al., Computers & Electronics in Agriculture, 2021  
4. Grimnes & Martinsen, Bioimpedance Basics  
5. Cole & Cole, 1941  

---


- GitHub: https://github.com/abhinavrach
- Repository link: (https://github.com/abhinavrach/bioimpedance-adulteration-detection)
