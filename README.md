This repository contains the electrical hardware design, power‑management circuitry, and thermal/electrical simulation work I developed for the Catalytic Converter Optimizer.
It is an inductive pre‑heating system intended to reduce cold‑start emissions in gasoline vehicles.
This project includes the electrical hardware design, power‑management circuitry, and MATLAB‑based thermal/electrical simulations that supported the patent application US20220042437A1.

Cold‑start emissions account for up to 90% of total pollutants produced during the first minute of engine operation.
This optimizer addresses that problem using inductive heating, dual‑battery power management, and a microcontroller‑driven closed‑loop control system.

The system uses a copper or aluminum induction coil to heat the catalytic converter directly and efficiently.
Dual‑Battery Power Architecture:
* The vehicle battery powers the heater during ignition
* Li‑Po 4S battery pack maintains idle heating
* LVD circuit prevents over‑discharge and protects battery life

A microcontroller continuously monitors catalytic converter temperature and switches heating modes based on thresholds.
MATLAB thermal simulations demonstrated up to 70% reduction in cold‑start emissions, validating the effectiveness of rapid pre‑heating.
