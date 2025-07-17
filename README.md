# ODIN
![image](https://github.com/user-attachments/assets/7a6c4068-aa30-43bb-8757-75a2ebcd984e)

⸻

OMHH Analysis Notebook

This Jupyter Notebook provides an analytical workflow for exploring and processing data on Organic Metal Halide Hybrids (OMHHs). These materials are studied for their electronic, optical, and structural properties, particularly their tunable bandgaps and compositional diversity. The notebook loads, cleans, and summarizes data from an Excel file and prepares the dataset for further exploration and modeling.

⸻

📁 Dataset
	•	Source: Halide dataform.xlsx, Sheet: OMHH
	•	Entries: 75 OMHH compounds
	•	Columns include:
	•	OMHH Name
	•	OMHH Formula
	•	IUPAC Name
	•	Dimensionality
	•	Metal Halide Motif
	•	Metal Halide Precursor
	•	Organic Cation
	•	Synthesis Description
	•	Bandgap (eV)
	•	and more

⸻

⚙️ Features

🔹 Data Loading & Cleaning
	•	Reads the Excel spreadsheet into a pandas DataFrame
	•	Sets headers and resets indexing
	•	Converts bandgap values to numeric format for quantitative analysis

🔹 Descriptive Statistics
	•	Counts occurrences of unique values in:
	•	Dimensionality
	•	Metal Halide Motif
	•	Organic Cation
	•	Bandgap (eV)

🔹 Visualization
	•	Uses matplotlib and seaborn to prepare visual plots and distributions
	•	Enables exploration of categorical and continuous features such as dimensionality and bandgap values

🔹 Feature Engineering (Built-in Tools)
	•	Utilizes pymatgen.Composition for chemical formula parsing
	•	Includes imports and structure for regression modeling using:
	•	RandomForestRegressor
	•	LinearRegression
	•	Model evaluation metrics (MAE, R², RMSE)

⸻

🛠️ Tools Used
	•	Python 3
	•	pandas, numpy
	•	matplotlib, seaborn
	•	pymatgen
	•	scikit-learn
	•	openpyxl (for Excel I/O)

⸻

💡 Applications

This notebook is structured for use in:
	•	Materials informatics
	•	Bandgap prediction
	•	Cation/motif classification
	•	Exploratory data analysis of hybrid perovskites
