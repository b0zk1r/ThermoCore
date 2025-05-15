# ThermoCore

- Version: 1.0
- Author: Tunga Kaya (@b0zk1r)
- Release Date: May 14, 2025
- Platform: HP Prime G2
- Language: HP PPL (Prime Programming Language)
- Tested On: HP Prime G2 Firmware 2.2.15270 (2025-01-31)

## Description

ThermoCore is a modular thermodynamics calculator written in HP PPL for the HP Prime G2 graphing calculator. It is designed to support engineers and students working on various thermodynamic problems. The program integrates multiple calculators and plotting utilities into a single, expandable application.

## Features

- Ideal Gas Law Solver

- Computes Pressure, Volume, Moles, or Temperature

- Work Calculations in Thermodynamic Processes

- Supports isobaric, isothermal, adiabatic, and isochoric processes

- Enthalpy Calculator

- Calculates total enthalpy from internal energy, pressure, and volume

- Thermodynamic Property Tools

- Unit conversion for pressure and temperature

- Calculates changes in enthalpy, entropy, and specific volume

- Steam Table Approximator

- Saturation properties by temperature or pressure

- Approximate values for superheated steam

- Carnot Cycle Efficiency

- Efficiency calculation for ideal heat engines

- Heat Transfer Tool (Q = mcΔT)

- Solve for Q, m, c, or ΔT

- Entropy Change Calculator

- Handles constant pressure, constant volume, and isothermal processes

- Rankine Cycle Analysis

- Estimates thermodynamic states and cycle efficiency with approximate steam property formulas

- Refrigeration and Heat Pump Performance

- Computes COP for ideal and real cycles

- Interpolation Tool

- Linear interpolation from tabular values

- T-s and P-v Diagram Plotting

- Displays idealized dome curves and process paths

- Compressibility Factor (Z) via DAK Equation

- Solves for Z using Newton-Raphson iteration

- Data Save/Load Simulation

- Stores mock thermodynamic data for demonstration (currently in-memory only)

## Limitations:

- Steam property estimations are based on simplified correlations, not full IAPWS IF97 tables

- No persistence of saved data (files not written to permanent memory)

- Input prompts do not include units, so you have to keep track of the units of your works. (Can be fixed in future updates, but depends on my laziness)

- Poor error handling (Program doesnt prompt error for negative pressure value etc.)

## Installation Instructions

Copy ThermoCore.hpprgm to your calculator using HP Connectivity Kit

On the calculator, open the Program Catalog and select ThermoCore

Run the program to access the main menu

## License

MIT License. See LICENSE file (if included) for full terms.
