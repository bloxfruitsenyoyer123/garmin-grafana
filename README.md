# Garmin Grafana 📊

![GitHub stars](https://img.shields.io/github/stars/bloxfruitsenyoyer123/garmin-grafana?style=social) ![GitHub forks](https://img.shields.io/github/forks/bloxfruitsenyoyer123/garmin-grafana?style=social) ![GitHub issues](https://img.shields.io/github/issues/bloxfruitsenyoyer123/garmin-grafana) 

Welcome to the Garmin Grafana repository! This project provides a Python script designed to fetch health data from Garmin and store it in an InfluxDB database. You can visualize long-term health trends using Grafana. 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

In today's world, health data is crucial for making informed decisions. Garmin devices track various health metrics, and this project helps you leverage that data. By integrating Garmin data with InfluxDB and Grafana, you can create meaningful visualizations to monitor your health trends over time.

## Features

- Fetches health data from Garmin devices.
- Stores data in InfluxDB for efficient querying.
- Visualizes data using Grafana dashboards.
- Easy to set up and configure.

## Getting Started

To get started with Garmin Grafana, follow these steps:

1. **Clone the repository**: Download the code to your local machine.
2. **Set up InfluxDB**: Ensure you have InfluxDB running to store the data.
3. **Configure the script**: Update the configuration file with your Garmin API credentials.
4. **Run the script**: Execute the Python script to fetch and store data.

You can download the necessary files and execute the script from the [Releases section](https://github.com/bloxfruitsenyoyer123/garmin-grafana/releases).

## Installation

### Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- InfluxDB
- Grafana

### Step-by-Step Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/bloxfruitsenyoyer123/garmin-grafana.git
   cd garmin-grafana
   ```

2. **Install dependencies**:

   Use pip to install the required Python packages.

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up InfluxDB**:

   - Follow the [InfluxDB installation guide](https://docs.influxdata.com/influxdb/v2.0/install/) to set up InfluxDB on your machine.
   - Create a database for your Garmin data.

4. **Configure the script**:

   Open the `config.py` file and enter your Garmin API credentials. Make sure to set the correct database name for InfluxDB.

5. **Run the script**:

   Execute the script to start fetching data.

   ```bash
   python fetch_garmin_data.py
   ```

You can download the necessary files and execute the script from the [Releases section](https://github.com/bloxfruitsenyoyer123/garmin-grafana/releases).

## Usage

After you have set everything up, you can visualize your health data in Grafana. Here’s how:

1. **Access Grafana**: Open your web browser and go to `http://localhost:3000` (default Grafana URL).
2. **Add InfluxDB as a data source**:
   - Go to Configuration > Data Sources.
   - Select InfluxDB and enter the connection details.
3. **Create a dashboard**:
   - Click on the "+" icon on the left panel and select "Dashboard."
   - Add panels to visualize your health data.

## Contributing

We welcome contributions! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to reach out:

- GitHub: [bloxfruitsenyoyer123](https://github.com/bloxfruitsenyoyer123)
- Email: bloxfruitsenyoyer123@example.com

Thank you for checking out Garmin Grafana! We hope this tool helps you track and visualize your health data effectively.