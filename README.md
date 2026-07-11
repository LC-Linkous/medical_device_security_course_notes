# Medical Device Security Course Notes

A collection of notes, examples, and student work samples from undergraduate course(s) I teach out of a medical device themed testbed.

Initial material is being added for the release of the publication at the 2026 ASEE Annual Conference & Exposition in Charlotte, NC. Several publications will follow in late 2026.

## Introduction

This repository hosts teaching material for an undergraduate course built around a medical device security testbed. The goal is to give students hands-on experience with device security concepts through a physical testbed and applied, project-based work. The notes, code examples, and student work samples collected here support a broader effort connecting classroom instruction to practical engineering skills and workforce development.

Content is released incrementally throughout the Spring 2026 semester alongside a series of related publications. Check back as new modules and materials are added.

### Facilities

The course runs out of a dedicated medical device security testbed at the VCU College of Engineering, part of the Commonwealth Cyber Initiative's Central Virginia Node. The testbed investigates the cybersecurity of medical devices — from patient monitors and infusion pumps to wearables and connected hospital equipment — across three research thrusts: offensive security (penetration testing of commercial devices), secure-by-design analysis, and machine learning applied to device data. The lab runs entirely on an isolated, air-gapped network so that testing stays fully contained.

#### Equipment

The testbed includes 40+ medical devices and 60+ commercial tools spanning several categories:

- **Portable devices:** patient monitors, CPAP machines, syringe/infusion pumps, ECG units
- **Stationary devices:** ultrasound, Wi-Fi hospital beds, IoT devices and baby monitors
- **Wearables:** blood-oxygen finger clips, heart-rate monitors, and at-home health devices
- **Research tools:** commercial-grade penetration testing platforms, software-defined radios (SDRs), wireless & RF security analysis gear, board-level debug interfaces, wired and wireless protocol analyzers, oscilloscopes and function generators, power supplies and voltmeters, and a hardware reverse-engineering bench

#### Network

The lab is built on an air-gapped network with no connection to the outside world. A firewall/router segments the environment into isolated zones — research workstations for analysis and machine learning, the medical devices under test, and a server hosting virtual test environments and device-data storage — with each zone walled off from the others. Guests connect to a separate isolated segment that cannot reach any of the test zones. This segmented design lets students work hands-on with real devices while keeping every experiment contained.

## Modules

The following modules are planned for inclusion. This list will be updated as material is released:

- **Module 0:** Reading a Research Paper
- **Module 1:** Arduino Traffic Light State Machine
- **Module 2:** Serial Debug & Interfacing (Introduction)
- **Module 3:** Firmware Extraction (Process Introduction)
- **Module 4:** Bash, Boot & Abstraction Layers
- **Module 5:** JTAG Interfacing & Pin Identification
- **Module 6:** Device Disassembly & Hardware Analysis
- **Module 7:** Wireless Communication & SDRs
- **Module 8:** Simulate & Build a Patch Antenna
- **Module 9:** Machine Learning for RF/Device Data

## How to Use This Material

Each module is divided into 2–5 units depending on its complexity. Some introductory modules are meant to take as little as one week, while some complex modules may take 4–5 weeks.

Units within each folder contain a README of topics, resources, and lists of hardware. Included in the modules are code, diagrams, student handouts, tutorials of student projects, and samples of student work (where applicable and when permission was given to share). The modules also include references to other tools, courses, and reference materials useful for editing the material to incorporate into existing course units, or for building new units from scratch.

## Related Resources and Publications

### Publications

