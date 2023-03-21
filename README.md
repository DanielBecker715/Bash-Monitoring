# Bash Monitoring
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Welcome to Bash Monitoring System, a lightweight monitoring solution for Linux. This project was developed as part of my vocational school project and I wanted to create something fun and useful at the same time.

## Requirements

To use Bash Monitoring System, you need to have the following requirements installed:

+ Operating System: Linux
+ Required packages: bc, screen

## Installation
To install Bash Monitoring System, please make sure that you have crontabs installed for AutoRestart and AutoDatabaseClear. Follow the steps below to install:

1.  Clone the repository:
`git clone https://github.com/DanielBecker715/Bash-Monitoring.git`
2. Navigate to the cloned directory: cd bash-monitoring
`cd bash-monitoring`
3. Set up crontabs for AutoRestart and AutoDatabaseClear using the following commands:
```bash
@reboot bash /monitor/runMonitoring.sh
0 0 * * * bash /monitor/cleanDatabase.sh
```

## Usage
Once the installation is complete, you can start using Bash Monitoring System. Run the following command to start monitoring your system:
`bash /monitor/runMonitoring.sh`

## License
This project is licensed under the MIT License - see the LICENSE file for details.
