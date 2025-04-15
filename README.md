
# DailyDoseOfDataScience

**DailyDoseOfDataScience** is a lightweight Python-based toolkit designed to visually explore and interact with data science workflows. This project aims to help data science enthusiasts understand various processes and data pipelines via visual aids, scripts, and examples.

## 🚀 Features

- Visual display of data science workflows.
- Modular and clean Python scripts for data handling and visualization.
- Demo video to showcase functionality.
- Ready-to-run scripts and a sample dataset (`city_stats.csv`).
- Compatible with Jupyter notebooks and Python scripts.

## 🧱 Project Structure

```
DailyDoseOfDataScience/
│
├── app.py                        # Application entry point
├── main.py                       # Core workflow logic
├── utlis_to_display_workflow.py # Utility to display workflows visually
├── workflow_all_flows.html      # Output HTML of the workflow visualization
├── city_stats.csv               # Sample dataset used in the project
├── demo.mp4                     # Demonstration video
├── requirements.txt             # Required Python packages
├── test/
│   ├── Copy_of_llamacloud_sql_router-2.ipynb  # Sample notebook
│   └── to_csv.py                              # Sample test script
└── .env.example / .gitignore    # Environment and Git settings
```

## 🛠️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/DailyDoseOfDataScience.git
cd DailyDoseOfDataScience
```

2. **Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

## 📦 Usage

### Run the main script:

```bash
python main.py
```

### Launch the app:

```bash
python app.py
```

You can also open the HTML file (`workflow_all_flows.html`) in your browser to see a visual representation of the workflow.

## 📊 Sample Output

Refer to the `demo.mp4` file for a quick demo of the system in action.

## 🧪 Testing

You can explore the `test/` directory for test scripts and notebooks that demonstrate how to use specific parts of the system.

## 📂 Dataset

The `city_stats.csv` file is a small dataset used within the workflow. You can replace or extend it with your own data.

## 🧠 Inspiration

This project is meant to give learners a **daily dose of hands-on data science** through interactive and visual workflow demonstrations.

## 📬 Contact

For feedback or contributions, feel free to raise an issue or fork the project.
