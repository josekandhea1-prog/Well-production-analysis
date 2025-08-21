# Natural Gas Well Feasibility Analysis: PEGASUS 70279125

## Overview
This project presents a comprehensive technical and economic feasibility analysis of the **PEGASUS (DEVONIAN) Well No. 70279125**. Utilizing historical production data, the study evaluates the well's performance, identifies operational challenges, and assesses its investment viability. It integrates core reservoir and production engineering techniques, demonstrating advanced analytical and modeling skills.

## Data Source
All historical production data (84 months) was directly extracted from the **Texas Railroad Commission** website.

## Methodologies Applied
The analysis employed a multifaceted approach, combining industry-standard techniques:

* **Decline Curve Analysis (DCA):** Utilized an exponential model to forecast future gas production and estimate the **Estimated Ultimate Recovery (EUR)**.
* **Economic Evaluation:** Performed a detailed financial assessment, including **Net Present Value (NPV)** calculation, to determine the project's profitability under defined economic parameters and **3-scenario sensitivity analysis** (varying gas price, OPEX, and discount rate).
* **Nodal Analysis (IPR/VLP):** Modeled Inflow Performance Relationship (IPR) and Vertical Lift Performance (VLP) curves to identify optimal production rates and diagnose operational constraints, such as liquid loading.

## Key Findings
The analysis yielded critical insights into the well's performance and economic outlook:

* **Estimated Ultimate Recovery (EUR):**
    * Gas: **3,710,384.63 MCF**
    * Condensate: **50,388.44 BBL**
* **Economic Viability (NPV):** The project consistently resulted in a **negative NPV** across all scenarios, indicating it is **not economically viable** under current assumptions:
    * **Base Case:** -$5,345,626.11
    * **Best Case:** -$1,335,180.21
    * **Worst Case:** -$8,729,472.01
* **Optimal Operating Point:** Identified at **4166.67 MCF/month** (gas flow rate) and **2583.33 psi** (bottom-hole flowing pressure).
* **Liquid Loading Impact:** Nodal analysis highlighted a critical issue of liquid loading, with a **Critical Flow Rate of 3125 MCF/month**, below which sustained production is significantly impeded.

## Tools & Skills Demonstrated
* **Microsoft Excel:** Utilized extensively for detailed **DCA modeling**, comprehensive **economic calculations** (NPV, cash flow), **Nodal Analysis**, **sensitivity analysis**, and **dynamic charting** (e.g., Goal Seek, complex formulas, trend analysis).
* **Petroleum Engineering Concepts:** Applied **DCA, IPR/VLP Nodal Analysis, Economic Evaluation, Liquid Loading Diagnosis, and Production Optimization**.

## Future Enhancements (Planned)
This project is planned for further enhancements, including:

* **Python Integration:** Expanding the use of Python (Pandas, Matplotlib) for advanced data validation, analysis, and enhanced visualization.
* **Hyperbolic Decline Models:** Implementation and comparison of hyperbolic decline models (with b<1 constraint) against the exponential model for a more robust production forecast.
* **Interactive Dashboards:** Development of interactive dashboards (e.g., using Streamlit) for dynamic scenario analysis and improved data presentation.
* **In-depth Financial Metrics:** Further analysis of cash flow specifics and detailed payback period.
