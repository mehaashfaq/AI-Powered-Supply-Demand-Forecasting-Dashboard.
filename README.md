# 📈 AI-Powered Supply & Demand Forecasting Studio

An interactive, data-driven business analytics dashboard built with **Streamlit** and **TensorFlow**. This application simulates real-world market environments by processing business operational variables through a structural deep learning architecture to instantly forecast consumer demand velocity and recommend optimal pricing thresholds.

---

## 🎯 Dashboard Features
* **Multi-Variable Prediction Matrix:** Processes 4 core market vectors simultaneously: Base Price, Marketing Expenditure, Competitor Benchmarks, and Generational Seasonality Indigents.
* **Real-Time Simulation Controls:** Features a reactive sidebar slider panel enabling instant "What-If" market scenario analysis across multiple product domains (Tech, Apparel, Appliances, Groceries).
* **AI Equilibrium Pricing Engine:** Evaluates price elasticity parameters to dynamically suggest the ideal competitive price point to maximize inventory turnover.
* **Dynamic Sales Velocity Visualization:** Uses high-fidelity interactive line charts to project a 60-day sales demand horizon based on active configurations.
* **Optimized Cloud Footprint:** Explicitly engineered using isolated lightweight computational layers to prevent RAM-overflow faults on free container tiers like Streamlit Community Cloud.

---

## 🛠️ Architecture & Core Dependencies
* **Core Runtime:** Python 3.10
* **Frontend Dashboard Interface:** Streamlit (v1.35.0)
* **Neural Network Processing:** TensorFlow-CPU (v2.12.0)
* **Data Arrays & Vector Pipelines:** NumPy (v1.23.5) & Pandas

---

## 💻 Local Installation & Deployment

Execute the following commands in your system terminal to clone and run this application locally:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME


Initialize Isolated Virtual Environment:

Bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Conflict-Free Production Dependencies:

Bash
pip install -r requirements.txt
Launch the Local Streamlit Instance:

Bash
streamlit run app.py
   