1. L. Linkous, E. Karincic, M. Suche, and E. Topsakal, "Reinforcement learning controlled mechanically reconfigurable antennas," in *2025 USNC-URSI National Radio Science Meeting (NRSM)*, Boulder, CO, USA, 2025, pp. 61–62, doi: [10.23919/USNC-URSINRSM66067.2025.10907084](https://doi.org/10.23919/USNC-URSINRSM66067.2025.10907084).

2. E. Karincic, L. Linkous, and E. Topsakal, "From classroom to career with practical network training," in *2024 ASEE Annual Conference & Exposition*, Portland, OR, USA, Jun. 2024. [Online]. Available: [https://peer.asee.org/47479](https://peer.asee.org/47479)

3. L. Linkous and E. Topsakal, "Machine learning assisted optimization methods for automated antenna design," in *2024 USNC-URSI National Radio Science Meeting (NRSM)*, Boulder, CO, USA, 2024, pp. 377–378, doi: [10.23919/USNC-URSINRSM60317.2024.10464597](https://doi.org/10.23919/USNC-URSINRSM60317.2024.10464597).
   *Note: 60k antennas simulated; dataset released for students to learn ML techniques for RF.*

4. E. Karincic, E. Topsakal, and L. Linkous, "Patch antenna calculations and fabrication made simple for cyber security research," in *2023 ASEE Annual Conference & Exposition*, Baltimore, MD, USA, Jun. 2023. [Online]. Available: [https://peer.asee.org/43974](https://peer.asee.org/43974)

5. L. Linkous, E. Karincic, and E. Topsakal, "Teaching device security through physical testbeds: A hands-on approach to engineering education and workforce development," in *2026 ASEE Annual Conference & Exposition*, Charlotte, NC, USA, Jun. 2026.

6. E. Karincic, L. Linkous, and E. Topsakal, "Classroom approaches to RF education with visual-based modulation recognition labs," in *2026 ASEE Annual Conference & Exposition*, Charlotte, NC, USA, Jun. 2026.

7. E. Karincic, L. Linkous, and E. Topsakal, "Experiential radio frequency engineering education with machine learning focused signal processing labs," in *2026 ASEE Annual Conference & Exposition*, Charlotte, NC, USA, Jun. 2026.

### Publication Repositories

- [Reinforcement Learning Controlled Reconfigurable Antennas (2025 URSI)](https://github.com/LC-Linkous/2025_URSI_RL_Reconfigurable_Antennas)
- [Practical Network Training / CML Labs (2024 ASEE)](https://github.com/Dollarhyde/cml-labs)
- [ML Assisted Antenna Design (2024 URSI NRSM)](https://github.com/LC-Linkous/2024-URSI-NRSM-1265)
- [Antenna Calculator (2023 ASEE)](https://github.com/Dollarhyde/AntennaCalculator)

### Public Software & Packages

This section includes publicly published software created explicitly to support this course and similar courses.

#### Hardware Control and Interfacing

- [tsapython](https://pypi.org/project/tsapython/)
- [nvnapython](https://pypi.org/project/nvnapython/)
- [hackrfpy](https://pypi.org/project/hackrfpy/)

### Our Supporting Projects

- [Cryptography Examples](https://github.com/LC-Linkous/cryptography_examples)
- [Computer Vision Notes](https://github.com/LC-Linkous/computer_vision_notes)
- [Data Interfacing Demo](https://github.com/LC-Linkous/data_interfacing_demo)
- [Kalman Filter](https://github.com/LC-Linkous/kalman_filter)
- [Reverse Engineering Notes](https://github.com/LC-Linkous/reverse_engineering_notes)
- [Research Antenna Collection](https://github.com/LC-Linkous/research_antenna_collection)

## How to Cite

If you use this material, please cite:

> L. Linkous, E. Karincic, and E. Topsakal, "Teaching device security through physical testbeds: A hands-on approach to engineering education and workforce development," in *2026 ASEE Annual Conference & Exposition*, Charlotte, NC, USA, Jun. 2026.

```bibtex
@inproceedings{linkous2026teaching,
  author    = {Linkous, L. and Karincic, E. and Topsakal, E.},
  title     = {Teaching Device Security Through Physical Testbeds: A Hands-on Approach to Engineering Education and Workforce Development},
  booktitle = {2026 ASEE Annual Conference \& Exposition},
  address   = {Charlotte, NC, USA},
  month     = jun,
  year      = {2026}
}
```

## License

This material is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). You are free to share and adapt it for non-commercial purposes with appropriate credit. See the [LICENSE](LICENSE) file for full terms.

This repository is a personal archive of the author's own course material and is not open to outside contributions at this time.