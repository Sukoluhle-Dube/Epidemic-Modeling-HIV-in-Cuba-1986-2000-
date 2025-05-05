# Epidemic Modeling: HIV in Cuba (1986-2000)

## Project Overview

This project explores the HIV/AIDS epidemic in Cuba between 1986 and 2000 using data visualization and basic epidemic modeling. Cuba's unique national HIV control strategies, including early testing, contact tracing, and quarantine, are examined in the context of the epidemic's progression.

## Data Source

The data used in this project represents the number of HIV cases, AIDS cases, and deaths from AIDS in Cuba from 1986 to 2000. The data is compiled from publicly available sources related to Cuba's HIV/AIDS program during this period.

## Methodology

1. **Data Visualization:** The project begins by loading and visualizing the data using libraries like Pandas, Matplotlib, and Seaborn. Various charts are created to illustrate:
   - Trends over time (line plots)
   - Cumulative impact (area charts)
   - Case breakdown per year (stacked bar charts)
   - Ratio of AIDS to HIV cases (line plot)
   - Correlations between variables (heatmap)

2. **Epidemic Modeling:** A basic SIA (Susceptible-Infected-AIDS) compartmental model is introduced to simulate the epidemic's dynamics. The model's parameters (transmission rate, progression rate, and death rate) are estimated using a combination of assumptions and data fitting techniques.

3. **Control Strategies:** The impact of potential control strategies is investigated by introducing control parameters that modify the model's parameters. This allows for an exploration of how different interventions could have affected the epidemic's trajectory.

## Findings

- The visualizations reveal a sharp rise in HIV cases in the late 1980s and early 1990s, with a peak around 2000.
- AIDS cases and deaths followed a lagged but upward trend, reflecting the progression from HIV to AIDS.
- The model fit indicates a good correlation between the simulated and actual HIV cases, suggesting that the SIA model captures the essential features of the epidemic.
- Incorporating control parameters into the model highlights the potential effectiveness of various interventions, such as reducing transmission rates or improving healthcare, in mitigating the epidemic's impact.

## Limitations

- The model is a simplified representation of a complex biological system and does not account for all factors influencing the epidemic's spread.
- Data limitations may exist, including potential underreporting or variations in data collection methods over time.

## Conclusion

This project provides insights into the HIV/AIDS epidemic in Cuba during a critical period. The data visualization and modeling approaches allow for an exploration of trends, underlying dynamics, and potential impacts of control strategies. The findings highlight the importance of early intervention, continuous monitoring, and evidence-based public health measures in addressing the challenges posed by HIV/AIDS.

## Files in the Repository

- `epidemic_modeling_cuba.ipynb`: Jupyter Notebook containing the project's code and analysis.
- `data.csv`: Data file containing the HIV/AIDS statistics.
- `README.md`: Project documentation.

## Acknowledgements

The creators of this project would like to acknowledge the researchers, public health professionals, and organizations that have contributed to understanding and combating the HIV/AIDS epidemic in Cuba and worldwide.
