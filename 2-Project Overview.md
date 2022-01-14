# 2 Project Overview

The Heliospheric Environmental and Radiation Measurement Experiment Suite (HERMES) is an external payload that will fly with the first two Gateway modules in their Near Rectilinear Halo Orbit (NRHO) at the Moon. Particle detectors and magnetometers will monitor in-situ space weather for purposes of scientific research and as a step toward development of systems capable of providing alerts and predictions in support of human exploration.

The Moon’s space environment is alternately dominated by the extended magnetosphere of Earth and by the highly variable outer atmosphere of the Sun (the “heliosphere”). Thus, the lunar plasma environment offers unique opportunities to study a variety of fundamental plasma physics processes that have application to many other objects throughout the universe.

## 2.1 Science Goals and Objectives

HERMES addresses scientific goals and objectives that leverage its unique orbit in coordination with other Heliophysics System Observatory (HSO) missions:

Goal A: Determine mechanisms of solar wind mass and energy transport.
* Objective A1: Determine effects of large-scale structures on plasma transport and particle energies within the solar wind.
* Objective A2: Determine effects of small-scale structures on plasma transport and particle energies within the solar wind.

Goal B: Characterize energy, topology, and ion composition in the deep magnetotail.
* Objective B1: Determine structure and dynamics of the magnetotail at lunar orbit.
* Objective B2: Quantify energy content of the magnetotail at lunar orbit.
* Objective B3: Quantify transport of atmospheric ions.

Goal C: Establish observational capabilities of an on-board pathfinder payload measuring local space weather to support deep-space and long-term human exploration.
* Objective C1: Assess the effects of field of view limitations associated with accommodation on Gateway.
* Objective C2: Assess interference with measurements due to electric currents and surface charging.

Level-1 Science Requirements that must be satisfied to achieve these objectives can be found in the Program Level Requirements Appendix (PLRA).

The HERMES project shall be considered successful if:
* HERMES achieves lunar orbit, completes commissioning, and subsequently returns data with 80% coverage of the magnetotail and 80% coverage of the solar wind over a period of six months.
* Physical parameters derived from the observations are made available in a public mission archive for use by the scientific community.

## 2.2 Science Instrumentation
To address the scientific objectives, the HERMES instrument suite obtains measurements of the cis-lunar plasma environment including magnetic fields and electrically charged particles (electrons and ions) using the following four instruments:
* Electron Electrostatic Analyzer (EEA), PI Dr. Daniel Gershman, NASA GSFC: The EEA provides measurements of low-energy electrons in the solar wind and in Earth’s deep magnetotail by measuring electron flux as functions of energy and direction.
* Miniaturized Electron pRoton Telescope (MERiT), PI Dr. Shrikanth Kanekal, NASA GSFC: The MERiT instrument measures the flux of high-energy electrons and ions with two telescopes pointing in opposite directions and nominally spanning the forward and reverse Parker Spiral
* Noise Eliminating Magnetometer Instrument in a Small Integrated System (NEMISIS), Dr. Eftyhia Zesta, NASA GSFC; Co-I Dr. Mark Moldwin, University of Michigan: NEMISIS is comprised of a fluxgate magnetometer (M0) at the end of a deployable boom and two inductive magnetometers (M1, M2) mounted on the HERMES platform. Each sensor measures the vector magnetic field at its location. Measurements from the 3 sensors are combined to reduce the contribution to the local field due to Gateway.
* Solar Probe Analyzer for Ions (SPAN-i), PI Dr. Roberto Livi, The University of California, Berkeley, Space Sciences Laboratory (SSL): The SPAN-i ion sensor measures Interplanetary and Magnetotail ion flux as functions of direction and energy/charge from several eV/q to 20 keV/q. A time-of-flight section enables it to sort particles by their mass/charge ratio, permitting differentiation of ion species.

Table 2-1. HERMES Instruments
| Instrument | Measurement | Range | Field of View | Cadence | Provider/PI |
|------------|-------------|-------|---------------|---------|-------------|
|EEA (low energy electron spectrometer) | Electron Velocity Distribution |1 eV – 30 keV in 64 steps, dE/E = 0.20 |360 deg parallel to HERMES base plate, 22.5 deg resolution | 1.0 s | NASA GSFC/ Daniel Gershman |
| MERiT (Energetic electron and proton telescope) | Proton and Electron Flux |Protons: 1 – 190 MeV, 20 bins, dE/E = 0.3 Electrons: 0.3 – 9 MeV, 11 bins, dE/E = 0.3 | 120 deg conical sunward and 120 deg conical anti-sunward | 1.0 s | NASA GSFC/ Shri Kanekal |
| NEMISIS (fluxgate and inductive magnetometers) | Magnetic Field Vector | Fluxgate: +/-65,000 nT Inductive: +/-100,000 nT | Not Applicable | 0.1 s | NASA GSFC/ Eftyhia Zesta|
| SPAN-i (low energy ion mass spectrometer) | Ion Velocity Distribution (mass/charge resolved) |2 eV – 20 keV, 64 steps, dE/E = 0.16 | 247.5 deg perpendicular to HERMES base plate, ±45 deg out of plane | 0.218 s | U.C. Berkeley/ Roberto Livi|

The instrument suite is supported by the Interface Control Electronics (ICE) Box which hosts the platform’s command and data handling system (C&DH), power converter, power switching boards and other electronics. The ICE Box provides power for the instruments and it is the interface with Gateway for command uplink, science data downlink, and instrument housekeeping (HK) downlink. The ICE Box also has the ability to store and forward data. This is in addition to Gateway’s capability to store data. The ICE Box provides time synchronization to the instruments, and forwards commands received from the Gateway to the instruments (Figure 2-1).

## 2.3 Mission Concept
HERMES takes advantage of an opportunity to conduct space-weather research from Gateway. The initial Gateway modules, the Power and Propulsion Element (PPE) and the Habitation and Logistics Outpost (HALO), will be launched into Earth orbit on a SpaceX Falcon Heavy rocket. Launch is projected to be no earlier than November 2024. The transit to lunar orbit will be accomplished using the PPE’s 50 kW Solar Electric Propulsion (SEP) subsystem. Transit time will be approximately 1 year. As the modules approach cis-lunar space they will transition to a lunar Near Rectilinear Halo Orbit (NRHO). The orbital period will be 7 days. Apoapsis will be 70,000 km above the Moon’s south pole, and periapsis at altitude ~3,000 km above the north polar regionThe NRHO is a solution to the 3-body Earth-Moon-Gateway orbit problem. A characteristic feature is the fact that the normal to the orbit plane is always pointed toward Earth. Thus the orbit appears as an eccentric halo as viewed from Earth.

The HERMES Payload (HP) is hosted on the HALO (Figure 2-2). Initial activation of the HP will occur shortly after launch. A 30-day commissioning period occurs when Gateway achieves lunar orbit. Mission Science Objectives will be accomplished during the 2 years of Phase E operations that follow. Dependent on the radiation and thermal environments, there may be opportunities to conduct targeted science investigations prior to arrival at the moon, but all Science Objectives can be accomplished entirely from lunar orbit.

While in lunar orbit, Gateway will be in the solar wind for about 75% of the time as it follows the Moon about Earth. The remaining time will be spent in traversal of the terrestrial magnetotail from the dusk side to the dawn side. Gateway is expected to arrive at the moon and commence Phase-E science operations near the time of the sunspot maximum for Solar Cycle 25.

