# Dataset-Improvement-Using-Outlier-Removal

Dataset Improvement Using Outlier Removal is a Python-based project aimed at enhancing data quality by removing statistical outliers. The project uses two key algorithms—Isolation Forest and Elliptic Envelope—to detect and eliminate anomalies from datasets. A regression model is used to evaluate the Mean Absolute Error (MAE) before and after outlier removal. The graphical user interface is built with PyQt Designer, with automated code generation via PyUIC. The tool takes a housing dataset as input and outputs MAE values and dataset shapes before and after processing. It emphasizes accuracy improvement in data analysis. Scikit-learn is used for model implementation. Results demonstrate a noticeable reduction in MAE. The project is modular and scalable for application in other domains.

#🛠️ Technologies Used
	Programming Language: Python
	Libraries/Frameworks/Tools:
•	Scikit-learn (sklearn) – for implementing Isolation Forest, Elliptic Envelope, and regression models
•	NumPy – for numerical operations and array handling
•	PyQt5 – for building the graphical user interface (GUI)
•	PyUIC – to convert .ui files (created with Qt Designer) to Python code
•	SQLite3 – for storing database entities (mentioned in software requirements)
	IDE/Development Tools:
•	Visual Studio Code (VS Code)
•	Anaconda – for managing Python environments and packages
•	Qt Designer – for designing the GUI visually
	Platform:
•	Windows (64-bit OS required)

#📊 Dataset Used
	Housing Dataset
•	The dataset contains features related to real estate or housing (though exact column names are not specified in the doc).
•	It is stored in a file named housing.csv.
•	This dataset is used to demonstrate the effect of outlier removal on regression model performance (evaluated via Mean Absolute Error).
