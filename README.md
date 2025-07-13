# Hospital Management System

This is a simple console-based Hospital Management System built in Python. It allows hospital staff to manage patients across various specializations based on urgency levels.

## Features

* Add new patients with urgency levels:

  * 0: Normal
  * 1: Urgent
  * 2: Super Urgent
* View patients in all specializations
* Get the next patient based on priority
* Remove a leaving patient
* Dummy data is preloaded for testing

## Directory Structure

```
smriti2805-hospital-management/
└── hms.py
```

## Getting Started

### Requirements

* Python 3.6 or higher

### Running the Program

```bash
python hms.py
```

Follow the on-screen prompts to interact with the application.

## Code Structure

### `Patient` Class

Represents individual patients with name and urgency status. Supports sorting by urgency.

### `HospitalManger` Class

Contains core logic for managing patients by specialization. Handles adding, removing, and retrieving patients.

### `FrontendManager` Class

Handles user interaction through a menu-driven interface. Calls methods from `HospitalManger`.

## Example Menu

```
Program Options:
1) Add new patient
2) Print all patients
3) Get next patient
4) Remove a leaving patient
5) End the program
```

## Notes

* Each specialization can have a maximum of 10 patients.
* Patients are automatically sorted based on urgency.
* Sorting is stable; patients with the same urgency retain their order.

## License

This project is provided for educational purposes and has no associated license.


