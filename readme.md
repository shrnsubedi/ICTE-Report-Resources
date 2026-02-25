# 🔌 Energy Consumption Analysis of MQTT Brokers  

This project analyzes and compares the energy usage of different MQTT brokers. The goal is to assess the efficiency of lightweight communication protocols commonly used in IoT, with a focus on their energy profiles under various workloads. The paper for the project can be found in the repository.

## Project Description

MQTT (Message Queuing Telemetry Transport) is a widely used protocol in IoT systems. This analysis explores:
- Energy consumption of different MQTT brokers (e.g., Mosquitto, EMQX, HiveMQ)
- Performance under varied message frequencies and payload sizes
- Comparison of energy profiles using real system measurements

## Key Features

- Structured benchmarking of MQTT brokers
- Power usage data collection and analysis
- Visualization of energy consumption patterns
- Insight into protocol efficiency for sustainable IoT design

## Technologies Used

- Python (Jupyter Notebook)
- pandas
- matplotlib / seaborn
- MQTT protocol tools
- Energy profiling tools (external, e.g., power meters or OS-level stats)

## Files

- `ICTE_analysis_full.ipynb`: Complete notebook with data loading, processing, and visual analysis.
- `ICTE-raw-data.csv`: File for data exported to csv
