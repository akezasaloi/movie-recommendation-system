# Movie Recommendation System

A machine learning-based movie recommendation system, built in Python and Jupyter Notebook. This project demonstrates how to analyze movie data and provide personalized recommendations using both collaborative and content-based filtering approaches.

## Features

- **Data Cleaning & Preparation:** Clean and preprocess movie data for modeling.
- **Content-Based Filtering:** Recommend movies based on features like genre, keywords, and description.
- **Collaborative Filtering:** Suggest movies using user ratings and similarities.
- **Tool Agent Integration:** Modular Python agents for automated tasks and experimentation.
- **Interactive Notebooks:** Step-by-step analysis in Jupyter Notebooks.

## Project Structure

```
movie-recommendation-system/
│
├── multi_tool_agent/        # Modular Python agent tools for task automation
│   ├── __init__.py
│   ├── agent.py
│   ├── requirements.txt
│   ├── root_agent.yaml
│   ├── test_gemini.py
│   └── tools.py
│
├── .gitignore              # Git ignore file
├── data_cleaning.ipynb     # Jupyter notebook for data cleaning
├── movieRec.ipynb          # Main recommendation system notebook
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies for core project
```

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Recommended: Virtual environment (venv, conda)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/akezasaloi/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   pip install -r multi_tool_agent/requirements.txt
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open `data_cleaning.ipynb` and `movieRec.ipynb` to explore and run the notebooks.

## Usage

- Run `data_cleaning.ipynb` to preprocess and clean raw movie data.
- Explore and modify `movieRec.ipynb` for model building, analysis, and generating recommendations.
- Use the `multi_tool_agent` Python module for advanced automation and experimentation.

## Data

- Uses publicly available movie datasets (e.g., MovieLens, IMDB, or Kaggle).
- Data preprocessing steps are covered in the notebooks.

## Contributing

Contributions welcome! Please submit issues or pull requests for improvements or new features.

## Contact

Questions or suggestions? Open an issue [here](https://github.com/akezasaloi/movie-recommendation-system/issues).
