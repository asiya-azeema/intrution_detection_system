
# Intrusion Detection System - EDA on DDoS Network Traffic

This project performs **Exploratory Data Analysis (EDA)** on the *Friday-WorkingHours-Afternoon-DDoS.csv* dataset. The goal is to explore patterns in network traffic and distinguish between normal and DDoS attack traffic using visual analysis.

## 📁 Dataset

- **Name:** Friday-WorkingHours-Afternoon-DDoS.csv
- **Source:** CICIDS2017 dataset (download separately)
- **Format:** CSV
- **Important Features:**
  - Flow Duration
  - Total Fwd/Backward Packets
  - Length of Fwd/Bwd Packets
  - Flow Bytes/s, Packets/s
  - Label (Normal or Attack)

## 📊 Visualizations Performed

1. **Label Distribution**
   - Bar plot showing normal vs. attack traffic.
2. **Numerical Feature Distributions**
   - Histograms for packet counts, durations, and flows.
3. **Pairwise Feature Relationships**
   - Pairplot highlighting how features relate by label.
4. **Correlation Matrix**
   - Heatmap to explore correlation among numerical features.
5. **Boxplot Comparison**
   - Flow Duration across normal vs attack traffic.

## 🛠️ Libraries Used

- Python 3
- pandas
- seaborn
- matplotlib

## ✅ Skills Highlighted

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Network Traffic Visualization
- Intrusion Detection Insights

## ▶️ How to Run

1. Ensure the dataset is available at the specified path.
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the script:
   ```bash
   python "Intrusion detection system.py"
   ```

## 📄 License

This project is intended for learning and research purposes.


## 🖼️ Screenshots

### 🖥️ Terminal Output (First Few Rows of the Dataset)
![Terminal Output](terminal_output.png)

### 📊 Label Distribution Plot
![Label Distribution](label_distribution.png)
