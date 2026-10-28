# U.S. Vehicle Fleet & Alternative Fuel Adoption Analysis

## Executive Summary
This project analyzes nationwide vehicle registration data across all 50 U.S. states and the District of Columbia to evaluate vehicle powertrain distribution (EVs, PHEVs, HEVs, Gasoline, Diesel) and alternative fuel market penetration. The goal of this analysis is to identify key EV adoption leaders and laggards, differentiate between significant and niche alternative fuels, and provide data-driven policy recommendations for charging infrastructure investments.

---

## Key Questions & Analytical Findings

### Q1: What percentage of vehicles in each state are EVs, PHEVs, HEVs, and Gasoline?
Across the total U.S. registered fleet (~287.1 million vehicles), gasoline vehicles remain dominant (~84.6%), followed by Ethanol/Flex (E85) at 7.05%, HEVs at 2.57%, and EVs at 1.24%.

#### State-by-State Fleet Share Table
| State / Region | EV % | PHEV % | HEV % | Gasoline % |
| :--- | :--- | :--- | :--- | :--- |
| **Alabama** | 0.27% | 0.12% | 1.31% | 84.83% |
| **Alaska** | 0.48% | 0.16% | 1.89% | 81.15% |
| **Arizona** | 1.38% | 0.39% | 2.69% | 83.76% |
| **Arkansas** | 0.26% | 0.12% | 1.37% | 82.93% |
| **California** | 3.41% | 1.11% | 4.62% | 84.64% |
| **Colorado** | 1.66% | 0.69% | 3.20% | 82.85% |
| **Connecticut** | 1.07% | 0.62% | 2.76% | 88.69% |
| **Delaware** | 0.92% | 0.42% | 2.54% | 86.51% |
| **District of Columbia** | 2.60% | 1.19% | 3.86% | 84.11% |
| **Florida** | 1.37% | 0.31% | 2.56% | 86.83% |
| **Georgia** | 0.96% | 0.24% | 2.23% | 85.63% |
| **Hawaii** | 2.37% | 0.68% | 3.96% | 88.05% |
| **Idaho** | 0.43% | 0.23% | 1.63% | 79.44% |
| **Illinois** | 0.99% | 0.33% | 2.23% | 85.23% |
| **Indiana** | 0.42% | 0.21% | 1.61% | 83.70% |
| **Iowa** | 0.29% | 0.19% | 1.43% | 80.72% |
| **Kansas** | 0.43% | 0.21% | 1.76% | 82.74% |
| **Kentucky** | 0.29% | 0.14% | 1.34% | 84.54% |
| **Louisiana** | 0.22% | 0.11% | 1.25% | 83.27% |
| **Maine** | 0.60% | 0.61% | 2.72% | 83.83% |
| **Maryland** | 1.42% | 0.62% | 3.03% | 85.53% |
| **Massachusetts** | 1.34% | 0.80% | 3.09% | 87.26% |
| **Michigan** | 0.59% | 0.34% | 1.83% | 83.63% |
| **Minnesota** | 0.72% | 0.31% | 2.33% | 82.43% |
| **Mississippi** | 0.13% | 0.07% | 0.97% | 83.56% |
| **Missouri** | 0.48% | 0.25% | 1.66% | 81.92% |
| **Montana** | 0.45% | 0.24% | 1.80% | 76.41% |
| **Nebraska** | 0.35% | 0.19% | 1.65% | 81.19% |
| **Nevada** | 1.85% | 0.41% | 2.94% | 84.87% |
| **New Hampshire** | 0.72% | 0.48% | 2.76% | 85.66% |
| **New Jersey** | 1.84% | 0.56% | 3.05% | 87.83% |
| **New Mexico** | 0.53% | 0.25% | 2.05% | 81.83% |
| **New York** | 1.16% | 0.82% | 2.33% | 87.52% |
| **North Carolina** | 0.77% | 0.26% | 2.09% | 85.45% |
| **North Dakota** | 0.13% | 0.10% | 1.13% | 78.42% |
| **Ohio** | 0.49% | 0.23% | 1.70% | 86.08% |
| **Oklahoma** | 0.53% | 0.77% | 1.67% | 83.20% |
| **Oregon** | 1.68% | 0.75% | 3.63% | 80.21% |
| **Pennsylvania** | 0.69% | 0.38% | 1.94% | 87.03% |
| **Rhode Island** | 0.73% | 0.58% | 2.50% | 89.11% |
| **South Carolina** | 0.41% | 0.18% | 1.69% | 85.77% |
| **South Dakota** | 0.19% | 0.14% | 1.40% | 78.25% |
| **Tennessee** | 0.51% | 0.17% | 1.68% | 85.96% |
| **Texas** | 0.89% | 0.21% | 2.15% | 82.93% |
| **Utah** | 1.30% | 0.42% | 2.68% | 81.26% |
| **Vermont** | 1.32% | 0.96% | 4.09% | 83.63% |
| **Virginia** | 1.10% | 0.35% | 2.79% | 86.36% |
| **Washington** | 2.23% | 0.60% | 3.69% | 81.91% |
| **West Virginia** | 0.19% | 0.12% | 1.09% | 84.82% |
| **Wisconsin** | 0.45% | 0.23% | 1.82% | 83.28% |
| **Wyoming** | 0.17% | 0.12% | 1.35% | 74.91% |

