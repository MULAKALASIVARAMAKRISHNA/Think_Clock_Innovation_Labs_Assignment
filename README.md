Battery Aging Analysis and Visualization 🚀 Overview This project analyzes the aging of Li-ion batteries by visualizing key parameters such as:

Battery Impedance Electrolyte Resistance (Re) Charge Transfer Resistance (Rct) The analysis uses NASA's Battery Dataset, collected through charge/discharge cycles and impedance measurements.

Features Data Preprocessing: Cleans and processes the data, handling missing values via interpolation. Battery Impedance Calculation: Combines Re and Rct to calculate overall battery impedance. Interactive Visualizations: Battery Impedance vs. Cycle Electrolyte Resistance (Re) vs. Cycle Charge Transfer Resistance (Rct) vs. Cycle All plots are created using Plotly for interactivity.

Setup Instructions Clone the Repository:

bash

Copy code

git clone https://github.com/MULAKALASIVARAMAKRISHNA/Think-Clock-Innovation-Labs-Assignment.git

cd Think-Clock-Innovation-Labs-Assignment

Install Dependencies:

Ensure Python 3.x is installed, then run:

bash Copy code pip install pandas plotly Prepare the Dataset: Download the NASA Battery Dataset and place the metadata.csv file in a data/ folder within the project directory. Update the file path in the script:

python Copy code file_path = "data/metadata.csv" Run the Script: Execute the Python script to generate visualizations:

bash Copy code python battery_analysis.py Project Output Battery Impedance vs. Cycle Re (Electrolyte Resistance) vs. Cycle Rct (Charge Transfer Resistance) vs. Cycle Visualizations provide insights into how battery parameters change with aging.

Technologies Used Python Pandas: Data handling and preprocessing Plotly: Interactive plotting
