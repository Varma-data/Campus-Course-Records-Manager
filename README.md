# Campus Course & Records Manager (CCRM)

## Overview
Campus Course & Records Manager (CCRM) is a comprehensive Java SE application for managing students, courses, enrollments, grades, and academic records. It demonstrates modern Java features, OOP principles, and professional code structure.

## Features
- Student and course management (CRUD)
- Enrollment tracking and transcript generation
- Grade analytics and reporting
- CSV import/export and automated backups
- Stream API, lambdas, and modern Java practices
- Exception handling and custom exceptions
- Design patterns: Singleton, Builder

## Project Structure
```
java project/
├── src/          # Source code
├── bin/          # Compiled classes
├── data/         # Application data and exports
├── test-data/    # Sample CSV files
├── backups/      # Automated backups
├── screenshots/  # Documentation images
├── README.md     # Project documentation
└── USAGE.md      # Usage guide
```

## Quick Start
1. Ensure JDK 17 or later is installed.
2. Compile:
	```bash
	javac -d bin -cp src -sourcepath src src\edu\ccrm\CCRM.java
	```
3. Run:
	```bash
	java -cp bin edu.ccrm.CCRM
	```
4. (Optional) Run with assertions:
	```bash
	java -ea -cp bin edu.ccrm.CCRM
	```

## Example Menu
```
Campus Course & Records Manager (CCRM) v1.0
========================================
1. Student Management
2. Course Management
3. Enrollment Management
4. Grade Management
5. File Operations (Import/Export)
6. Reports & Analytics
7. Backup Operations
8. Platform Information
0. Exit
```

## Documentation
- `README.md`: Project overview and setup
- `USAGE.md`: Usage instructions and workflows
- `test-data/`: Sample CSV files for import/export

## Requirements
- JDK 17 or later
- Windows 10/11 (tested)

## Educational Value
- Demonstrates OOP, modern Java, design patterns, and professional structure
- Suitable for learning Java SE and best practices

---
**Project Status:** ✅ COMPLETE – All requirements fulfilled with comprehensive implementation and documentation.