# Data Engineering Project

A collection of ETL (Extract, Transform, Load) projects and data analysis scripts using Python and Jupyter notebooks.

## 📁 Project Structure

```
.
├── api_elt.ipynb              # API-based ETL pipeline
├── cars45_etl.ipynb           # Cars45 data ETL process
├── superstore_etl.ipynb       # Superstore data ETL process
├── playground.ipynb           # Experimental notebook for testing
├── clean_cars45.csv           # Cleaned cars45 dataset
└── sources/
    ├── car45_data.csv         # Source data for cars45 project
    └── superstore.csv         # Source data for superstore project
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Docker (optional, for containerized execution)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd "Data Engineering"
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 📊 Projects

### API ETL (api_elt.ipynb)
ETL pipeline that extracts data from APIs and loads it into target systems.

### Cars45 ETL (cars45_etl.ipynb)
Data transformation and cleaning for Cars45 vehicle inventory data.
- Input: `sources/car45_data.csv`
- Output: `clean_cars45.csv`

### Superstore ETL (superstore_etl.ipynb)
ETL process for superstore sales and inventory data.
- Input: `sources/superstore.csv`

##  Usage

1. Open any `.ipynb` file in Jupyter Notebook:
```bash
jupyter notebook
```

2. Run cells sequentially to execute the ETL pipelines

3. Check the output files generated in the project directory

## 🔧 Technologies Used

- **Python**: Core programming language
- **Jupyter Notebook**: Interactive development environment
- **Pandas**: Data manipulation and analysis
- **Docker**: Containerization
- **Apache Airflow**: Workflow orchestration (optional)


## ✅ Contributing

3. Test thoroughly
4. Submit a pull request

