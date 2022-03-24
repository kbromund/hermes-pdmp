# 3 HERMES Ground Segment
Responsibility for operation of the HERMES Payload is shared by the Mission Operations Center (MOC), the Science Operations Center (SOC), and the Instrument Team Facilities (ITF), which together comprise the HERMES Ground Segment (GS). These several components of the GS are described in sections that follow. The HERMES Ground Segment supports operations of HERMES, as well as the production, storage, management, and dissemination of HERMES science and operational data products. It is primarily intended to support post-launch activities, although some elements may be employed to enable pre-launch testing of the HERMES Payload.
The GS will establish baselines for nominal operation of individual HP instruments to accomplish commissioning activities, collect science data, and initiate on-orbit calibration sequences. It will communicate with the Huntsville Operations Support Center regarding the state of Gateway as it affects HP operation, and it will accommodate operational changes imposed by Gateway. The GS will monitor Health and Safety data from the HP and identify operational anomalies. It will follow Anomaly Review Board (ARB) advisement to resolve anomalies, resume nominal operations, and recover instruments, if necessary.

## 3.1 Huntsville Operations Support Center (HOSC)
The Huntsville Operations Support Center at Marshall Space Flight Center is a multi-mission facility that will provide support for Flight Operations for Gateway. It transmits HERMES data to the ground. It receives HERMES commands and distributes them to the HERMES ICE Box. Its functions include:
*  Monitoring and maintenance of Gateway health and safety.
*  Generation of Gateway commands.
*  Merging and uplink of payload commands, including HERMES commands.
*  Gateway and HERMES engineering data capture.
*  HERMES science data capture.
*  Telemetry pass planning
*  Support real-time commanding of HERMES for commissioning activities and anomaly resolution

Additionally, the HOSC will provide the MOC with various data, as outlined in the Gateway Payload Interface Document, including the following:
*  All HP telemetry and select Gateway telemetry (real-time and playback).
*  Planning aids/products.
*  Gateway health/safety and status reports.
*  Predictive and definitive ephemeris and attitude products.
*  Ancillary data.

## 3.2 Mission Operations Center (MOC)
The Mission Operations Center is hosted in the Science and Planetary Operations Control Center (SPOCC) in Building 32 at the NASA Goddard Space Flight Center. The MOC receives raw data from the HOSC, produces Level-0 data files, and transmits those to the SOC. It supports all nominal and contingency operations including pre-launch activities, launch, on-orbit activation, and instrument calibration sequences. As part of nominal operations, it is staffed for 8 hours/day, five days/week, with automated alarm notification to on-call staff, including SOC and ITFs members, during off-hours.

The MOC is responsible for the HERMES Payload and payload-related operations. These functions include:
*  Health and safety monitoring of the HERMES Payload which includes the ICE Box, magnetometer boom, and critical instrument safety parameters.
*  Generation of real-time and stored commands.
*  Command planning and scheduling including coordinating Real-Time commanding windows.
*  Raw data capture from the HOSC.
*  Processing and dissemination of low-level instrument suite engineering telemetry.
*  Gateway and HERMES Payload attitude and ephemeris data distribution.
*  Level-0 data generation and distribution.
*  Configuration management of the HERMES telemetry and command definitions database.

## 3.3 Science Operations Center (SOC)
The Science Operations Center (SOC) is located at the NASA Goddard Space Flight Center in Greenbelt, Maryland. The SOC receives HERMES Level-0, HK, and ancillary data from the MOC and distributes those data to the Instrument Team Facilities. It is primarily responsible for ensuring that HERMES collects and distributes the data products required to achieve the HERMES science goals and objectives. It works with the MOC to manage and conduct instrument operations and serves as the central hub for all instrument and ancillary data required for instrument operations support, data processing, data distribution, and science analysis. Along with the Project Scientist, the SOC has responsibility for ensuring that HERMES is compliant with NASA policy for preservation and distribution of data, including transfer of data to a permanent archive. As part of nominal operations, it is staffed for 8 hours, five days a week, with automated alarm notification to on-call staff, including SOC and ITF personnel, during off-hours. Specific responsibilities of the SOC include:

*  Support instrument operations including health, safety, and performance, monitoring, instrument operations planning and scheduling.
* Level-0 to Level-1 data processing.
* Transfer required data products to ITFs.
* Instrument calibration support.
* All data archiving and public distribution.
* All software archiving and public distribution.
For payload operations, the specific SOC responsibilities include
* Support the planning and scheduling of instrument activities in coordination with the ITFs and HERMES Science Working Group.
* Monitor Instrument Suite performance.
* Support routine operations and commissioning of the Instrument Suite.
* Relay Instrument-relevant health and safety telemetry to ITFs.
* Notify the ITFs of anomalous conditions and respond as instructed.
* Coordinate Instrument planning and commanding among the different instruments and MOC activities.

For organizational purposes, the SOC contains the Science Data Center (SDC) for data production, management, and distribution functions.

