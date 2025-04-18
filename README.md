# Naveen_Customer-segmentation-
# Customer Segmentation Using K-Means Clustering

This project is a simple Python-based customer segmentation tool using K-Means clustering. The application allows users to upload a CSV file and select specific features (e.g., purchase behavior, browsing patterns) for segmenting customers into meaningful groups.

## Features
- Upload your CSV data file using a file dialog.
- Choose columns to include in the clustering process.
- Visualize the optimal number of clusters using the Elbow Method.
- View cluster summaries.
- Visualize customer segments using scatter plots.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- tkinter (standard in most Python installations)

Install dependencies with:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run
1. Open the script in a Python environment that supports GUI (like IDLE or Jupyter).
2. Run the script.
3. When prompted, select your CSV file.
4. Enter the column names you wish to use for clustering.
5. View the Elbow Method plot and input the number of clusters.
6. See the clustered data and a visualization.

## Example Columns to Use
- `Total_Spent`
- `Frequency`
- `Avg_Session_Time`
- `Pages_Viewed`

Ensure these columns are numeric and do not contain missing values.

## Acknowledgements
- Developed with help from **ChatGPT by OpenAI**.
- Libraries and documentation:
  - [pandas](https://pandas.pydata.org/)
  - [scikit-learn](https://scikit-learn.org/)
  - [matplotlib](https://matplotlib.org/)
  - [tkinter](https://docs.python.org/3/library/tkinter.filedialog.html)

## License
This project is free to use for educational and non-commercial purposes.

