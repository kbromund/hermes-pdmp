# 4 Data Products

## 4.1 Data Level Definitions
### 4.1.1 NASA Science Mission Directorate (SMD) Defined Levels
In anticipation of the proposed July 2021 revision of the SMD Scientific Information Policy, HERMES will utilize Data Level Definitions given below in Table 4-1.

Table 4-1. NASA SMD Data Level Definitions
|Data Level|Description|
|-|-|
|0|Unprocessed instrument and payload data at full resolution, with any and all communications artifacts (e.g., synchronization frames, communications headers, duplicate data) removed. This level of data may only be available upon request.|
|1|Reconstructed, unprocessed instrument data at full resolution, time-referenced, and annotated with ancillary information. This level of data will be in a standard format that is accessible.|
|2|Data that has been processed to remove instrument or sensor effects.|
|3|Data that has been mapped on to a uniform space-time grid, resampled, or combined to produce a set of data with greater completeness and consistency.|
|4|Products delivered as part of a Mission derived from data. This could include model outputs, analysis of results, catalogs, or databases derived from Mission data.|

## 4.1.2 HERMES Project Defined Data Levels
Additionally, HERMES will produce two levels of data not incorporated in the SMD Data Level hierarchy.

Quicklook (QL) data products will be produced and released through the SDC within 1 day of delivery of telemetry by the HOSC to the MOC. These products will be similar in nature to data products at Levels 2 and 3, but quality is not validated prior to release, algorithms for production may be simplified, and the data products do not benefit from calibration updates employed in production for Levels 2 and 3. QL data are useful for identification and evaluation of changes in instrument performance. They are suitable for identification of events or regions encountered by Gateway and therefore will be valuable as an early guide for scientific research. QL data are not approved by the HERMES Project for publication. Publications should rely on Level-2 and Level-3 data products which are validated by the instrument teams within one month of receipt of telemetry and supersede any information provided in QL files.

Auxiliary data include calibration data and other parameters that the HERMES Project utilizes in production of data at Levels 2 and 3. They can be used for independent validation of HERMES data products.

Table 4-2. HERMES Project Data Definitions
| Data Level | Description |
|-|-|
|Quicklook (QL)|Processed but unvalidated data products that can be used to evaluate instrument performance and as an early guide for research. These may be similar to products at Level 2 or Level 3. However, they do not utilize improvements to calibrations developed for Levels 2 and 3 data, and may utilize simplified production algorithms. The HERMES Project does not approve the use of Quicklook data for scientific publication.|
|Auxiliary (Aux)| Calibration factors and other instrument-related factors required for production of Level-2 and Level-3 data from Level 1 data.|

### 4.1.3 Schedule for Release of Data
An initial release of data to the public will occur as soon as is practical for data at Levels 1 and 2, and not later than 6 months after completion of commissioning. Subsequent releases will be monthly. Once data have been delivered by the HOSC to the MOC, the Level-1 and Quicklook data products will be updated within one day. Data at Level 3 will be updated monthly, once algorithms have been developed, verified, and validated. Level-4 data products will be added to the SDC as they become available. All data will be accessible by the public without restriction via the SDC interface, with the exception of Level-0 data. It is not anticipated that users will have need of Level-0 data. Level-0 data will be made available upon request.

Table 4-3. Data Release Schedule. Following Level-0 receipt by the SOC from the  MOC.
| Data Level | Public Release |
|-|-|
|0|Upon Request|
|1|Daily|
|2|Monthly|
|3|Monthly|
|4|Upon Receipt|
|Quicklook|Daily|
|Auxiliary|Monthly|

## 4.2 Data Formats
The SDC will produce and distribute data in the Common Data Format (CDF) utilized by NASA’s Space Physics Data Facility for archival of Heliophysics data.

## 4.3 HERMES Data Products

Table 4-4. EEA Data Products
|Data Level | Product | Description |
|-|-|-|
|1|3D Count Distributions|Counts in 256 energy-deflection steps x 32 azimuth position counters at 12 bits and at 1 second cadence|
|1|1D Count Distributions|Counts in 256 energy-deflection steps x 2 total event counters at 16 bits and at 1 second cadence|
|2|3D Phase Space Densities|Validated electron phase space densities (s3 cm-6) in 256 energy-deflection steps x 32 azimuth position counters at 12 bits and at 1 second cadence. Utilizes latest updates to sensor calibration factors.|
|3|Moments of the Electron Phase Space Distribution|Electron Density, Speed, and Temperature derived from the Level-2 Phase Space Densities and corrected for spacecraft potential|
|3|Spacecraft Potential|Potential of the EEA instrument relative to the surrounding plasma|
|3|2D electron energy-pitch-angle distributions|Combined with magnetic field measurement to produce 2D energy-pitch-angle distributions|
|4|TBD|TBD|
|QL|3D Phase Space Densities (Unvalidated)|As in Level 2, but unvalidated and computed using preliminary sensor calibration factors|
|QL|Moments of the Electron Phase Space Distribution (Unvalidated)|As in Level 3, but computed from the Quicklook Phase Space Densities and not validated|
|QL|Spacecraft Potential (Unvalidated)|Unvalidated Potential of the EEA instrument relative to surrounding plasma|
|Auxiliary|TDB||

