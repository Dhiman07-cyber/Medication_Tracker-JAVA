# Medication Tracker - Java

A comprehensive Java Swing application for tracking and managing medication schedules with reminder functionality.

## Features

- **Add Medications**: Input medicine name, dosage, time, and frequency
- **Edit/Delete**: Modify or remove existing medications
- **Smart Reminders**: View next upcoming medication reminder
- **Flexible Dosage**: Choose from presets (1 Tablet, 2 Tablets, 5ml, 10ml) or enter custom dosage
- **Multiple Frequencies**: Daily, Alternate Days, Weekly, Every 6/8 Hours, One-time, or Custom
- **User-Friendly Interface**: Clean, intuitive GUI with scrollable medication list

## Screenshots

The application features a modern Swing interface with:
- Form-based medication entry
- Card-style medication display
- Real-time next reminder updates
- Edit and delete functionality for each medication

## Requirements

- Java 8 or higher
- No external dependencies required (uses built-in Swing)

## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Dhiman07-cyber/Medication_Tracker-JAVA.git
   cd Medication_Tracker-JAVA
   ```

2. **Compile the Java files:**
   ```bash
   javac MedicationTracker.java
   ```

3. **Run the application:**
   ```bash
   java MedicationTracker
   ```

   Or use the provided Run script:
   ```bash
   ./Run
   ```

## How to Use

1. **Adding Medications:**
   - Enter the medicine name
   - Select or enter custom dosage
   - Set the time using hour/minute spinners and AM/PM
   - Choose frequency from dropdown
   - Click "Add Medication"

2. **Managing Medications:**
   - View all added medications in the scrollable list
   - Click "Edit" to modify existing medications
   - Click "Delete" to remove medications
   - Monitor the "Next Reminder" display for upcoming doses

3. **Time Format:**
   - Uses 12-hour format with AM/PM selection
   - Automatic conversion to 24-hour format for internal processing

## Project Structure

```
Medication_Tracker-JAVA/
├── MedicationTracker.java    # Main application class with GUI
├── Medication.class          # Compiled class file
├── PROJECT.java             # Additional project file
├── Run                      # Execution script
└── README.md               # This file
```

## Technical Details

- **Language**: Java
- **GUI Framework**: Swing
- **Architecture**: Object-oriented with separate Medication class
- **Time Handling**: Uses Java 8 LocalTime for accurate time management
- **Layout**: BorderLayout with GridBagLayout for form components

## Contributing

Feel free to fork this repository and submit pull requests for improvements or bug fixes.

## License

This project is open source and available under the MIT License.

## Author

Dhiman Saikia - [GitHub Profile](https://github.com/Dhiman07-cyber)