🌊 SMWREH 2026 | Team ReGenX

Smart Mine Water Circularity and Renewable Energy Hub


An intelligent and modular approach to mine-water treatment, water
circularity, real-time quality verification, and
renewable-energy-aware operation.

🌐 Live Website

https://minewateraffectedsihdashboard.netlify.app/

🎥 Idea Demo Video

https://youtu.be/_JOYUxP4N-4?si=U-YT9berG47gxxGW

🧩 Hardware Animation

https://ai.studio/apps/fdac3cd5-0ee1-44f5-96e7-9cf5365ac632

This interactive animation presents the proposed hardware concept and system operation.

📌 Project Overview

SMWREH stands for Smart Mine Water Circularity and Renewable
Energy Hub.

The project is being developed by Team ReGenX for Smart India
Hackathon 2026 under the Renewable/Sustainable Energy theme.

SMWREH proposes a modular mine-water management system that combines:

Real-time water-quality sensing

Smart treatment-demand analysis

Targeted and modular treatment

Chromium-focused detection and removal

Final quality verification

Re-treatment when quality requirements are not met

Water reuse for suitable non-potable applications

Renewable-energy integration using solar power and battery storage

The overall objective is to support cleaner water, efficient treatment,
reduced freshwater dependence, and more sustainable mine-water
management.

🧾 Problem Statement

Problem Statement ID: SIH26217
Problem Statement Title: Student Innovation
Theme: Renewable/Sustainable Energy
Category: Hardware
Team ID: 109
Team Name: Team_ReGenX

The Problem

Mining-affected water may contain contaminants such as Cr(VI), high
turbidity, and dissolved impurities. Conventional treatment systems may
operate at fixed intensity, making them difficult to adapt to changing
water quality and energy availability.

This can result in:

Increased treatment and pumping energy demand

Limited adaptability to different contamination levels

Inadequate real-time quality verification

Reduced opportunities for treated-water reuse

Difficulty deploying a single treatment configuration across
different sites

💡 Our Proposed Solution

SMWREH uses a modular treatment train supported by sensing,
decision-making, treatment, and quality-verification layers.

The system is designed to:

Measure the initial water-quality parameters.

Detect target contaminants, including Cr(VI).

Determine the required treatment intensity.

Apply suitable treatment modules.

Verify the quality of the treated water.

Allow reuse only when the quality check is passed.

Send water for re-treatment when the quality target is not achieved.

Coordinate treatment and pumping with available renewable energy.

🔄 System Workflow

MINE WATER
    │
    ▼
REAL-TIME WATER-QUALITY SENSING
    │
    ▼
TREATMENT DEMAND ANALYSIS
    │
    ▼
MODULAR / TARGETED TREATMENT
    │
    ▼
QUALITY VERIFICATION
    │
    ├── PASS ──► VERIFIED WATER REUSE
    │
    └── FAIL ──► RE-TREATMENT
                     │
                     └──► QUALITY RECHECK

🏗️ Modular Treatment Train

The proposed treatment train includes the following stages:

Raw Water Intake

Smart Sensing

Solids Removal

Fe-Electrocoagulation for Cr(VI) Removal

Targeted Cartridge

Polishing

Quality Check

Reuse

The treatment modules can be selected, adjusted, or replaced according
to site-specific water quality and treatment requirements.

⚙️ Technical Approach

The implementation is organized into three main layers.

Layer 1: Water Characterization

Real-time sensors are used to monitor water-quality and operating
parameters, including:

pH

Electrical conductivity / TDS

Turbidity

Temperature

Flow rate

Target contaminant concentration, including Cr(VI)

Layer 2: Decision Layer

The decision layer analyzes:

Treatment demand based on water quality

Flow rate and operating conditions

Electrocoagulation parameters

Battery state of charge

Solar-energy availability

Energy demand per litre of treated water

The system uses these inputs to support energy-aware treatment
decisions.

Layer 3: Action Layer

The action layer coordinates the physical treatment process through:

Pumps

Electrocoagulation reactor

Targeted treatment cartridge

Filtration/polishing unit

Re-treatment valve

Final Quality Verification

After treatment, the system checks the output water using relevant
parameters such as:

pH

TDS / electrical conductivity

Turbidity