Table 4-5. NEMISIS Data Products
|Data Level | Product | Description |
|-|-|-|
|1|Vector Magnetic Field from 3 sensors (M0, M1, M2) in spacecraft coordinates|CCSDS, each packet is 4-sec long at 10 Hz rate, 3-axis magnetic field components for all three sensors in coordinate system native to the HERMES Payload|
|1|Sensor Temperatures|Temperatures at M0, M1, M2
|1|Housekeeping Flags|TBD|
|2|Vector Magnetic Field from 3 sensors (M0, M1, M2) in GSE coordinates|3d vector magnetic fields (Bx, By, Bz) in nT for each magnetometer (M0, M1, M2) using final calibrations for offsets and gains
|Sensor Temperatures|final values for temperatures in
|3|Magnetic field at Gateway|Background-subtracted and processed 3d vector magnetic field (Bx, By, Bz) in nT in a common coordinate system (e.g. GSE). Derived by combining individual sensor data.|
|4|TBD|
|QL|Vector Magnetic Field from 3 sensors (M0, M1, M2) in GSE coordinates (Unvalidated)|Despiked values for 3d vector magnetic fields (Bx, By, Bz) in nT for each magnetometer (M0, M1, M2) in their local coordinate system, plus temperatures in Celsius for each sensor. (and time-corrected and time-checked)
|Auxiliary|TDB||

Table 4-6. MERiT Data Products
|Data Level|Product|Description|
|-|-|-|
|1|Counts|Raw time-ordered instrument data for each differential channel (x31) binned data in energy ranges, number of times that detector exceeded a threshold anything that triggers a thresholds singles counts (x16)
|1|Pulse Heights|Pulse Height of triggers above threshold ( particles events raw events pulses) checksum validated|
|2|Electron Energy Spectra|Electron spectra in physical units|
|2|Proton Energy Spectra|Proton spectra in physical units|
|3|TBD||
|4|TBD||
|QL|Counts|Same as Level 1 but deadtime corrected|
|Auxiliary|TDB||

Table 4-7. SPAN-i Data Products
| Data Level | Product | Description |
|-|-|-|
|1|H+ Counts|32 Energies x 8 Deflections (256 HV step) x 16 Anodes every 0.87s (may be compressed)|
|1|He++ Counts|32 Energies x 8 Deflections (256 HV step) x 16 Anodes every 0.87s (may be compressed)|
|1|O+ Counts|32 Energies x 8 Deflections (256 HV step) x 16 Anodes every 0.87s (may be compressed)|
|2|H+ Flux|Differential Energy Flux [cm-2 sr-1 s-1 eV/eV] in units of eV/Q, elevation angle, and azimuthal angle. Preliminary calibration applied.|
|2|He++ Flux|Differential Energy Flux [cm-2 sr-1 s-1 eV/eV] in units of eV/Q, elevation angle, and azimuthal angle. Preliminary calibration applied.|
|2|O+ Flux|Differential Energy Flux [cm-2 sr-1 s-1 eV/eV] in units of eV/Q, elevation angle, and azimuthal angle. Preliminary calibration applied.|
|3|H+ Moments|H+ Density, Velocity, Temperature|
|3|He++ Moments|H++ Density, Velocity, Temperature|
|3|O+ Moments|O+ Density, Velocity, Temperature
|4|TBD||
|QL|H+ Flux (Unvalidated)|Same as Level 2, but preliminary calibration applied|
|QL|He++ Flux (Unvalidated)|Same as Level 2, but preliminary calibration applied
|QL|O+ Flux (Unvalidated)|Same as Level 2, but preliminary calibration applied
|QL|H+ Moments (Unvalidated)|Same as Level 2, but preliminary calibration applied
|QL|He++ Moments (Unvalidated)|Same as Level 2, but preliminary calibration applied
|QL|O+ Moments (Unvalidated)|Same as Level 2, but preliminary calibration applied|

## 4.4 HERMES Data Volumes

Table 4.8 indicates the expected daily data volumes for each HERMES science investigation.

Table 4-8. Estimated Data Volumes in GB
| Instrument | Raw | Level-0 | Level-1 | Level-2 | Level-3 | Total |Total over 2 years|
|-|-|-|-|-|-|-|-|
|EEA|0.21|0.21|1.12|3.4|TBD|6|4400|
|MAG|0.21|0.21|1.12|3.4|TBD|6|4400|
|MERiT|0.21|0.21|1.12|3.4|TBD|6|4400|
|SPAN-i|0.21|0.21|1.12|3.4|TBD|6|4400
|ICEBox|1.03||||
|Total|0.86|0.86|4.5|13.5|TBD|24.2|17700|