### 3.3.1 The Science Data Center (SDC)
The Science Data Center (SDC) is the SOC component responsible for science data management, distribution, and processing of science data sets. In collaboration with the ITFs as well as the HERMES Science Working Group, the SDC will determine data storage and distribution mechanisms and ensure that data is processed and released to the public within the required timeframes. In addition, the SDC will develop web-based interfaces for accessing data and analysis tools, and it will coordinate the development of data analysis and visualization tools with the HERMES science team. These tools, as well as appropriate data products, and associated documentation will be available to the public via the Internet.

Specific SDC responsibilities are summarized as follows:
* Provide oversight and coordination of the distributed HERMES data processing system.
* Generate Level-1 and Quicklook products.
* Ensure ITFs access to all Level-0 data, provide Level-1 data, and Quicklook, and ancillary data.
* Provide tools to transform data into a variety of coordinate systems.
* Receive and manage processed science data products (Level 2, Level 3, and Auxiliary) from ITFs.
* Collect and archive associated software and documentation from ITFs.
* Disseminate science data products to the science community via SDC web interfaces.
* Coordinate with the Space Physics Data Facility (SPDF) for additional dissemination of science products and analysis tools.

## 3.4 Instrument Team Facilities
The HERMES Instrument Team Facilities are the principal institutions associated with each of the HERMES instruments. These facilities and their personnel provide support to the operation of the instruments and the overall data processing and distribution effort for the HERMES science and operational data products. The ITFs receive Level-0, Level-1 and HK data from the SOC. The ITFs are responsible for production of Level-2, Level-3, and Auxiliary data and for delivery of those data to the SOC.

The institutions listed in the table below have responsibility for each of the HERMES investigations and their corresponding instruments, together constituting the HERMES instrument suite:

Table 3-1. HERMES Instrument Team Facilities (ITF)
| Investigation                                                                    | Managing Institution                                                   | Point of Contact |
| -------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------- |  |
| Electron Electrostatic Analyzer (EEA)                                            | Goddard Space Flight Center (GSFC)                                     | D. Gershman      |
| Noise Eliminating Magnetometer Instrument in a Small Integrated System (NEMISIS) | Goddard Space Flight Center (GSFC)                                     | E. Zesta         |
| Miniaturized Electron pRoton Telescope (MERiT)                                   | Goddard Space Flight Center (GSFC)                                     | S. Kanekal       |
| Solar Probe Analyzers for Ions (SPAN-i)                                          | University of California-Berkeley (UCB) Space Science Laboratory (SSL) | R. Livi          |

ITFs are responsible for the following:
* Payload Operations Support:
* Participate in routine planning, attend routine planning teleconferences, and review instrument operational plans, as necessary.
* Monitor the detailed health, safety, and performance assessment of their respective instruments and provide instrument health and status reports.
* Provide instrument-planning requests and corresponding commands to the GS for incorporation into instrument operations plans.
* Provide any necessary updates to software (flight and ground).
* Support development of flight procedures and scripts.
* Science Data Center Support:
* Develop algorithms and software for production of Level-2, Level-3, Auxiliary, and Quicklook data products.
* Produce or arrange for production of Level-2, Level-3, and Auxiliary data products and deliver validated products to the SOC.
* Provide data product descriptions.
* Generate and maintain documentation of science algorithm, processing software systems, and data versions.
* Support the development of visualization tools.
* Provide science product metadata consistent with the SPASE standard as per the NASA Heliophysics Science Data Management Policy document.
* Support end-to-end testing of interfaces with the SDC.

## 3.5 Associated Organizations
### 3.5.1 HERMES Science Working Group (SWG)
The HERMES Science Working Group (SWG) is chartered by the Heliophysics Division at NASA Headquarters. The SWG is led by the HERMES PS. It includes the Instrument Team PIs, the Interdisciplinary Science Team PIs, and scientists from Gateway international partner organizations (CSA, ESA, JAXA) selected jointly by NASA HQ, the HERMES PS, and the partner organizations.
### 3.5.2 HERMES Interdisciplinary Science (IDS) Teams
External scientists competitively selected through ROSES 2020 Amendment B18, to pursue scientific objectives associated with and in support of the HERMES Mission.
### 3.5.3 Space Physics Data Facility (SPDF)
The SPDF is managed by the Heliospheric Science Division (HSD) at NASA's Goddard Space Flight Center. The Facility archives data from most NASA Heliophysics missions to promote correlative and collaborative research across discipline and mission boundaries. The SPDF provides multi-mission data services such as CDAWeb, software tools used for working with CDF data files, and is responsible for long-term HERMES data archival.
### 3.5.4 Moon to Mars Space Weather Office (M2M)
Located at Goddard Space Flight Center, the M2M is responsible for forecasting and distributing real-time space weather conditions to stakeholders such as Space Radiation Analysis Group (SRAG). The M2M will collaborate with the HERMES SWG in pursuing HERMES Goal C.