Temperature

Flow

Cr(VI) concentration

The measured values can be used to calculate treatment performance and
determine whether the water is suitable for the intended reuse
application.

⚡ Renewable Energy Integration

The renewable-energy layer is designed to support sustainable system
operation through:

Solar photovoltaic power

Battery storage

Smart energy control

Energy-aware scheduling

Pump and treatment-load coordination

The objective is to align treatment activity with renewable-energy
availability while maintaining the required water-quality checks.

🛠️ Technologies and Components

Hardware

Water-quality sensors

pH sensor

EC/TDS sensor

Turbidity sensor

Temperature sensor

Flow sensor

Cr(VI) detection setup

DPC and/or optical sensing arrangement

ESP32 or Arduino-based controller

Electrocoagulation setup

Pumps and valves

Solar panel and battery system

Software Prototype

HTML

CSS

JavaScript

Python

Data processing and control logic

Real-time dashboard and visualization

AI-assisted development tools, where applicable

Future Integration

React / Node.js

Firebase / Supabase

Cloud storage

Machine learning for treatment and energy optimization

Update this section to reflect only the technologies and components
actually implemented in the current version.

📊 Monitoring and Data Visualization

The software dashboard is intended to support:

Live water-quality monitoring

Before-and-after parameter comparison

Treatment-efficiency calculation

Energy-consumption tracking

System-status monitoring

Alerts for abnormal readings

Data logging

Export of reports in CSV/PDF formats, if implemented

📈 Key Performance Indicators

The project focuses on the following measurable outcomes:

KPI                                 Description

Cr(VI) Removal                      Target removal performance of at
least 90%, subject to validation

Energy Consumption                  Energy used per volume of treated
water

Treatment Capacity                  Flow and treatment throughput in
litres per hour

Solar Contribution                  Share of operating energy supplied
by renewable sources

These are project targets or evaluation parameters. Actual performance
should be reported only after experimental validation.

✅ Feasibility and Viability

Feasibility

Modular treatment stages can be adapted to site-specific water
quality.

Sensors, pumps, filtration, and electrocoagulation components can be
integrated into a compact prototype.

Solar power and battery storage can support selected system loads.

A monitoring dashboard can provide real-time operational visibility.

Practical Viability

Modular deployment can support different mine sites and
contamination conditions.

Continuous monitoring can assist operational decisions.

Final quality verification creates a quality-control checkpoint
before reuse.

Replaceable modules can simplify maintenance and future upgrades.

Potential Applications

Mining-affected locations

Industrial water-treatment sites

Contaminated-water treatment clusters

Non-potable water-reuse applications

Renewable-energy-assisted treatment facilities

🌱 Expected Impact and Benefits

Water

Reduced contaminant burden

Verified treated-water quality

Improved opportunities for water reuse

Reduced freshwater dependence

Energy

Solar-assisted operation

Energy-aware treatment scheduling

Better visibility into energy consumption

Increased renewable-energy contribution

Environment

Reduced mine-water discharge

Lower contaminant mobility

Resource recovery and reuse

Support for circular water management

Economic and Social

Modular and scalable deployment

Real-time monitoring

Improved operational decision-making

Potential reduction in freshwater requirements



👥 Team ReGenX

Role

Name

Team Leader

Agrawal Aashray Manojkumar

Team Member

Jagrav Dharmendra Shukla

Team Member

Patel Ved Jaysukhbhai

Team Member

Shah Manya Manish

Team Member

Liza Himanshu Modi

Team Member

Aryan Bhushan

📌 Project Status

🟡 Status: Under Development

This project is being developed for Smart India Hackathon 2026 by
Team ReGenX.

🌍 Vision

To create a smarter and more sustainable mine-water ecosystem where
water quality, treatment demand, and renewable-energy availability
work together to support circular water management.

---

## 🖼️ Project Showcase

### 📊 Live Dashboard

![AQUA-MINE Dashboard](dashboard.png)

Our interactive dashboard for real-time mine-water quality monitoring and treatment management.

### ⚙️ SMWREH Hardware Prototype

![SMWREH Hardware Prototype](hardware-prototype.jpeg)

Our proposed modular hardware system for mine-water treatment, chromium removal, and renewable-energy integration.
