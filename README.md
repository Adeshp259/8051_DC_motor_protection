# 8051-Based DC Motor Protection and Monitoring System

**Project Status:** In Development

## 1. Project Overview

This project aims to develop a microcontroller-based DC motor protection and monitoring system using the 8051 microcontroller and Embedded C.

The system will monitor important motor operating parameters and implement protective actions when abnormal conditions are detected.

The project is being developed and tested as a low-voltage laboratory prototype.

## 2. Project Objectives

- Understand practical 8051 peripheral interfacing.
- Measure motor current, supply voltage and temperature.
- Implement motor ON/OFF control.
- Develop protection logic for abnormal operating conditions.
- Display operating conditions and fault information.
- Maintain a structured, documented Embedded C project.

## 3. Planned Hardware

- 8051 microcontroller (P89V51RD2)
- ADC0804 analog-to-digital converter
- DC motor
- Current sensing circuit
- Voltage sensing circuit
- Temperature sensor
- MOSFET motor driver
- 16x2 LCD
- Buzzer and indicator LEDs
- Regulated DC power supply

*Final component ratings and circuit connections will be documented after hardware selection and testing.*

## 4. Planned Protection Features

- Overcurrent protection
- Undervoltage protection
- Overvoltage protection
- Overtemperature protection
- Motor shutdown during fault conditions
- Fault indication and reset

## 5. Development Tools

- Keil µVision
- Embedded C
- Git and GitHub
- 8051 development hardware
- Digital multimeter and oscilloscope

## 6. Project Development Stages

1. Project setup and version control
2. ADC0804 interfacing
3. Voltage measurement
4. Current measurement
5. Temperature measurement
6. DC motor driver interfacing
7. Protection logic development
8. LCD and fault indication
9. System integration and testing

## 7. Repository Structure

- `Hardware/` – circuit diagrams and PCB files
- `Firmware/` – Embedded C source code
- `Testing/` – test results and fault testing
- `Documentation/` – technical documentation
- `Media/` – project photographs and videos

## 8. Project Documentation

Development progress, experiments, debugging and testing results will be documented throughout the project.

**Note:** This is a work in progress. Features will be marked complete only after implementation and testing.