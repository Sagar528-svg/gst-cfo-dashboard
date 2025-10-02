# 📈 GST CFO Dashboard (Streamlit Proof-of-Concept)

This project is a demonstration of a Goods and Services Tax (GST) financial dashboard, built using Streamlit. It is designed to provide a CFO or Finance Manager with a quick, intuitive visualization of monthly GST liabilities and their impact on cash flow.

The primary goal of this repository is to showcase the power of combining deep financial domain knowledge with modern, user-friendly data visualization tools.

## ✨ Key Features & Analysis

The dashboard processes sales and purchase records to generate two main views:

### 1. Liability Overview
* **Monthly GST Liability Chart:** Visual tracking of Output GST (Sales), Input GST (Purchases), and the calculated Net GST Payable over time.
* **Input Tax Credit (ITC) Utilization:** Analysis of available credit against total liability.

### 2. Cashflow Impact
* **Total GST Impact:** A clear snapshot of the total cash component related to GST (both inflow and outflow).
* **Working Capital Focus:** Helps visualize the net monthly burden or benefit related to GST payments.

## ⚠️ Important Note: Mock Data

This application is built and run entirely on **randomly generated mock data** created by the `generate_mock_data()` function within the script. It is a concept demonstration and **does not connect to any real-world financial systems, databases, or sensitive information.**

## 🛠️ Technology Used

* **Framework:** [Streamlit](https://streamlit.io/) (for the interactive web interface)
* **Data Handling:** [Pandas](https://pandas.pydata.org/) and [NumPy](https://numpy.org/) (for data manipulation and mock data generation)
* **Visualization:** [Plotly Express](https://plotly.com/python/plotly-express/) and [Plotly Graph Objects](https://plotly.com/python/graph-objects/) (for dynamic charts)

## 🚀 How to Run the App Locally

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository URL Here]
    cd [Your Repository Name]
    ```
2.  **Install Dependencies:**
    ```bash
    pip install streamlit pandas numpy plotly
    ```
3.  **Run the App:**
    ```bash
    streamlit run gst_cfo_dashboard.py
    ```

## 📄 License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.
