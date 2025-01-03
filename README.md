# **Dominant Color Extractor**

## **Overview**

The **Dominant Color Extractor** is a machine learning-powered web application designed to analyze images and extract the top 5 dominant colors. It presents these colors as a vibrant palette, making it a valuable tool for design inspiration, content creators, and hobbyists. Built with Python and tested using Streamlit, the application provides an interactive and visually appealing user experience.

## **Features**

- **Image Analysis**: Upload any image to extract the most prominent colors.
- **Color Palette Generation**: Displays the top 5 dominant colors visually.
- **Streamlit Interface**: Interactive, user-friendly web interface for seamless operation.
- **Customizable Output**: Adjust the number of dominant colors to extract.

## **Project Structure**

```bash
illness_prediction/
├── app/                      # Web application backend/frontend
│   └── app.py                # Main application script
│
├── data/                     # Data storage and preprocessing
│   ├── raw/                  # Raw data files
│   ├── processed/            # Processed/cleaned data
│   ├── external/             # External data sources (optional)
│   └── data_preprocessing.py # Scripts for data cleaning/preprocessing
│
├── models/                   # Machine learning models
│   ├── trained_models/       # Saved trained models
│   ├── training/             # Training scripts
│   │   ├── train.py          # Main training script
│   │   └── utils.py          # Helper functions for training
│   └── illness_model.py      # Code for model definition and inference
│
├── notebooks/                # Jupyter notebooks for experimentation
│   ├── EDA.ipynb             # Exploratory Data Analysis
│   ├── model_dev.ipynb       # Model development
│   └── preprocessing.ipynb   # Data preprocessing
│
├── tests/                    # Unit and integration tests
│   ├── test_data.py          # Tests for data preprocessing
│   ├── test_model.py         # Tests for model predictions
│   └── test_app.py           # Tests for API endpoints and app functionality
│
├── config/                   # Configuration files
│   ├── config.yaml           # General configuration
│   └── logging_config.py     # Logging configuration
│
├── logs/                     # Logs for debugging
├── docker/                   # Docker configuration
│   ├── Dockerfile            # Dockerfile for containerization
│   └── docker-compose.yml    # Multi-service setup
│
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
├── .gitignore                # Files to exclude from version control
└── setup.py                  # Packaging script (optional)
```

## **Installation**

### Step 1: Clone the Repository

```bash
git clone git@github.com:SenhadjiMSaid/Dominant-Color-Extractor.git
cd Dominant-Color-Extractor

```

### Step 2: Install Dependencies

Create a conda environment using the provided environment.yml file:

```bash
conda env create -f environment.yml
```

Activate the environment:

```bash
conda activate color_extractor_env
```

If you need to add new packages in the future, update the environment.yml file and use:

```bash
conda env update --file environment.yml --prune
```
