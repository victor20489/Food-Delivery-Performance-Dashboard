### 🛵 Food Delivery Efficiency Analysis

An exploratory data analysis (EDA) project investigated to uncover the core operational factors impacting food delivery efficiency. By analyzing key variables such as distances, traffic levels, and vehicle modes, this project maps patterns that dictate delivery speed and provides data-driven recommendations to optimize logistics. 

### 📊 Executive Summary

* **Total Volume Managed:** **200** unique orders analyzed.
* **Average Delivery Time:** **44.74 minutes** per order.
* **Average Trip Distance:** **6.62 km**.

### 🔍 Core Insights & Key Relationships

### 1. Distance vs. Delivery Time

* **The Pattern:** Analyzed how delivery duration scales with trip distance. Typically, a positive relationship exists where longer distances predictably increase times, though variance spikes heavily depending on vehicle choice and congestion.

### 2. Distance vs. Delivery Mode

* **The Pattern:** Evaluated vehicle choices relative to distance boundaries. Notably, **cars caused the biggest delays** in the dataset, suggesting that full-sized vehicles struggle with urban delivery friction, parking constraints, or localized bottlenecks despite their speed potential.

### 3. Route Length vs. Delivery Time

* **The Pattern:** Examined route optimization and actual layout efficiency. Helps distinguish whether delays stem from raw geographical distance or complex, convoluted route structures that trap larger vehicles.

### 4. Distance vs. Traffic Level

* **The Pattern:** Highlighted how congestion levels correlate with delivery mileage. Surprisingly, **medium traffic levels caused the biggest delays** across the data, indicating that unpredictable, mid-day congestion may be less accounted for in routing algorithms than peak heavy traffic.

### 🛠️ Project Structure

text

├── data/                  # Raw and processed food delivery datasets
├── notebooks/             # Jupyter notebooks covering EDA, plotting, and calculations
├── src/                   # Python scripts for data cleaning and utility functions
├── README.md              # Project documentation and summary of findings
└── requirements.txt       # Necessary Python libraries to replicate the environment

Use code with caution.

### 💡 Actionable Recommendations

Based on the analyzed trends, the following optimizations are proposed to improve overall platform efficiency: 

* **De-prioritize Cars for Urban Clusters:** Since cars introduced the longest delays, shift short-to-medium range dispatches toward agile transit options like motorbikes, e-bikes, or scooters.
* **Adjust Medium Traffic Padding:** Recalibrate the routing engine's time-estimation algorithms to add a safety buffer for medium traffic conditions, preventing missed ETA expectations.
* **Dynamic Vehicle Dispatching:** Set strict distance boundaries where specific transit modes perform optimally to maximize fleet utilization and drop-off speed.

### 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed on your system. 

### Installation

1. Clone this repository: 

bash

git clone https://github.com/victor20489/food-delivery-efficiency.git
cd food-delivery-efficiency

Use code with caution.
2. Install the dependencies: 

bash

pip install -r requirements.txt

Use code with caution.
3. Run the primary analysis notebook inside the notebooks/ directory to review the visualizations.
