# Attendance-System
A School Attendance System is a simple app for tracking student attendance. Teachers mark attendance daily, and students can view their records. It saves time and keeps records accurate.

## Features

### For Teachers
- **Class Management**: View all assigned classes and their details
- **Attendance Tracking**: Mark student attendance for each class session
- **Attendance History**: View historical attendance records for each class
- **Analytics**: See attendance percentages and patterns

### For Students
- **Attendance Overview**: View personal attendance statistics and summaries
- **Class List**: See all enrolled classes and their details
- **Attendance Records**: Track attendance status for all classes

## Technology Stack
- HTML5
- CSS3 with modern styling
- JavaScript (ES6) for interactivity
- Python's built-in HTTP server for demo deployment

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)

### Demo Accounts
The system has two demo accounts:

1. **Teacher Demo**
   - Email: teacher@example.com
   - Password: password (or any password for demo)

2. **Student Demo**
   - Email: student@example.com
   - Password: password (or any password for demo)

### Running the Application
1. Start the application server by running:
   ```
   python -m http.server 5000 --bind 0.0.0.0
   ```
2. Open your web browser and navigate to the application URL
3. Use the demo buttons to populate login credentials, then click "Sign In"
4. Navigate through the interface to explore the features

## Usage Guide

### Teacher Interface
1. **Dashboard**: After login, you'll see your class list
2. **Mark Attendance**: Click the "Mark Attendance" button on any class card
3. **Toggle Attendance**: Use the switches to mark students present/absent
4. **Submit**: Click "Submit Attendance" to save the records
5. **View History**: Click "History" on any class card to see past attendance records
6. **Expand Details**: Click on any date to view the detailed attendance for that day

### Student Interface
1. **Overview Tab**: Shows attendance summary, statistics, and recent records
2. **Classes Tab**: Shows a list of all enrolled classes and their details
3. **Attendance Rate**: View your overall attendance percentage
4. **Records**: See individual attendance records with date and status

## Project Structure

- `index.html`: Main application file containing the HTML, CSS, and JavaScript
- `README.md`: This documentation file

## Design Principles

The application follows these key design principles:
- **Simple and Clean UI**: Material-inspired design with intuitive navigation
- **Responsive Layout**: Works on desktop and mobile devices
- **Role-Based Access**: Different interfaces for teachers and students
- **Visual Feedback**: Clear status indicators and interactive elements

## Future Enhancements

- Integration with real student database systems
- Export attendance reports to PDF or Excel
- Mobile application with offline capabilities
- Email notifications for low attendance
- Biometric attendance options (fingerprint, facial recognition)

## Contributing

While this is a demo project, suggestions for improvements are welcome.

## License

This project is available as an educational resource.
