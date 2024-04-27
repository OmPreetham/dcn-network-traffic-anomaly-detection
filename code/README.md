# Anomaly Detection in Network Traffic

This is tailored for use in Google Colab or a local Jupyter Notebook environment.

## Pre-requisites

Ensure you have the following installed if you are running this notebook locally:

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Required Python libraries: `numpy`, `pandas`, `tensorflow`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn`

Alternatively, you can use Google Colab, which already includes most libraries, and you can install any missing ones directly within the notebook.

## Steps to Run the Notebook

### 1. Prepare the Data

- Make sure your datasets are named `Train.txt` and `Test.txt`.

### 2. Upload the Data to the Correct Location

- **Google Colab:** Use the sidebar to navigate to the 'Files' tab. Click on 'Upload' and select your `Train.txt` file. Make sure it uploads to the `/content/` directory.
- **Jupyter Notebook:** Place your `Train.txt` and `Test.txt` files in the root directory where your notebook is located, or adjust the path in the notebook code to match your file's location.

### 3. Open the Notebook

- **Google Colab:** Upload your `.ipynb` file similarly to how you uploaded the data, or connect your Google Colab to GitHub where your notebook is hosted and open it directly.
- **Jupyter Notebook:** Open your Jupyter environment, navigate to the directory containing your `.ipynb` file, and open it.

### 4. Install Required Libraries

If you find that some libraries are missing, you can install them by running:

```bash
!pip install numpy pandas tensorflow matplotlib seaborn scikit-learn imbalanced-learn
```

in a cell at the beginning of your notebook.

### 5. Execute the Notebook

Run each cell in the notebook sequentially. In Google Colab or Jupyter, you can use Shift + Enter to run a cell and move to the next one.
