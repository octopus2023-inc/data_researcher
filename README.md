# data_researcher

data_researcher is an open-source Python framework designed to **automate exploratory data analysis (EDA) on tabular data** leveraging Large Language Models (LLMs). Similar in approach to OpenAI's deep research —but focused on your data— data_researcher dives deeply into datasets, identifying issues, uncovering hidden insights, and generating structured, actionable reports in minutes, saving valuable time for data analysts and data scientists.

## 🚀 Key Features

**Automated Exploratory Data Analysis**: Quickly explore datasets, identifying anomalies, data quality issues, and distribution characteristics without manual intervention.

**Contextual exploration based on all your available information**: Provide context on your data and each column, so the model can understand what each column mean,

**Automatic insight Extraction**: data_researcher will propose and run queries on your data automatically, based on a given description of your data and columns. It finds noteworthy insights without any manual intervention.

**Automated Reporting:** Generate structured, comprehensive reports detailing identified issues, insights, and recommendations for further investigation.

## 📌 Installation

You can install data_researcher via pip:
```
pip install data_researcher
```

## 📖 Quickstart

Here's a quick example demonstrating how easy it is to use data_researcher:

```
import data_researcher

# Load your dataset (CSV example)
data = data_researcher.load_data('your_dataset.csv')

# Provide context on your data
context=data_researcher.provide_context('Your context about the data, including each column meaning')

# Initialize the researcher
researcher = data_researcher.DataResearcher(api_key='your_llm_api_key')

# Run analysis
report = researcher.analyze(data,context)

# Output report
print(report)
```

## 🛠️ How it Works

data_researcher operates through the following workflow:

**Data Profiling**: Rapidly assesses data for basic statistics, missing values, distributions, and potential anomalies.

**LLM Analysis**: Uses LLMs to interpret the data given your context, identifying hidden patterns, anomalies, correlations, and opportunities for deeper exploration.

**Report Generation**: Compiles insights and findings into a structured, human-readable report that can be easily shared and reviewed.

## 🤝 Coming soon

data_researcher is coming soon. **Star the repo so we know we have demand for it.**

## 📄 License

Distributed under the MIT License. See LICENSE for more information.

