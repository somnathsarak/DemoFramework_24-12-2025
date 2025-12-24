# DemoFramework_24-12-2025

## Selenium Test Automation Framework
**Created on:** December 24, 2025

### Overview
A comprehensive Java-based Selenium test automation framework for testing the Orange HRM application. This framework demonstrates industry best practices including Page Object Model (POM), TestNG, Maven, and Extent Reports integration.

### Technology Stack
- **Language:** Java
- **Build Tool:** Maven
- **Test Framework:** TestNG
- **Web Driver:** Selenium WebDriver 4.15.0
- **Reporting:** Extent Reports 5.1.1
- **Logging:** Log4j

### Framework Features
✅ Page Object Model (POM) Design Pattern
✅ PageFactory for Web Element Localization
✅ Automatic Test Retry Mechanism
✅ Event-Based Test Listening
✅ Detailed Test Execution Logging
✅ Configuration Management via Properties File
✅ Support for Multiple Browsers (Chrome, Firefox, Edge)
✅ Extent Reports Integration for Enhanced Reporting
✅ CI/CD Ready Structure

### Project Structure
```
DemoFramework_24-12-2025/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/automation/
│   │   │       ├── base/          # Base classes
│   │   │       ├── factory/       # WebDriver factory
│   │   │       ├── utils/         # Utility classes
│   │   │       └── listeners/     # TestNG listeners
│   │   └── resources/
│   │       └── config.properties  # Configuration file
│   └── test/
│       ├── java/
│       │   └── com/automation/
│       │       ├── pages/         # POM classes
│       │       └── tests/         # Test classes
│       └── resources/
├── config/                         # Configuration folder
├── reports/                        # Test reports
├── test-output/                    # TestNG output
├── pom.xml                        # Maven configuration
├── testng.xml                     # TestNG suite configuration
└── README.md
```

### Getting Started

#### Prerequisites
- Java 8 or higher
- Maven 3.6+
- Chrome/Firefox/Edge browsers

#### Installation
1. Clone the repository:
   ```
   git clone https://github.com/somnathsarak/DemoFramework_24-12-2025.git
   ```

2. Navigate to the project directory:
   ```
   cd DemoFramework_24-12-2025
   ```

3. Install dependencies:
   ```
   mvn clean install
   ```

#### Running Tests
```
mvn test
```

#### Running Specific Test Suite
```
mvn test -Dsuite=testng.xml
```

### Configuration
Modify `src/main/resources/config.properties` to set:
- Application URL
- Browser type
- Login credentials
- Wait timeouts
- Report path

### Test Reports
Extent Reports are generated in the `reports/` directory after each test execution.

### Repository Timeline
Created: **December 24, 2025**
Framework Version: **1.0**

### Author
Somnath Sarak

### License
Open Source
