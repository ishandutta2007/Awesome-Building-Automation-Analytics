# Awesome-Building-Automation-Analytics

## Top Building Automation Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Fault Detection, Energy Optimization & Autonomous Building Controls*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Building Automation Analytics**. These tools monitor building equipment performance, detect faults, optimize energy consumption, and increasingly enable autonomous control of HVAC, lighting, and other building systems.



**Examples** include Clockworks Analytics, CopperTree Analytics, Facilio, BuildingMinds, Switch Automation, BrainBox AI, Enertiv, GridPoint, 75F, and OpenBlue Enterprise Manager (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom analytics pipelines, and transparent building data management — ideal for facility managers, building engineers, researchers, and developers building vendor-independent building analytics solutions. The open-source ecosystem offers production-grade building operating systems, semantic data models, and research frameworks for control optimization.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Clockworks Analytics](https://www.clockworksanalytics.com/)**  

  Automated fault detection and diagnostics platform for building HVAC systems, identifying energy waste and equipment issues through continuous analytics.



- **[CopperTree Analytics](https://www.coppertreeanalytics.com/)**  

  Building analytics platform for HVAC performance monitoring and energy efficiency optimization with rule-based and AI-driven diagnostics.



- **[Facilio](https://facilio.com/)**  

  Connected building operations platform with energy management, maintenance, and sustainability tools for portfolios.



- **[BuildingMinds](https://www.buildingminds.com/)**  

  Real estate data platform unifying building performance analytics, ESG reporting, and portfolio management.



- **[Switch Automation](https://www.switchautomation.com/)**  

  Smart building platform for energy management, ESG reporting, and building system integration.



- **[BrainBox AI](https://www.brainboxai.com/)**  

  AI-powered HVAC optimization platform using deep learning to reduce energy consumption and carbon emissions in commercial buildings.



- **[Enertiv](https://www.enertiv.com/)**  

  Building operations platform with energy monitoring, equipment health, and work order management.



- **[GridPoint](https://www.gridpoint.com/)**  

  Energy management platform for commercial buildings with demand response, backup power, and sustainability reporting.



- **[75F](https://www.75f.io/)**  

  IoT-based building management system focused on HVAC, lighting, and energy optimization for commercial buildings.



- **[OpenBlue Enterprise Manager](https://www.johnsoncontrols.com/openblue)**  

  Comprehensive building management platform from Johnson Controls with AI-driven insights, autonomous controls, and energy optimization. Features generative AI tools that proactively recommend energy savings projects, automated fault detection and diagnostics, and support for tracking energy conservation projects across 130+ categories. Customers report up to 30% reduction in energy spend and 20% reduction in maintenance costs .



## Open-Source GitHub Projects



- **[Smart Core Building Operating System (SC BOS)](https://github.com/smart-core-os/sc-bos)**  

  Open-source building operating system for connecting building systems, running actions, hosting applications, and securing access to building data and control. Written in Go with Vue.js web applications. Deployed as controllers (Area, Building, Gateway) that communicate across a building cohort. Features OAuth2 and OpenID Connect authentication, role-based access, plugin architecture for drivers, autos, zones, and systems, and a comprehensive REST API. Currently in active development with BETA-status Go API. Ideal for organizations building custom building automation platforms without vendor lock-in .



- **[Brick Ontology](https://github.com/BrickSchema/Brick)**  

  Open-source, standardized ontology for describing building components, relationships, and operations. Provides a uniform metadata schema for buildings with classes for physical entities (equipment, devices, spaces), virtual entities (points, sensors), and logical entities (zones). Defines relationships for composition (hasPart), topology (feeds, hasLocation), and telemetry (hasPoint). The de facto standard for semantic building data modeling, with MCP server implementations enabling AI agent interaction with building metadata .



- **[Mortar](https://github.com/gtfierro/mortar)**  

  Open-source data model that combines Brick metadata with timeseries data for building analytics. Organizes timeseries data into streams linked to Brick models, providing context such as units, type, location, and related equipment. Enables semantic queries across building systems and supports the full lifecycle from metadata modeling to timeseries analysis .



- **[OpenBuildingControl (OBC)](https://github.com/lbl-srg/modelica-buildings/tree/master/Buildings/Controls/OBC)**  

  Open-source project from Lawrence Berkeley National Laboratory developing tools and processes for performance evaluation, specification, and verification of building control sequences. Implements ASHRAE Guideline 36 control sequences for HVAC systems in Modelica. Includes elementary control blocks and standardized sequence implementations for air handling units, VAV systems, and central plants. The reference implementation for standardized building control sequences .



- **[DRL-BEMS](https://github.com/AIS-Clemson/DRL-BEMS)**  

  Deep reinforcement learning based Building Energy Management System for multi-VAV open offices. Achieves 37% reduction in HVAC energy consumption with less than 1% temperature comfort violation and 2.5% humidity comfort violation. Requires minimal input variables (outdoor temperature, indoor temperature, time, control signals) and uses binary action space for temperature range enforcement. Computationally efficient at ~7.75 minutes per epoch. Published in Applied Energy .



- **[ACTIVE (Automated Control Testbed for Integration, Verification, and Emulation)](https://github.com/SmithRWORNL/ACTIVE)**  

  Open-source framework from Oak Ridge National Laboratory (BSD 3-Clause) supporting optimized operation and management of diverse building types. Enables development, testing, and validation of AI-based, rule-based, and model-based control strategies. Facilitates seamless transition from simulation to real-world field validation. Supports full building management lifecycle: data acquisition, system monitoring, optimized control, adaptive learning, device dispatch, and advanced analytics. Python-based with active development as of 2025 .



- **[Brick Ontology Service](https://github.com/Pamekitti/brick-ontology-service)**  

  FastAPI service managing and querying building data using the Brick ontology schema. Provides RESTful endpoints for semantic building data management, SPARQL queries, and RDF graph operations. Built with RDFLib and BrickSchema for standardized building metadata representation. Includes building model generation utilities for office, lab, hospital, and retail building types with standard equipment templates (AHU, VAV, Chiller) .



- **[Asuna](https://github.com/lauslim12/Asuna)**  

  Open-source, scalable building management system built for research purposes. Features infinite room and floor creation, user booking, multi-role support (user, admin, owner), admin CRUD operations, earnings tracking, visitor management, and voucher creation. Built with Next.js, Chakra UI, Express.js, MongoDB, and deployed on Vercel/Heroku. Tested with Technology Acceptance Model showing production readiness for coworking spaces and office buildings .



- **[Energy Management in Building Facilities](https://github.com/Kokonelas/Energy_Management_In_Building_Facilities)**  

  Modular Java application simulating smart building management system. Includes microservices for photovoltaic panel control, HVAC monitoring, lighting and sound automation, water and power tracking, and security system simulation. Designed with modular architecture for educational and prototyping purposes .



- **[ecosysnc](https://github.com/kimdain0222/ecosysnc)**  

  Smart Building Energy Management System (SBEMS) analyzing campus building power usage to automatically control lighting and air conditioning when vacant. Features data analysis, occupancy prediction models, automatic control logic, and real-time dashboard. Built with React.js frontend, FastAPI backend, Python ML pipeline, and PostgreSQL .



### Additional Strong Open-Source Options



- **Google Digital Buildings** — Google's open-source ontology and SDK for managing their own buildings, providing a large-scale semantic building data model used internally at Google .

- **Building Energy Management Simscape** — MATLAB/Simscape project for modeling building energy management systems including heat transfer and HVAC control for multi-story buildings .

- **WIA Standards Building Energy Management** — Open standards repository with control protocol implementations for supply air temperature reset, fan control with static pressure reset, and economizer control .

- **fan-monitor** — Python-based remote monitoring tool for building ventilation fan run and fault states, useful for basic equipment monitoring .

- **DAB-CPS Framework** — Open-source framework for autonomous building management using blockchain and AI, validated in real-world building with DAO governance, space reservation, and AI virtual assistant for facility management .



**Frameworks for building custom building analytics solutions**: Combine **Brick Ontology** as the semantic data model foundation with **Mortar** for metadata-timeseries integration . Use **SC BOS** for building operating system infrastructure with multi-controller deployment and OAuth2 security . Implement **OpenBuildingControl** ASHRAE Guideline 36 sequences for standardized HVAC control . For AI-driven optimization research, **DRL-BEMS** provides a published DRL framework with demonstrated 37% energy savings . For validation and testing, **ACTIVE** from ORNL offers a comprehensive testbed for control strategy development . Note that full enterprise building analytics with automated fault detection, portfolio benchmarking, and utility bill management remains primarily commercial territory; open-source stacks provide strong semantic models, control libraries, and research frameworks that require integration for production deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Building automation analytics tools must comply with local building codes, energy regulations, and grid interconnection standards.

- Self-hosted open-source solutions require proper infrastructure, expertise in building automation protocols (Modbus, BACnet, MQTT, KNX), and ongoing maintenance. Integration with existing building systems requires specialized knowledge.

- The open-source ecosystem provides strong semantic models, control libraries, and research frameworks, but full commercial building analytics with automated fault detection, portfolio benchmarking, and utility bill management remains primarily a commercial offering.



---



**Made for facility managers, building engineers, energy analysts, and smart building developers.**  

Let's make building automation analytics more open, transparent, and efficient.
