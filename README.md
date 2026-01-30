# LV Log
## Introduction
A lightwieght and extendable Logging Library for LabVIEW
## Features
- Uses sinks to allow you to write to one or more mediums, including:
  - Text File
  - G-CLI
  - TDMS File
  - LabVIEW Queue
  - Rotating Daily Text File
- Get logger by name: Use anywhere in your code without passing references
- Filter Globally by Debug Level (DEBUG, INFO, WARN, ERROR, FATAL)
- Create named loggers to easily identify where the log is coming from
- Extensible sinks: Users can create their own sinks for custom log outputs
- Define Sinks for all loggers adn/or idividual loggers
## Upcoming features
- Filter Debug Level by logger
- Rotating File Size Sink
## Installation
Install from the Releases page on this GitHub with the .vip package
## Testing
### Pre Requisites
Please install LUnit to run the unit tests: https://www.vipm.io/package/astemes_lib_lunit/
### Running
Use LUnit to "Run All LUnit Tests in this Project" in LV Logging.lvproj OR Testing.lvproj (They run the same suite) 
## Usage
### Quick Start
<img width="554" height="134" alt="lvlog_quickstart" src="https://github.com/user-attachments/assets/0f619b53-2ed0-4098-a1ad-afac1cf6e45e" />
