# Chipkin Automation Systems 

Chipkin Automation Systems is a building and industrial automation protocol expert. We develop, support, and configure protocol converters/gateways, data loggers, remote monitoring, and control applications.

- Website: https://store.chipkin.com/
- Contact us: https://store.chipkin.com/contact-us

## CAS BACnet Stack 

Chipkin’s BACnet Stack ([CAS BACnet Stack](https://store.chipkin.com/services/stacks/bacnet-stack)) is a software library that allows you to add a native BACnet interface to your embedded devices or applications. The BACnet stack supports both BACnet server (Field device, power meter, gas detector, etc...) and BACnet client (HMI, Utilities, data loggers, etc.). More information about the CAS BACnet Stack can be found here https://store.chipkin.com/services/stacks/bacnet-stack

See the [repositories tab](https://github.com/orgs/chipkin/repositories) for a full list of CAS BACnet Stack examples in many different programming languages 


### BACnet profile examples

The [CAS BACnet Stack](https://store.chipkin.com/services/stacks/bacnet-stack) supports every standardized device profile in ASHRAE 135-2024 Annex L, and there is one example repository per profile. Pick the profile your device claims, then the language you build in. "Ask" means the example hasn't been built yet for that language - [contact Chipkin](https://www.chipkin.com/contact/) if you need one.

#### Controllers (Annex L.4)

| Profile | C++ | Node.js | C# | Rust | Python | GO |
|---|---|---|---|---|---|---|
| **B-SS** Smart Sensor (**Start here**) | [B-SS-CPP](https://github.com/chipkin/BACnetProfileExample-B-SS-CPP) | Ask | Ask | Ask | Ask | Ask |
| **B-SA** Smart Actuator | [B-SA-CPP](https://github.com/chipkin/BACnetProfileExample-B-SA-CPP) | Ask | Ask | Ask | Ask | Ask |
| **B-ASC** Application Specific Controller | [B-ASC-CPP](https://github.com/chipkin/BACnetProfileExample-B-ASC-CPP) | [B-ASC-Node](https://github.com/chipkin/BACnetProfileExample-B-ASC-Node) | Ask | Ask | Ask | Ask |
| **B-AAC** Advanced Application Controller | [B-AAC-CPP](https://github.com/chipkin/BACnetProfileExample-B-AAC-CPP) | Ask | Ask | Ask | Ask | Ask |
| **B-BC** Building Controller | [B-BC-CPP](https://github.com/chipkin/BACnetProfileExample-B-BC-CPP) | Ask | Ask | Ask | Ask | Ask |

#### Life safety controllers (Annex L.5)

| Profile | C++ | Node.js | C# | Rust | Python |GO |
|---|---|---|---|---|---|---|
| **B-LSC** Life Safety Controller | [B-LSC-CPP](https://github.com/chipkin/BACnetProfileExample-B-LSC-CPP) 🚧 | Ask | Ask | Ask | Ask |Ask |
| **B-ALSC** Advanced Life Safety Controller | [B-ALSC-CPP](https://github.com/chipkin/BACnetProfileExample-B-ALSC-CPP) | Ask | Ask | Ask | Ask |Ask |

#### Access control controllers (Annex L.6)

| Profile | C++ | Node.js | C# | Rust | Python |GO |
|---|---|---|---|---|---|---|
| **B-ACC** Access Control Controller | [B-ACC-CPP](https://github.com/chipkin/BACnetProfileExample-B-ACC-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-AACC** Advanced Access Control Controller | [B-AACC-CPP](https://github.com/chipkin/BACnetProfileExample-B-AACC-CPP) | Ask | Ask | Ask | Ask |Ask |

#### Lighting controllers (Annex L.11)

| Profile | C++ | Node.js | C# | Rust | Python |GO |
|---|---|---|---|---|---|---|
| **B-LD** Lighting Device | [B-LD-CPP](https://github.com/chipkin/BACnetProfileExample-B-LD-CPP) | Ask | Ask | Ask | Ask |Ask |Ask |
| **B-LS** Lighting Supervisor | [B-LS-CPP](https://github.com/chipkin/BACnetProfileExample-B-LS-CPP) | Ask | Ask | Ask | Ask |Ask |Ask |

#### Elevator controllers (Annex L.13)

| Profile | C++ | Node.js | C# | Rust | Python |GO |
|---|---|---|---|---|---|---|
| **B-EM** Elevator Monitor | [B-EM-CPP](https://github.com/chipkin/BACnetProfileExample-B-EM-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-EC** Elevator Controller | [B-EC-CPP](https://github.com/chipkin/BACnetProfileExample-B-EC-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-AEC** Advanced Elevator Controller | [B-AEC-CPP](https://github.com/chipkin/BACnetProfileExample-B-AEC-CPP) | Ask | Ask | Ask | Ask |Ask |

#### Authentication and authorization (Annex L.14)

| Profile | C++ | Node.js | C# | Rust | Python |GO |
|---|---|---|---|---|---|---|
| **B-AS** Authorization Server | [B-AS-CPP](https://github.com/chipkin/BACnetProfileExample-B-AS-CPP) | Ask | Ask | Ask | Ask |Ask |

#### Miscellaneous (Annex L.7, combinable with any one family)

| Profile | C++ | Node.js | C# | Rust | Python |GO |
|---|---|---|---|---|---|---|
| **B-BBMD** Broadcast Management Device | [B-BBMD-CPP](https://github.com/chipkin/BACnetProfileExample-B-BBMD-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-ACDC** Access Control Door Controller | [B-ACDC-CPP](https://github.com/chipkin/BACnetProfileExample-B-ACDC-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-ACCR** Access Control Credential Reader | [B-ACCR-CPP](https://github.com/chipkin/BACnetProfileExample-B-ACCR-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-RTR** Router | [B-RTR-CPP](https://github.com/chipkin/BACnetProfileExample-B-RTR-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-GW** Gateway | [B-GW-CPP](https://github.com/chipkin/BACnetProfileExample-B-GW-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-DAP** Device Address Proxy | [B-DAP-CPP](https://github.com/chipkin/BACnetProfileExample-B-DAP-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-SCHUB** BACnet/SC Hub | [B-SCHUB-CPP](https://github.com/chipkin/BACnetProfileExample-B-SCHUB-CPP) | Ask | Ask | Ask | Ask |Ask |
| **B-GENERAL** General device (Annex L.8) | *(satisfied by every example above)* | — | — | — | — |— |

### BIBBs (BACnet Interoperability Building Blocks)

#### K.1 Data Sharing (DS)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.1.1 - DS-RP-A | Data Sharing - ReadProperty-A | ✅ |
| K.1.2 - DS-RP-B | Data Sharing - ReadProperty-B | ✅ |
| K.1.3 - DS-RPM-A | Data Sharing - ReadPropertyMultiple-A | ✅ |
| K.1.4 - DS-RPM-B | Data Sharing - ReadPropertyMultiple-B | ✅ |
| K.1.5 - DS-WP-A | Data Sharing - WriteProperty-A | ✅ |
| K.1.6 - DS-WP-B | Data Sharing - WriteProperty-B | ✅ |
| K.1.7 - DS-WPM-A | Data Sharing - WritePropertyMultiple-A | ✅ |
| K.1.8 - DS-WPM-B | Data Sharing - WritePropertyMultiple-B | ✅ |
| K.1.9 - DS-COV-A | Data Sharing - COV-A | ✅ |
| K.1.10 - DS-COV-B | Data Sharing - COV-B | ✅ |
| K.1.11 - DS-COVP-A | Data Sharing - COV Property-A | ✅ |
| K.1.12 - DS-COVP-B | Data Sharing - COV Property-B | ✅ |
| K.1.13 - DS-COVU-A | Data Sharing - COV Unsubscribed-A | ✅ |
| K.1.14 - DS-COVU-B | Data Sharing - COV Unsubscribed-B | ✅ |
| K.1.15 - DS-V-A | Data Sharing - View-A | ✅ |
| K.1.16 - DS-AV-A | Data Sharing - Advanced View-A | ✅ |
| K.1.17 - DS-M-A | Data Sharing - Modify-A | ✅ |
| K.1.18 - DS-AM-A | Data Sharing - Advanced Modify-A | ✅ |
| K.1.19 - DS-WG-A | Data Sharing - WriteGroup-A | Ask |
| K.1.20 - DS-WG-I-B | Data Sharing - WriteGroup-Internal-B | ✅ |
| K.1.21 - DS-WG-E-B | Data Sharing - WriteGroup-External-B | ✅ |
| K.1.22 - DS-VSI-B | Data Sharing - Value Source Information-B | Ask |
| K.1.23 - DS-COVM-A | Data Sharing - COV Multiple-A | ✅ |
| K.1.24 - DS-COVM-B | Data Sharing - COV Multiple-B | ✅ |
| K.1.25 - DS-LSV-A | Data Sharing - Life Safety View-A | ✅ |
| K.1.26 - DS-LSAV-A | Data Sharing - Life Safety Advanced View-A | ✅ |
| K.1.27 - DS-LSM-A | Data Sharing - Life Safety Modify-A | ✅ |
| K.1.28 - DS-LSAM-A | Data Sharing - Life Safety Advanced Modify-A | ✅ |
| K.1.29 - DS-ACV-A | Data Sharing - Access Control View-A | ✅ |
| K.1.30 - DS-ACAV-A | Data Sharing - Access Control Advanced View-A | ✅ |
| K.1.31 - DS-ACM-A | Data Sharing - Access Control Modify-A | ✅ |
| K.1.32 - DS-ACAM-A | Data Sharing - Access Control Advanced Modify-A | ✅ |
| K.1.33 - DS-ACUC-A | Data Sharing - Access Control User Config-A | ✅ |
| K.1.34 - DS-ACUC-B | Data Sharing - Access Control User Config-B | ✅ |
| K.1.35 - DS-ACSC-A | Data Sharing - Access Control Site Config-A | ✅ |
| K.1.36 - DS-ACSC-B | Data Sharing - Access Control Site Config-B | ✅ |
| K.1.37 - DS-ACAD-A | Data Sharing - Access Control Access Door-A | ✅ |
| K.1.38 - DS-ACAD-B | Data Sharing - Access Control Access Door-B | ✅ |
| K.1.39 - DS-ACCDI-A | Data Sharing - Access Control Credential Data Input-A | Ask |
| K.1.40 - DS-ACCDI-B | Data Sharing - Access Control Credential Data Input-B | ✅ |
| K.1.41 - DS-LO-A | Data Sharing - Lighting Output-A | ✅ |
| K.1.42 - DS-LOS-A | Data Sharing - Lighting Output Status-A | ✅ |
| K.1.43 - DS-ALO-A | Data Sharing - Advanced Lighting Output-A | ✅ |
| K.1.44 - DS-LO-B | Data Sharing - Lighting Output-B | ✅ |
| K.1.45 - DS-BLO-B | Data Sharing - Binary Lighting Output-B | ✅ |
| K.1.46 - DS-LV-A | Data Sharing - Lighting View-A | ✅ |
| K.1.47 - DS-LAV-A | Data Sharing - Lighting Advanced View-A | ✅ |
| K.1.48 - DS-LM-A | Data Sharing - Lighting Modify-A | ✅ |
| K.1.49 - DS-LAM-A | Data Sharing - Lighting Advanced Modify-A | ✅ |
| K.1.50 - DS-EV-A | Data Sharing - Elevator View-A | ✅ |
| K.1.51 - DS-EAV-A | Data Sharing - Elevator Advanced View-A | ✅ |
| K.1.52 - DS-EM-A | Data Sharing - Elevator Modify-A | ✅ |
| K.1.53 - DS-EAM-A | Data Sharing - Elevator Advanced Modify-A | ✅ |


#### K.2 Alarm and Event Management (AE)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.2.1 - AE-N-A | Alarm and Event - Notification-A | ✅ |
| K.2.2 - AE-N-I-B | Alarm and Event - Notification-Internal-B | ✅ |
| K.2.3 - AE-N-E-B | Alarm and Event - Notification-External-B | ✅ |
| K.2.4 - AE-ACK-A | Alarm and Event - Acknowledge-A | ✅ |
| K.2.5 - AE-ACK-B | Alarm and Event - Acknowledge-B | ✅ |
| K.2.6 - AE-ASUM-A | Alarm and Event - Alarm Summary-A (deprecated) | ✅ |
| K.2.7 - AE-ASUM-B | Alarm and Event - Alarm Summary-B (deprecated) | ✅ |
| K.2.8 - AE-ESUM-A | Alarm and Event - Enrollment Summary-A (deprecated) | ✅ |
| K.2.9 - AE-ESUM-B | Alarm and Event - Enrollment Summary-B (deprecated) | ✅ |
| K.2.10 - AE-INFO-A | Alarm and Event - Information-A (deprecated) | ✅ |
| K.2.11 - AE-INFO-B | Alarm and Event - Information-B | ✅ |
| K.2.12 - AE-LS-A | Alarm and Event - LifeSafety-A | ✅ |
| K.2.13 - AE-LS-B | Alarm and Event - LifeSafety-B | ✅ |
| K.2.14 - AE-VN-A | Alarm and Event - View Notifications-A | ✅ |
| K.2.15 - AE-AVN-A | Alarm and Event - Advanced View Notifications-A | ✅ |
| K.2.16 - AE-VM-A | Alarm and Event - View and Modify-A | ✅ |
| K.2.17 - AE-AVM-A | Alarm and Event - Advanced View and Modify-A | ✅ |
| K.2.18 - AE-AS-A | Alarm and Event - Alarm Summary View-A | ✅ |
| K.2.19 - AE-ELV-A | Alarm and Event - Event Log View-A | ✅ |
| K.2.20 - AE-ELVM-A | Alarm and Event - Event Log View and Modify-A | ✅ |
| K.2.21 - AE-EL-I-B | Alarm and Event - Event Log-Internal-B | ✅ |
| K.2.22 - AE-EL-E-B | Alarm and Event - Event Log-External-B | ✅ |
| K.2.23 - AE-NF-B | Alarm and Event - Notification Forwarder-B | ✅ |
| K.2.24 - AE-NF-I-B | Alarm and Event - Notification Forwarder-Internal-B | ✅ |
| K.2.25 - AE-CRL-B | Alarm and Event - Configurable Recipient Lists-B | ✅ |
| K.2.26 - AE-TES-A | Alarm and Event - Temporary Event Subscription-A | Ask |
| K.2.27 - AE-LSVN-A | Alarm and Event - Life Safety View Notifications-A | ✅ |
| K.2.28 - AE-LSAVN-A | Alarm and Event - Life Safety Advanced View Notifications-A | ✅ |
| K.2.29 - AE-LSVM-A | Alarm and Event - Life Safety View and Modify-A | ✅ |
| K.2.30 - AE-LSAVM-A | Alarm and Event - Life Safety Advanced View and Modify-A | ✅ |
| K.2.31 - AE-AC-A | Alarm and Event - Access Control-A | ✅ |
| K.2.32 - AE-AC-B | Alarm and Event - Access Control-B | Ask |
| K.2.33 - AE-ACAVN-A | Alarm and Event - Access Control Advanced View Notifications-A | ✅ |
| K.2.34 - AE-ACVM-A | Alarm and Event - Access Control View and Modify-A | ✅ |
| K.2.35 - AE-ACAVM-A | Alarm and Event - Access Control Advanced View and Modify-A | ✅ |
| K.2.36 - AE-EVN-A | Alarm and Event - Elevator View Notifications-A | ✅ |
| K.2.37 - AE-EAVN-A | Alarm and Event - Elevator Advanced View Notifications-A | ✅ |
| K.2.38 - AE-EVM-A | Alarm and Event - Elevator View and Modify-A | ✅ |
| K.2.39 - AE-EAVM-A | Alarm and Event - Elevator Advanced View and Modify-A | ✅ |

#### K.3 Scheduling (SCHED)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.3.1 - SCHED-A | Scheduling-A (deprecated) | ✅ |
| K.3.2 - SCHED-I-B | Scheduling-Internal-B | ✅ |
| K.3.3 - SCHED-E-B | Scheduling-External-B | ✅ |
| K.3.4 - SCHED-R-B | Scheduling-Readonly-B | ✅ |
| K.3.5 - SCHED-AVM-A | Scheduling-Advanced View and Modify-A | ✅ |
| K.3.6 - SCHED-VM-A | Scheduling-View and Modify-A | ✅ |
| K.3.7 - SCHED-WS-A | Scheduling-Weekly Schedule-A | ✅ |
| K.3.8 - SCHED-WS-I-B | Scheduling-Weekly Schedule-Internal-B | ✅ |
| K.3.9 - SCHED-TMR-I-B | Scheduling-Timer-Internal-B | ✅ |
| K.3.10 - SCHED-TMR-E-B | Scheduling-Timer-External-B | ✅ |

#### K.4 Trending (T)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.4.1 - T-VMT-A | Trending - View and Modify Trends-A (deprecated) | ✅ |
| K.4.2 - T-VMT-I-B | Trending - View and Modify Trends-Internal-B | ✅ |
| K.4.3 - T-VMT-E-B | Trending - View and Modify Trends-External-B | ✅ |
| K.4.4 - T-ATR-A | Trending - Automated Trend Retrieval-A | ✅ |
| K.4.5 - T-ATR-B | Trending - Automated Trend Retrieval-B | ✅ |
| K.4.6 - T-VMMV-A | Trending - View and Modify Multiple Values-A (deprecated) | ✅ |
| K.4.7 - T-VMMV-I-B | Trending - View and Modify Multiple Values-Internal-B | ✅ |
| K.4.8 - T-VMMV-E-B | Trending - View and Modify Multiple Values-External-B | ✅ |
| K.4.9 - T-AMVR-A | Trending - Automated Multiple Value Retrieval-A | ✅ |
| K.4.10 - T-AMVR-B | Trending - Automated Multiple Value Retrieval-B | ✅ |
| K.4.11 - T-V-A | Trending - View-A | ✅ |
| K.4.12 - T-AVM-A | Trending - Advanced View and Modify-A | ✅ |
| K.4.13 - T-A-A | Trending - Archival-A | ✅ |

#### K.5 Device Management (DM)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.5.1 - DM-DDB-A | Device Management - Dynamic Device Binding-A | ✅ |
| K.5.2 - DM-DDB-B | Device Management - Dynamic Device Binding-B | ✅ |
| K.5.3 - DM-DOB-A | Device Management - Dynamic Object Binding-A | ✅ |
| K.5.4 - DM-DOB-B | Device Management - Dynamic Object Binding-B | ✅ |
| K.5.5 - DM-DCC-A | Device Management - DeviceCommunicationControl-A | ✅ |
| K.5.6 - DM-DCC-B | Device Management - DeviceCommunicationControl-B | ✅ |
| K.5.9 - DM-TM-A | Device Management - Text Message-A | ✅ |
| K.5.10 - DM-TM-B | Device Management - Text Message-B | ✅ |
| K.5.11 - DM-TS-A | Device Management - TimeSynchronization-A | ✅ |
| K.5.12 - DM-TS-B | Device Management - TimeSynchronization-B | ✅ |
| K.5.13 - DM-UTC-A | Device Management - UTCTimeSynchronization-A | ✅ |
| K.5.14 - DM-UTC-B | Device Management - UTCTimeSynchronization-B | ✅ |
| K.5.15 - DM-RD-A | Device Management - ReinitializeDevice-A | ✅ |
| K.5.16 - DM-RD-B | Device Management - ReinitializeDevice-B | ✅ |
| K.5.17 - DM-BR-A | Device Management - Backup and Restore-A | ✅ |
| K.5.18 - DM-BR-B | Device Management - Backup and Restore-B | ✅ |
| K.5.19 - DM-R-A | Device Management - Restart-A | ✅ |
| K.5.20 - DM-R-B | Device Management - Restart-B | ✅ |
| K.5.21 - DM-LM-A | Device Management - List Manipulation-A | Ask |
| K.5.22 - DM-LM-B | Device Management - List Manipulation-B | Ask |
| K.5.23 - DM-OCD-A | Device Management - Object Creation and Deletion-A | ✅ |
| K.5.24 - DM-OCD-B | Device Management - Object Creation and Deletion-B | ✅ |
| K.5.27 - DM-ANM-A | Device Management - Automatic Network Mapping-A | ✅ |
| K.5.28 - DM-ADM-A | Device Management - Automatic Device Mapping-A | ✅ |
| K.5.29 - DM-ATS-A | Device Management - Automatic Time Synchronization-A | ✅ |
| K.5.30 - DM-MTS-A | Device Management - Manual Time Synchronization-A | ✅ |
| K.5.31 - DM-SP-VM-A | Device Management - Subordinate Proxy-View and Modify-A | Ask |
| K.5.32 - DM-SP-B | Device Management - Subordinate Proxy-B | Ask |
| K.5.33 - DM-LOM-A | Device Management - Lighting Output Management-A | ✅ |
| K.5.34 - DM-DDA-A | Device Management - Dynamic Device Assignment-A | ✅ |
| K.5.35 - DM-DDA-B | Device Management - Dynamic Device Assignment-B | ✅ |
| K.5.36 - DM-DAP-VM-A | Device Management - Device Address Proxying-View and Modify-A | Ask |
| K.5.37 - DM-DAP-B | Device Management - Device Address Proxying-B | Ask |
| K.5.38 - DM-TSDI-A | Device Management - Time Series Data Import-A | ✅ |
| K.5.39 - DM-TSDE-A | Device Management - Time Series Data Export-A | ✅ |

#### K.6 Network Management (NM)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.6.1 - NM-CE-A | Network Management - Connection Establishment-A | Ask |
| K.6.2 - NM-CE-B | Network Management - Connection Establishment-B | Ask |
| K.6.3 - NM-RC-A | Network Management - Router Configuration-A | Ask |
| K.6.4 - NM-RC-B | Network Management - Router Configuration-B | ✅ |
| K.6.5 - NM-BBMDC-A | Network Management - BBMD Configuration-A | ✅ |
| K.6.6 - NM-BBMDC-B | Network Management - BBMD Configuration-B | ✅ |
| K.6.7 - NM-FDR-A | Network Management - Foreign Device Registration-A | ✅ |
| K.6.8 - NM-SCH-B | Network Management - Secure Connect Hub-B | ✅ |
| K.6.9 - NM-SCDC-A | Network Management - Secure Connect Direct Connect-A | Ask |
| K.6.10 - NM-SCDC-B | Network Management - Secure Connect Direct Connect-B | Ask |
| K.6.11 - NM-CC-A | Network Management - Communications Configuration-A | ✅ |
| K.6.12 - NM-SCCM-A | Network Management - Secure Connect Certificate Management-A | Ask |

#### K.7 Gateway (GW)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.7.1 - GW-VN-B | Gateway - Virtual Network-B | ✅ |
| K.7.2 - GW-EO-B | Gateway - Embedded Objects-B | ✅ |

#### K.8 Audit Reporting (AR)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.8.1 - AR-L-A | Audit Reporting - Logging-A | Ask |
| K.8.2 - AR-R-B | Audit Reporting - Reporter-B | Ask |
| K.8.3 - AR-R-S-B | Audit Reporting - Reporter-Simple-B | Ask |
| K.8.4 - AR-F-B | Audit Reporting - Forwarder-B | Ask |
| K.8.5 - AR-V-A | Audit Reporting - View-A | Ask |
| K.8.6 - AR-AVM-A | Audit Reporting - Advanced View and Modify-A | Ask |

#### K.9 Authentication and Authorization (AA)

| BIBB | Description | Supported |
|------|-------------|:---------:|
| K.9.1 - AA-DAC-A | Dynamic Authorization Client-A | Ask |
| K.9.2 - AA-SAC-A | Static Authorization Client-A | Ask |
| K.9.3 - AA-AT-B | Authorization Target-B | Ask |
| K.9.4 - AA-NAT-B | Non-secure Authorization Target-B | Ask |
| K.9.5 - AA-AS-B | Authorization Server-B | Ask |



----

## CAS BACnet Stack v5 exaples

Most common programming language examples 

- C++
  - [BACnet Server example CPP](https://github.com/chipkin/BACnetServerExampleCPP) - A BACnet IP server example written in C++ using the CAS BACnet Stack.
  - [BACnet Client example CPP](https://github.com/chipkin/BACnetClientExampleCPP) - A BACnet IP client example written in C++ using the CAS BACnet Stack.  
- TypeScript/NodeJS
  - [BACnet Server Example in TypeScript](https://github.com/chipkin/BACnetServerExampleTypeScript) - A BACnet IP server example written in TypeScript using the CAS BACnet Stack.
  - [BACnet Client Example NodeJS](https://github.com/chipkin/BACnetClientExampleNodeJS) - A basic BACnet IP client example written in NodeJS using the CAS BACnet Stack.
- CSharp
  - [BACnet Server Example CSharp](https://github.com/chipkin/BACnetServerExampleCSharp) - A basic BACnet IP server example written in CSharp using the CAS BACnet Stack.
  - [BACnet Client Example CSharp](https://github.com/chipkin/BACnetClientExampleCSharp) - A basic BACnet IP client example written in CSharp using the CAS BACnet Stack.
- GoLang
  - [BACnet Server Example GoLang](https://github.com/chipkin/BACnetServerExampleGolang) - A basic BACnet IP server example written in GoLang using the CAS BACnet Stack.
- Python 3.x
  - [BACnet Server Example Python 3.x](https://github.com/chipkin/BACnetServerExamplePython) - A basic BACnet IP server example written in Python 3.x using the CAS BACnet Stack.
- Rust
  - [BACnet Server Example in RUST](https://github.com/chipkin/BACnetServerExampleRUST) - A basic BACnet IP server example written in RUST using the CAS BACnet Stack.
  - [BACnet Client Example in RUST](https://github.com/chipkin/BACnetClientExampleRUST) - A basic BACnet IP client example written in RUST using the CAS BACnet Stack.
- Java
  - [BACnet Server Example in Java](https://github.com/chipkin/BACnetServerExampleJava) - A basic BACnet IP server example written in Java using the CAS BACnet Stack.
  - [BACnet Client Example in Java](https://github.com/chipkin/BACnetClientExampleJava) - A basic BACnet IP client example written in Java using the CAS BACnet Stack.

Hardware examples

- [ESP32-BACnetServerExample](https://github.com/chipkin/ESP32-BACnetServerExample) - A simple BACnet server with one Multi-state-value (MSV) object. The MSV shows the current mode of the built-in LED.
- [RP2040-BACnetServerExample](https://github.com/chipkin/RP2040-BACnetServerExample) - A simple BACnet server with one Multi-state-value (MSV) object. The MSV shows the current mode of the built-in LED.

Specific feature examples

- [BACnetSCNodeExampleCPP](https://github.com/chipkin/BACnetSCNodeExampleCPP) - A C++ example application demonstrating a BACnet/SC (Secure Connect) Node using the libwebsockets.
- [BACnetElevatorExample](https://github.com/chipkin/BACnetElevatorExample) - Example of a BACnet IP server using Elevator group, Elevator, Escalator, Lift, Double deck lift objects types, and Alarms and Events, intrinsic event, and fault algorithms
- [BACnetVirtualDevicesServerExampleCPP](https://github.com/chipkin/BACnetVirtualDevicesServerExampleCPP) - BACnet Virtual Device Server Example written in C++.
- [BACnetServerExampleProprietaryPropertyCSharp](https://github.com/chipkin/BACnetServerExampleProprietaryPropertyCSharp) - Demonstrating how to add Vendor Proprietary Property and object types

See the [repositories tab](https://github.com/orgs/chipkin/repositories) for a full list of examples.
