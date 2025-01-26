# Optimizing Service Efficiency in the Fast-Food Industry: A Case Study of McDonald's

<p align="center">
  <img src="Report/mc.png" alt="Alt text">
</p>

This repository contains an analysis of strategies to enhance service efficiency at McDonald's, focusing on reducing queue times and optimizing resource allocation through data-driven insights and simulation modeling.

## Table of Contents
- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Data Collection](#data-collection)
- [Models](#models)
- [Results and Recommendations](#results-and-recommendations)
- [File Descriptions](#file-descriptions)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [License](#license)

---

## Introduction
Service time plays a pivotal role in the fast-food industry. This project examines McDonald's operations, proposing solutions to reduce wait times and enhance customer satisfaction while maintaining profitability.

---

## Project Objectives
1. Minimize customer queue times.
2. Optimize resource allocation to reduce employee idle time.
3. Increase revenue through operational improvements informed by simulation insights.

---

## Data Collection
### Key Details
- **Observation Period**: Two weeks (peak hours: 11 AM - 2 PM).
- **Metrics Captured**:
  - Arrival times.
  - Wait times.
  - Order processing times.
  - Ordering methods (counter vs. self-service).
  - Dining preferences (eat-in vs. takeout).

---

## Models
The study utilized **JaamSim**, a simulation software, to replicate McDonald's operations and test optimization strategies.

### Key Elements:
- **Customer Arrival**:
  - Dine-in: Normal distribution (mean = 1.7 mins, std dev = 2.9 mins).
  - Drive-thru: Exponential distribution (mean = 4.3 mins).
- **Order Processing**:
  - Decision branches for self-service vs. counter (80% self-service, 20% counter).
- **Queue Management**:
  - Simulated bottlenecks in drive-thru, kitchen, and self-service queues.

### Results:
- Adding one kitchen employee reduced bottlenecks, increasing revenue by $100 per 8-hour shift.
- Monte Carlo simulations confirmed the accuracy of the model.

---

## Results and Recommendations
1. **Install Digital Signage**:
   - Directs drive-thru customers to available lanes, reducing congestion.
2. **Add Staff During Peak Hours**:
   - Deploy additional employees to enhance service speed.
3. **Efficiency Gains**:
   - Increased service efficiency from 73% to 89%.

---

## File Descriptions
- **`FINAL REPORT - Management.pdf`**: Comprehensive analysis report.
- **`Jaam Sim project.cfg`**: Configuration file for the simulation model.
- **`mcd model.xlsx`**: Dataset used for analysis and modeling.
- **`OPTIMIZING SERVICE EFFICIENCY IN THE FAST FOOD INDUSTRY.pptx`**: Presentation summarizing findings.

---

## Technologies Used
- **JaamSim**: Simulation modeling.
- **Microsoft Excel**: Data collection and analysis.
- **Monte Carlo Simulation**: Validation of model accuracy.

---

## Contributors
- **Harshan Ragavandar Ramesh**
- **Muhammad Miqdad**
- **Srikar Varma Nadimpalli**
- **Ruthwick Reddy Podduturi**

---

## License
This project is licensed under the [MIT License](LICENSE).

For further questions or contributions, please create an issue or contact the contributors directly.

