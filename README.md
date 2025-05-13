# COVID-19 Data Analysis Project

## Project Description
This project analyzes COVID-19 data to explore and visualize trends in cases, deaths, and vaccinations across different countries of interest (Kenya, USA, and India). The analysis provides insights into the progression of the pandemic, comparing impacts across regions and examining vaccination rollouts.

## Objectives
- Load and clean COVID-19 data from Our World in Data
- Compare case progression and death rates between Kenya, USA, and India
- Analyze vaccination progress across these countries
- Generate visualizations to clearly illustrate trends and patterns
- Extract meaningful insights from the data analysis

## Tools and Libraries Used
- **Python**: Primary programming language
- **Jupyter Notebook**: Interactive development environment
- **pandas**: Data manipulation and analysis
- **matplotlib**: Data visualization
- **seaborn**: Enhanced data visualization
- **plotly** (optional): For creating interactive choropleth maps
- **VS Code with Jupyter extension**: Development environment

## Dataset
The analysis uses the COVID-19 dataset from Our World in Data, which includes:
- Daily and cumulative COVID-19 cases and deaths
- Vaccination data
- Population information
- Geographic identifiers

## How to Run the Project
1. **Prerequisites**:
   - Python 3.6+
   - Required libraries: pandas, matplotlib, seaborn
   - Optional: plotly (for choropleth maps)

2. **Setup**:
   ```bash
   # Clone the repository (if applicable)
   git clone https://github.com/NjokiBeth/python-EDA.git)
   
   # Install required packages
   pip install pandas matplotlib seaborn
   pip install plotly  # Optional, for choropleth maps
   ```

3. **Running the Notebook**:
   - Ensure the COVID-19 dataset file (`owid-covid-data.csv`) is in the project directory
   - Open the Jupyter notebook (`covid_analysis.ipynb`) in VS Code with the Jupyter extension or JupyterLab
   - Run the cells sequentially to generate the analysis and visualizations

4. **Alternative Execution**:
   - You can also run the notebook in Google Colab or any other Jupyter-compatible environment

## Key Insights

### 1. Case Progression
The United States experienced the highest total number of COVID-19 cases among our selected countries, followed by India and Kenya. The data shows distinctive waves of infection in all three countries, though with different timing and magnitudes.

### 2. Death Rates
The death rate (deaths as a percentage of confirmed cases) varied significantly between countries. This could be attributed to differences in healthcare system capacity, testing strategies, demographics, and reporting methods.

### 3. Vaccination Rollout
The United States initiated vaccination programs earlier and achieved higher vaccination rates more quickly than India and Kenya. This reflects global inequities in vaccine access and distribution capacity. Vaccination rates correlate with reductions in death rates in subsequent waves of infection.

### 4. Disparities in Impact
When normalizing for population size (cases per million), the relative impact of COVID-19 varies significantly. While absolute numbers might be higher in populous countries like India, the per capita impact provides a better measure of how severely each country was affected.

### 5. Data Limitations
Several limitations should be noted when interpreting this analysis:
- Testing capacity varied widely between countries and over time
- Reporting criteria and methods differed between countries
- Data collection systems improved over time, affecting trend analysis
- Vaccination data has more gaps than case/death data, particularly for earlier periods

## Reflections
This project demonstrates the power of data analysis and visualization in understanding complex global phenomena like the COVID-19 pandemic. The analysis reveals how socioeconomic factors, healthcare infrastructure, and policy decisions influenced the trajectory of the pandemic differently across countries.

The visualization techniques employed help transform raw data into actionable insights, providing a clearer picture of how the pandemic evolved over time. This type of analysis is crucial for informing public health responses to future global health crises.

Future extensions of this work could include predictive modeling, incorporation of policy intervention data, or expansion to include more countries for a more comprehensive global analysis.

## License
This project is shared under the [MIT License](LICENSE).
