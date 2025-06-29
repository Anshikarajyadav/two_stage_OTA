# Two-Stage Operational Transconductance Amplifier (OTA)

This project implements and analyzes a **two-stage OTA (Operational Transconductance Amplifier)** using 180nm Technology
## 🧠 Objective

Design and characterize a two-stage OTA to:
- Achieve high open-loop gain.
- Provide a stable phase margin in a closed-loop configuration.
- Validate functionality with both AC and time-domain responses.

## 📁 Files Included

- `Schematic.asc`: Schematic of the OTA circuit (LTspice format).
- `report.pdf`: Contains detailed AC analysis, closed-loop gain calculation, and simulation results.

## 📈 Simulation Results

### 🔹 Open-Loop Gain
- **Magnitude**: 73.88 dB

### 🔹 Closed-Loop Gain
- **Target Gain**: 2  
- **Measured Gain**:  
  \( A = \frac{1.7560233 - 1.755550}{0.0002} = \mathbf{2.36} \)

### 🔹 Phase Margin
- \( PM = 180^\circ - 76.257^\circ = \mathbf{103^\circ} \)

### 🔹 Step Response
- Step input: 0.2 V (rise/fall time = 0.1 ns)
- Response demonstrates stability and expected settling behavior.

## 🛠 Tools Used

- **LTspice** for circuit design and simulation
- Basic AC analysis and transient simulation techniques

## 📚 Author

**Anshika Raj Yadav**  
Roll No: 230102111  
IIT Guwahati

