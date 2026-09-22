# U.S. Trade & Production Analysis

An interactive research project exploring U.S. exports, imports, domestic production, industrial concentration, and regional economic activity.

I built this project to better understand how international trade connects with the physical U.S. economy — what the country produces, what it imports and exports, where production is concentrated, and how dependent different industries may be on domestic and international supply chains.

Rather than presenting the analysis as a single dashboard, the project contains several connected analytical tools covering exports, imports, production, and regional economic activity.

## Project Components

### U.S. Export Dashboard

The primary export dashboard analyzes approximately **$1.896 trillion in 2024 U.S. domestic goods exports** across:

- 21 HS industry sections
- 1,222 products
- Sector export shares
- Product-level export concentration
- HHI concentration measures
- Major export products
- Export anomalies
- Regional and mega-region comparisons

The dashboard allows individual sectors to be explored in greater detail, including their largest exported products and the degree to which exports are concentrated among a smaller number of products.

### U.S. Import Foundation

The import dashboard uses an **audited 2024 base with a 2025 macroeconomic update**.

It explores:

- U.S. goods imports and exports
- Import end-use categories
- Domestic exports vs. total exports
- Trade balances
- Import/export ratios
- Supplier concentration
- Related-party trade
- Production-oriented imports
- Industry and product-level trade patterns

The project distinguishes between official observed data, modeled estimates, and provisional data rather than treating every value as equally certain.

A confidence framework is used to identify:

- **High confidence** — direct official data or simple calculations from official data
- **Medium confidence** — recognized concordances or moderate modeling
- **Low / pending** — estimates requiring additional assumptions or primary-source verification

### Tradable Production Flow Model

This component explores the relationship between state economic output and international trade across all 50 states.

The model includes:

- State GDP
- Estimated tradable share of GDP
- Estimated tradable GDP
- State exports
- Export intensity
- Export Coverage Ratio (exports ÷ estimated tradable GDP)
- Tradable vs. non-tradable industry classifications
- Production-flow modeling

The model is intended as an analytical framework rather than an official economic statistic. Several calculations rely on assumptions about the tradability of industries and national input-output relationships.

### U.S. Metro Population Explorer

An additional interactive dashboard compares 69 U.S. urban regions using approximate population figures.

The dataset includes metro areas, combined statistical areas, regional corridors, and several broader regional concepts. Because these are not all identical Census geographic classifications, this component is intended as a comparative visualization rather than an official population ranking.

## Data & Research Approach

The project primarily works with U.S. trade and economic statistics and draws on government datasets and releases including the **U.S. Census Bureau** and **Bureau of Economic Analysis (BEA)**.

A major part of the project has been reconciling differences between datasets and definitions.

Examples include:

- Separating domestic exports from total exports that include re-exports
- Distinguishing Census-basis and balance-of-payments trade figures
- Reviewing HS product and industry classifications
- Standardizing concentration measurements
- Separating observed values from modeled estimates
- Auditing earlier assumptions when newer or stronger source data becomes available

Some detailed HS-level values remain provisional pending direct primary-data verification. These limitations are identified within the dashboards rather than hidden from the analysis.

## Tools & Methods

- HTML
- JavaScript
- Chart.js
- Interactive data visualization
- Trade-data analysis
- Supply-chain analysis
- Economic data analysis
- HHI concentration analysis
- Data auditing and validation
- Scenario and assumption modeling
- AI-assisted research and development

## Repository Structure

`index.html`  
Main U.S. export analysis dashboard.

`imports/`  
Audited U.S. import analysis and 2025 macro trade update.

`tradable_production_flow_system.html`  
State-level tradable production and export-flow model.

`us_city_population_dashboard_dark.html`  
Interactive U.S. regional population explorer.

## Project Philosophy

One of the main goals of this project is to avoid presenting estimates with more certainty than the underlying data supports.

As the project developed, I revisited earlier calculations, corrected values when stronger sources became available, separated official statistics from modeled estimates, and documented areas where additional primary data is still required.

The project remains a work in progress as I continue refining the underlying data, methodology, and interactive tools.
