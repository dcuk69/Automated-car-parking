# Automated Car Parking System

An automated car parking system that uses **IR sensors** for real-time slot detection and an LCD to display current parking availability. The architecture is modular and scalable, allowing easy expansion to more slots or levels.

## Features

- Real-time vehicle detection for each parking slot using IR sensors  
- LCD display showing total, occupied, and available slots  
- Modular design for adding more slots with minimal code changes  
- Low-cost and easy-to-deploy system for small to medium parking areas  

## Hardware Requirements

- Microcontroller board (e.g., Arduino Uno)  
- IR sensors (one per parking slot)  
- 16x2 character LCD  
- Jumper wires, resistors, breadboard or PCB  
- Suitable power supply  

## How It Works

- Each parking slot is monitored by an IR sensor to detect the presence of a vehicle.  
- The microcontroller continuously reads sensor inputs and calculates the number of occupied and free slots.  
- The LCD is updated in real time to show current parking availability.  
- The code and wiring are structured to make adding new slots as simple as updating pin mappings and slot count.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/automated-car-parking-system.git
   cd automated-car-parking-system
