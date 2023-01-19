# 5 CONFIGURATION MANAGEMENT & CONTROL
Configuration Management (CM) establishes and maintains the integrity of HERMES Ground Segment products and provides visibility and control of changes in the performance, functional, and physical characteristics of HERMES Ground Segment products.

Configuration Control is the systematic proposal, justification, evaluation, coordination, and approval or disapproval of changes. Configuration Control also includes the implementation of all approved changes to the baseline. The Configuration Control process includes identification of proposed changes, documentation of proposed changes, evaluation and disposition of proposed changes, and integration of approved changes.
Configuration management for the project is further described below.

## 5.1 Document Configuration Management
Changes proposed to HERMES Ground Segment process plans and procedures will be documented via Configuration Change Requests (CCRs). The HERMES Ground Segment will utilize a Living with a Star (LWS) provided CM and library system, TDMS. This capability is currently accessible via the internal network at GSFC and provides:
* Document Configuration Management
* Action Item Management

The CM system provides the capability to generate a Configuration Change Request (CCR) as well as Signature Change Requests (SCoRe) for new documents and document updates. CCRs and SCoRes can be drafted in advance. The CCRs, SCoRes, and Ground Segment Configuration Control Board (CCB) Agendas and Minutes are accessible via the web site. Notifications can be distributed to other personnel as required via email addresses. The CM system provides a searchable Documentation Library to locate and retrieve submitted and approved documents.

## 5.2 Configuration Control Board (CCB)
The CCB is a board composed of technical and administrative representatives who approve or disapprove proposed configuration changes to an “Approved Baseline”. While the HERMES project also holds its own separate project-wide CCB, the Ground Segment will also hold its own Ground-Segment CCB with the appropriate ground element team members.
The Ground Segment CCB will be chaired by the HERMES Ground Segment Manager and will consist of lead representatives from the HERMES MOC, the HERMES SOC, HERMES ITFs, and HERMES Project Science Office.

##5.3 Version Control
The HERMES GS will maintain both an issue tracking and version control system for its data production software, processing environment, analysis tools, data products and static calibration data. The SOC will maintain the repository of reference and will provide this functionality.

### 5.3.1 Software Version Control
The HERMES Ground Segment will use a source code management system for tracking code changes, software configurations, and other processing and data handling system dependencies (e.g. static calibration data). It is imperative that both software and calibration data are revision controlled (preferably together if they depend on each other), and that the revision repository is backed up regularly and maintained off-site.

### 5.3.2 Data Version Control
A system of data version numbering will be instituted. Version numbers will be incremented when changes in the processing system produce a different data result. Specifically:
* Changes to software or calibration data such that science data products change for a specific time range indicates that the version number of the science data must change.
* When the version changes for a product that other products depend upon, the version must be incremented for the dependent products as well.
The corresponding software changes will be documented, and version numbers will be included in data product file names. In the case that a team distributes a software calibrator rather than data files, the calibrator must clearly indicate to the user which version of the data the calibrator produces. A consistent version numbering scheme will be determined prior to the Ground Segment CDR and documented in the HERMES Instrument Suite Science Data Analysis Support and Data Products Plan.

## 5.4 Release Control
To ensure that HERMES science products (software or data) are of high quality, validation efforts will be integral to their generation. Pre-production validation includes design and peer reviews of algorithms, software, and workflows that will be used to produce data products. Production validation will include automated unit testing, integration testing, and product testing, in addition to validation by the ITF and/or SDC team as appropriate.
