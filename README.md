# COVID-19 Patient Management System

This repository contains a comprehensive system for managing COVID-19 patient data, including symptoms, test results, and location tracking. Designed to help healthcare providers manage patient information efficiently, the system supports various operations such as entering new patient data, updating existing records, and generating reports on high-risk locations and patient status.

## Features

- **Patient Data Entry**: Input detailed information about patients, including symptoms and travel history.
- **COVID-19 Test Result Management**: Update and track the COVID-19 test results for patients.
- **Risk Location Tracking**: Keep a record of high-risk COVID-19 locations that patients have visited.
- **Patient Recommendations**: Provide COVID-19 health recommendations based on the patient's symptoms and visited locations.
- **Data Storage**: Maintain a persistent storage of patient data and locations with file handling.
- **Feedback System**: Collect user feedback to improve system usability.

## Getting Started

### Prerequisites

- C++ Compiler (GCC recommended)
- Basic knowledge of file handling in C++

### Installation

1. Clone the repository:
```
git clone https://github.com/aniketdebnath/Covid-19-Monitoring-App.git
cd /path/to/your/source/code.
```
3. Compile the program using your C++ compiler:
```
g++ -o MainProgram.cpp main.cpp
```
3. Run the compiled program:
```
./MainProgram
```
### Usage

Upon running the program, you will be greeted with a menu that allows you to choose from several options:
```
Fill in Patient Details: Enter new patient data.
Upload Patient's COVID Test Result by ID: Update COVID-19 test results.
Display Updated High-Risk Locations for COVID: List all high-risk locations.
Update New COVID Positive Patient's Detail: Add new COVID-19 positive cases.
Display COVID Positive Patients Detail: Show details of all COVID-19 positive patients.
Exit the Program: Save all changes and exit the program.
```
Navigate through the menu by entering the number corresponding to your choice.

### File Structure
The data is stored across multiple files in a predefined directory structure:
```
Database/Patient Database.txt: Stores patient information.
Database/Symptom Database.txt: Contains possible COVID-19 symptoms.
Database/COVID location Database.txt: Lists high-risk locations.
Database/User Feedback.txt: Captures user feedback on system usability.
```
## Contributing

Contributions are welcome! If you have suggestions or enhancements, feel free to fork this repository and submit a pull request. You can also open an issue if you find any bugs or have feature requests.
