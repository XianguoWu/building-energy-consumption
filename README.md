🏠 Building Energy Consumption Dataset
📌 Overview

This dataset contains 1,000 synthetic but realistic samples for the task of predicting energy consumption in buildings.
It was generated to reflect the average building energy consumption in Iran (~285 kWh/m²/year), with realistic variations to cover both efficient and inefficient buildings.

The dataset is useful for machine learning regression tasks, feature analysis, and sustainable building research.

📊 Features

The dataset includes 10 input parameters that influence building energy consumption, and 1 output variable:

Window_wall_ratio (–) → Ratio of window area to wall area.

External_wall_heat_transfer (W/m²·K) → Heat transfer coefficient of external walls.

Roof_heat_transfer (W/m²·K) → Heat transfer coefficient of the roof.

Outer_window_heat_transfer (W/m²·K) → Heat transfer coefficient of outer windows.

External_wall_solar_absorption (–) → Solar absorption coefficient of external walls.

Roof_solar_absorption (–) → Solar absorption coefficient of the roof.

Outer_window_solar_absorption (–) → Solar absorption coefficient of windows.

Airtightness (ac/h) → Air infiltration rate.

Heating_temp (°C) → Heating set-point temperature.

Cooling_temp (°C) → Cooling set-point temperature.

Target Variable:

Energy_consumption (kWh/m²/year) → Annual energy consumption of the building.

Mean: ~285 kWh/m²/year

Range: 150 – 400 kWh/m²/year

✅ Data Realism

Input features are sampled within real-world engineering ranges.

The output is calibrated to align with reported average energy use in Iranian buildings (285 kWh/m²/year).

This makes the dataset useful for predictive modeling, optimization, and benchmarking.

🔧 Potential Use Cases

Machine learning regression for building energy prediction.

Feature importance and sensitivity analysis.

Benchmark dataset for sustainable building research.

Academic projects on energy efficiency.

✍️ Note: This dataset is synthetic but based on realistic assumptions and national averages. It should be used for research, education, and modeling purposes, not as an official building audit dataset.
