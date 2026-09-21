### 🛵 Food Delivery Efficiency Analysis

A data visualization project investigating the operational factors that impact food delivery efficiency. By analyzing key variables such as distances, traffic levels, and vehicle modes across our delivery lifecycle, this project highlights patterns that dictate delivery speed and provides actionable recommendations to optimize logistics. 

### 📊 Executive Summary

* **Total Volume Managed:** **200** unique orders analyzed.
* **Average Delivery Time:** **44.74 minutes** per order.
* **Average Trip Distance:** **6.62 km**.

### 🔍 Core Insights & Visual Findings

### 1. Distance vs. Delivery Time

* **The Pattern:** Shows how delivery duration scales with trip distance. Typically, a positive relationship exists where longer distances predictably increase times, though variance spikes heavily depending on vehicle choice and congestion.

### 2. Distance vs. Delivery Mode

* **The Pattern:** Evaluated vehicle choices relative to distance boundaries. Notably, **cars caused the biggest delays** in the dataset, suggesting that full-sized vehicles struggle with urban delivery friction, parking constraints, or localized bottlenecks despite their speed potential.

### 3. Route Length vs. Delivery Time

* **The Pattern:** Examined route optimization and actual layout efficiency. Helps distinguish whether delays stem from raw geographical distance or complex, convoluted route structures that trap larger vehicles.

### 4. Distance vs. Traffic Level

* **The Pattern:** Highlighted how congestion levels correlate with delivery mileage. Surprisingly, **medium traffic levels caused the biggest delays** across the data, indicating that unpredictable, mid-day congestion may be less accounted for in routing algorithms than heavy peak traffic.

### 💡 Actionable Recommendations

Based on the analyzed trends, the following optimizations are proposed to improve overall platform efficiency: 

* **De-prioritize Cars for Urban Clusters:** Since cars introduced the longest delays, shift short-to-medium range dispatches toward agile transit options like motorbikes, e-bikes, or scooters.
* **Adjust Medium Traffic Padding:** Recalibrate the routing engine's time-estimation algorithms to add a safety buffer for medium traffic conditions, preventing missed ETA expectations.
* **Dynamic Vehicle Dispatching:** Set strict distance boundaries where specific transit modes perform optimally to maximize fleet utilization and drop-off speed.
