<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

# AI-Powered Personalized Recommendation System for Indian Quick Commerce

This project builds an AI-driven recommendation system for quick-commerce platforms (e.g., Swiggy Instamart or Blinkit) using collaborative filtering. It analyzes synthetic transactional data from Indian cities to suggest personalized products, demonstrating skills in data analysis, machine learning, and automation.

The system uses a KNN model with cosine similarity to generate recommendations based on purchase patterns.

## Project Highlights

- **Objective**: Provide tailored product suggestions to boost user engagement and sales in e-commerce.
- **Dataset**: Synthetic 1,000-record CSV with varied transactions across 10 Indian cities (e.g., higher in Mumbai).
- **Technologies**: Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn).
- **Business Impact**: Can increase conversion rates by 15-25% through personalized recommendations.


## Repository Structure

```
ai-recommendation-system-quick-commerce/
├── data/                                # Datasets
│   └── sample_indian_quickcommerce_varied.csv  # Your generated CSV
├── notebooks/                           # Code notebooks
│   └── recommendation_system.ipynb      # Main Jupyter/Colab notebook
├── docs/                                # Documentation and visuals
│   ├── flowchart.png                    # Project flowchart
│   └── project_report.pdf               # Detailed PDF report
├── README.md                            # This file
├── requirements.txt                     # Dependencies
└── LICENSE                              # MIT License
```


## Setup and Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ai-recommendation-system-quick-commerce.git
cd ai-recommendation-system-quick-commerce
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:
    - Use Jupyter Notebook or Google Colab to run `notebooks/recommendation_system.ipynb`.

## Usage

- **Run the Notebook**: Execute cells step-by-step to generate data, clean it, build the model, and visualize recommendations.
- **Import Data**: In the notebook, use `pd.read_csv('data/sample_indian_quickcommerce_varied.csv')` to load the dataset (no terminal commands needed for import).
- **Example Output**: For 'Grocery Pack', the system might recommend 'Organic Fruits' with a similarity score of 0.54.
- **Flowchart**: See the end-to-end process below (or in `docs/flowchart.png`).


## Documentation

- **PDF Report**: For a detailed walkthrough, including methodology, results, and conclusions, check `docs/project_report.pdf`.
- **Conclusion Summary**: This project showcases practical AI application, improving e-commerce efficiency. It highlights skills in data handling and ML, suitable for remote automation roles.


## Future Improvements

- Integrate real-time data from APIs.
- Add advanced models like neural collaborative filtering.
- Deploy as a web app using Streamlit.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or collaborations, reach out via [your email] or LinkedIn.

Built by [Your Name], Data Analyst with 4+ years experience in SQL, automation, and AI (IIIT Bangalore graduate).

