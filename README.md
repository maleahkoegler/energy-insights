# Energy Insights – My Energy Profile

## Project Overview

**My Energy Profile – personal energy consumption in a global context** is an interactive web project that helps users understand their personal energy consumption by placing it into a national and global context.

Users can configure personal parameters such as country of origin, age, household size, living situation, and heating type. Based on these inputs, the platform dynamically updates data visualizations, enabling meaningful comparisons with national averages, other countries, and global benchmarks.

The goal of the project is to make complex energy and climate data **accessible, comparable, and personally relevant**.

---

## Current Project State

At its current stage, the project consists of:

* A responsive **landing page** with a clear project vision
* A modern UI with refined typography, spacing, and branding
* Navigation structure prepared for future sections
* A design-focused branch (`ui-design`) used for UI and branding improvements

The application logic and interactive data visualizations will be implemented in the next development phase.

---

## Planned Features & Sections

### 1. My Energy Consumption

Personalized estimates and comparisons of energy use.

**Planned data & indicators:**

* Total energy consumption per year (kWh per capita)
* Comparison with national averages and other countries
* Breakdown by sector:

  * Household energy
  * Mobility
  * Indirect energy consumption (goods & services)

**Data sources:**

* Our World in Data – Energy production & consumption

  * [https://ourworldindata.org/energy-production-consumption](https://ourworldindata.org/energy-production-consumption)
  * [https://ourworldindata.org/energy-mix](https://ourworldindata.org/energy-mix)
  * [https://ourworldindata.org/electricity-mix](https://ourworldindata.org/electricity-mix)
* World Bank – Electricity consumption per capita

  * [https://databank.worldbank.org/reports.aspx?source=2&series=EG.USE.ELEC.KH.PC](https://databank.worldbank.org/reports.aspx?source=2&series=EG.USE.ELEC.KH.PC)
* International Energy Agency (IEA)

  * [https://www.iea.org/data-and-statistics/data-product/energy-efficiency-indicators-highlights](https://www.iea.org/data-and-statistics/data-product/energy-efficiency-indicators-highlights)

---

### 2. Energy Costs

Comparison of electricity prices across countries and regions.

**Planned indicators:**

* Average electricity prices by country
* Household electricity cost comparisons

**Data sources:**

* World Bank – Electric prices

  * [https://databank.worldbank.org/embed/Electric-Prices-by-Country/id/7b12e700](https://databank.worldbank.org/embed/Electric-Prices-by-Country/id/7b12e700)
* Global Petrol Prices

  * [https://www.globalpetrolprices.com/electricity_prices/](https://www.globalpetrolprices.com/electricity_prices/)

---

### 3. Availability of Energy

Exploration of global access to energy and electricity.

**Key questions:**

* When did different regions gain full access to electricity?
* Which regions still face energy access challenges?

**Data source:**

* IEA – SDG7 Database

  * [https://www.iea.org/data-and-statistics/data-product/sdg7-database](https://www.iea.org/data-and-statistics/data-product/sdg7-database)

---

### 4. My Energy Mix

Detailed analysis of the energy sources used in a selected country.

**Planned content:**

* Composition of energy sources:

  * Coal
  * Oil
  * Natural gas
  * Nuclear
  * Renewables
* Electricity mix by country
* Historical development of national energy mixes
* Energy imports and dependencies

**Data sources:**

* Our World in Data – Energy datasets

  * [https://github.com/owid/energy-data](https://github.com/owid/energy-data)
* U.S. Energy Information Administration (EIA)

  * [https://www.eia.gov/opendata/index.php#bulk-downloads](https://www.eia.gov/opendata/index.php#bulk-downloads)

---

### 5. My Household

Energy consumption within a household broken down by usage.

**Planned breakdown:**

* Heating
* Hot water
* Lighting
* Appliances
* Cooking

**Data source:**

* IEA – Energy efficiency indicators

  * [https://www.iea.org/data-and-statistics/data-product/energy-efficiency-indicators-highlights](https://www.iea.org/data-and-statistics/data-product/energy-efficiency-indicators-highlights)

---

### 6. Energy Transition in Context

Placing personal energy use within the broader energy transition.

**Planned comparisons:**

* Share of renewable energy by country
* Development of renewables over time
* National targets vs. actual progress toward climate neutrality
* CO₂ intensity of energy production

**Data sources:**

* Our World in Data – Renewable energy

  * [https://ourworldindata.org/renewable-energy](https://ourworldindata.org/renewable-energy)
* Eurostat – Renewable energy statistics

  * [https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Renewable_energy_statistics](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Renewable_energy_statistics)
* IEA – Greenhouse gas emissions

  * [https://www.iea.org/data-and-statistics/data-product/greenhouse-gas-emissions-from-energy-highlights](https://www.iea.org/data-and-statistics/data-product/greenhouse-gas-emissions-from-energy-highlights)
* Global Carbon Atlas & Carbon Monitor

  * [https://globalcarbonatlas.org](https://globalcarbonatlas.org)
  * [https://carbonmonitor.org](https://carbonmonitor.org)

---

### 7. What If? – Interactive Scenarios

Exploration of hypothetical behavioral and systemic changes.

**Planned scenarios:**

* What if I switch to a heat pump?
* What if I commute by public transport instead of by car?
* What if my country had 100% renewable energy?
* What if everyone consumed as much energy as I do?

These scenarios aim to illustrate individual and collective impacts on energy demand and emissions.

---

### 8. Global Comparison

Global positioning of energy consumption patterns.

**Planned visualizations:**

* Per capita energy consumption by country
* Global rankings and distributions

**Data source:**

* The Global Economy – Energy use per capita

  * [https://www.theglobaleconomy.com/rankings/Energy_use_per_capita/](https://www.theglobaleconomy.com/rankings/Energy_use_per_capita/)

---

## Tech Stack (Planned)

* **HTML5 / CSS3** – Structure and styling
* **JavaScript** – Interactivity and data handling
* **Data visualization libraries** (planned):

  * D3.js or similar
* **External open datasets** (OWID, IEA, World Bank, EIA)

---

## Project Goal

This project aims to bridge the gap between **personal behavior** and **global energy systems** by:

* Making energy data understandable
* Encouraging reflection on personal consumption
* Highlighting inequalities and transition pathways

---

## Status

🚧 **Work in progress** – UI and branding phase completed, data integration and interactive visualizations upcoming.

---

## License

This project uses publicly available data from the listed sources. Licensing details depend on the respective data providers.

---

*Built to understand and contextualize global energy consumption.*
