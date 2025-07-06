# Analog IC Design Projects in Cadence

This repository contains the design files, simulation results, and documentation for three analog integrated circuit (IC) design projects implemented using Cadence in a 45nm CMOS technology. The projects include:

- **Three Current-Mirror Operational Transconductance Amplifier (OTA)**
- **Fully Differential 3GHz LC Voltage-Controlled Oscillator (LC-VCO)**
- **Phase-Frequency Detector and Charge Pump (PFD-CP) Type-II Fractional-N Phase-Locked Loop (PLL)**

## Overview

These projects were developed to meet specific performance specifications, addressing challenges in modern analog circuit design. The designs utilize the \(g_m/I_D\) methodology, careful transistor sizing, and simulation-driven optimization to achieve robust performance.

### Project Details

1. **Three Current-Mirror OTA**
   - **Objective**: Maximize Gain Bandwidth Product (GBW) with DC gain ≥40dB and unity gain frequency ≥20MHz.
   - **Key Features**: Two-stage single-ended symmetric design, self-biased inverters, and current mirrors.
   - **Specifications**: Supply voltage 1V, power consumption ≤1000µW, slew rate >10V/µs, phase margin >45°.

2. **Fully Differential 3GHz LC-VCO**
   - **Objective**: Achieve a center frequency of 3GHz with low phase noise and power consumption.
   - **Key Features**: Cross-coupled NMOS and PMOS stages, MOS varactors, and symmetric inductor.
   - **Specifications**: Supply voltage 1V, tuning range ±10%, phase noise minimized.

3. **PFD-CP Type-II Fractional-N PLL**
   - **Objective**: Enable clock generation or frequency synthesis with a 3–5GHz VCO range.
   - **Key Features**: Tri-state PFD, charge pump, low-pass filter, ring VCO, and delta-sigma modulator.
   - **Specifications**: Supply voltage 1V, lock time <1µs, loop bandwidth 1MHz, power consumption ≤10mW.

## Repository Structure

- `ota/`: Files related to the Three Current-Mirror OTA design, including schematics and simulation data.
- `lc-vco/`: Files related to the Fully Differential 3GHz LC-VCO design, including layout and simulation results.
- `pll/`: Files related to the PFD-CP Type-II Fractional-N PLL design, including netlists and performance logs.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/analog-ic-design-projects.git
   ```
2. Open the project files in Cadence with the 45nm CMOS technology library.
3. Run simulations using the provided netlists and verify results against the specifications.

## Prerequisites

- Cadence Virtuoso or compatible EDA tool.
- 45nm CMOS process design kit (PDK).
- Basic knowledge of analog IC design and simulation workflows.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
