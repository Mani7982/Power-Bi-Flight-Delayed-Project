# Flight Insights: Delays and Cancelations
## Project Overview
This project involves the analysis of nearly 2,000,000 commercial flights from major US airports to understand patterns in flight delays and cancellations. Using Power BI, the raw data is transformed into a user-friendly, interactive dashboard that allows stakeholders to explore the data by various dimensions such as airport, airline, and day of the week.
## Dataset
The dataset used in this project contains information on nearly 2,000,000 commercial flights from major US airports. The data includes:

- **Flight details** (date, time, airline, origin, destination)
- **Flight status** (on-time, delayed, canceled)
- **Delay details** (reason, duration)

## Objectives
The primary goal of this project is to identify trends and factors contributing to flight delays and cancellations. Specifically, this project aims to:

- Analyse delay patterns across different airports and airlines
- Identify the most common reasons for flight delays and cancellations
- Provide stakeholders with an interactive tool to explore flight data by various dimensions

## Features
- **Interactive Dashboard**: A Power BI dashboard that allows users to drill down into flight delays and cancellations by airport, airline, day of the week, and more.
- **Relational Data Model**: A well-structured data model to ensure accurate and efficient analysis.
- **Custom Calculations**: DAX measures and calculated columns to derive insights from the data.

## Business Intelligence Workflow
This project follows a standard Business Intelligence workflow:

1. **Load and Transform Data**: The raw data is loaded into Power BI and transformed to ensure it is clean and ready for analysis.
2. **Build a Relational Data Model**: A relational data model is created to establish relationships between different tables.
3. **Add Calculated Columns & DAX Measures**: Custom calculations are added to derive additional insights from the data.
4. **Design the Dashboard**: The final step is to design a stunning, interactive dashboard that presents the insights in a clear and engaging way.
### Star Schema Data Modle:
![image](https://github.com/user-attachments/assets/9fd60f1b-b73a-4874-8b46-4128db76affb)


## Power BI Dashboard
![Flight Insights Dashboard](screenshot.png) *(Include a screenshot of your dashboard here)*

The Power BI dashboard includes the following key visualisations:

- **Flight Delays by Airport**: Visualise which airports have the highest delay rates.
- **Delay Reasons**: Understand the common causes of delays.
- **Flight Status by Airline**: Compare on-time performance across airlines.
- **Time-Series Analysis**: Explore delays and cancellations over time.

## Usage
Once you have the project opened in Power BI Desktop, you can explore the dashboard by interacting with the various visualisations. Use filters and slicers to drill down into specific details, such as delays by airport or cancellations by airline.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to submit a pull request.

## License
This project is licensed under the MIT License 

## Acknowledgments
This project was guided by the excellent tutorials provided by Maven Analytics. Special thanks to their team for creating comprehensive and easy-to-follow resources that helped me develop this analysis.