---

### Q2: Which states have the highest EV adoption rates, and which states lag behind?
* **Highest Adoption Rate:** **California** leads the nation with an EV penetration rate of **3.41%** (1,256,600 EVs), followed by District of Columbia (2.60%), Hawaii (2.37%), and Washington (2.23%).
* **Lowest Adoption Rates:** **North Dakota** and **Mississippi** lag behind with the lowest EV penetration rates at **0.13%**, followed by Wyoming (0.17%), South Dakota (0.19%), and West Virginia (0.19%).

---

### Q3: Which alternative fuels (biodiesel, ethanol, and hydrogen) are significant vs. niche?
* **Ethanol/Flex (E85) — Significant (7.05%):** E85 represents a major portion of the fleet with over 20.2 million registered vehicles, integrated into existing liquid fuel infrastructure across all 50 states.
* **Biodiesel — Significant (0.98%):** Biodiesel accounts for 2.8 million vehicles nationwide, acting as a viable drop-in alternative for commercial and freight transport.
* **Hydrogen — Niche (0.01% / ~16,900 vehicles):** Hydrogen remains an ultra-niche technology representing less than 1 out of 17,000 vehicles. 100% of all registered hydrogen passenger vehicles in the dataset are located exclusively in California due to localized refueling constraints.

---

### Q4: Where should policymakers prioritize EV infrastructure investment based on adoption trends and gaps in support?
* **Urban Center & Multi-Unit Dwelling (MUD) Charging:** Policymakers should focus infrastructure capital on dense urban centers (e.g., Washington D.C., New York, Miami, Dallas) where rapid EV adoption faces a bottleneck: millions of apartment/condo residents lack access to private garages for home charging.
* **Public Highway Corridors:** Expand DC fast-charging networks along major interstate corridors in high-volume growth states (Florida, Texas, Washington) to eliminate long-distance range anxiety.
* **De-prioritizing Legacy Gaseous Fuels:** Capital should be directed away from hydrogen or CNG fueling in non-California markets, as plug-in electric vehicles outnumber gaseous alternative fuel vehicles nationwide by over 100 to 1.

---

## File Structure & Usage Guide
* **`Vehicle Data.csv` / `Vehicle Data Analysis.Xlsx`**: Raw dataset containing state-level vehicle registration counts by fuel type.
* **`Vehicle Data Analysis.xlsx`**: Excel spreadsheet containing pivot tables, calculated percentage fields, and conditional formatting rules.
* **`README.md`**: Project documentation and summary report.

---