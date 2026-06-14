# Parking Garage Counter System

A console-based Python application that helps a parking garage monitor the usage of its parking spaces. The program manages a minimum of 25 parking space records and provides a text-based menu for an attendant to add, search, display, and update spaces and generate a summary report of the garage's current state.

---

## Team Members

The members of **Group 7** are:

- **José Leyva**
- **Julio Mayedo Fernández**
- **William Riera**

---

## Project Description

The Parking Garage Counter System is a console-based Python application designed to help a parking garage monitor the usage of its parking spaces. The program manages a minimum of 25 parking space records. Each record stores a parking spot number, the license plate of the assigned vehicle, the vehicle type, and the current parking status.

Through a text-based menu, an attendant can:

- Add new records
- Search for a specific space
- Display all spaces
- Update the status of a space
- Generate a summary report that reflects the current state of the garage

---

## Problem Statement

Parking garages often rely on manual or informal methods to track which spaces are occupied, available, or reserved. These methods are time-consuming and prone to error, which can lead to overbooking, lost revenue, and frustrated customers. The Parking Garage Counter System addresses this problem by providing a simple, centralized tool that records the status of every parking space and produces an accurate summary on demand, allowing staff to make quick and informed decisions about space availability.

---

## Project Goals

- Maintain accurate records for at least 25 parking spaces.
- Track each space using one of three status values: **Occupied**, **Available**, or **Reserved**.
- Provide core operations to add, search, display, and update parking space records.
- Generate a summary report containing four reporting items.
- Demonstrate collaborative software development using a shared GitHub repository.

---

## Inputs

- Parking spot number, used as the identifier for each space.
- Vehicle license plate.
- Vehicle type (for example, car, motorcycle, or truck).
- Parking status (Occupied, Available, or Reserved).
- Menu selections that direct the program's actions.

## Outputs

- A formatted list of all parking space records.
- Search results for an individual parking space.
- Confirmation messages after a record is added or updated.
- A summary report showing total parking spaces, occupied spaces, available spaces, and reserved spaces.

---

## Assigned Roles

| Team Member   | Role                             | Responsibilities                                                     |
| ------------- | -------------------------------- | ---------------------------------------------------------------------|
| José Leyva    | Developer                        | Add/search functions, input validation                               |
| Julio Mayedo  | Developer                        | Display/update functions, summary report                             |
| William Riera | Lead Developer / Repository Mgr. | Repository setup, menu structure, solution architect, documentation  |

---

## Repository Structure

```
team7-parking-garage-counter-system/
├── README.md
├── documentation/    Project documentation and writeups
├── flowcharts/       Program flow and logic diagrams
├── sourcecode/       Python source files
└── screenshots/      Screenshots of the program running
```
