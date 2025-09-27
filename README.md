# Open Cluster Analytics

Project for learning Open Clusters Analytics using data from the ESA's mission GAIA

## 📁 Project structure

```
├── data/
│   ├── raw/          # Raw data
│   ├── processed/    # Processed data
│   └── external/     # Data from external sources
├── notebooks/
│   ├── exploratory/  # Notebooks for Exploratory Data Analysis
│   └── final/        # Final notebooks
├── src/
│   ├── utils/        # Utility functions
│   └── __init__.py
├── tests/            # Testing
├── docs/             # Documentation
├── environment.yml   # conda environment config
├── requirements.txt  # Alternative dependencies for virtual environments
└── README.md
```

## 🚀 Config of environment

### 1. Clone the repository
```bash
git clone https://github.com/SergioPereiraLema/Open-Clusters-Analytics.git
cd nombre-repo
```

### 2. Create a conda environment and install dependencies
```bash
# Using environment.yml (recomended):
conda env create -f environment.yml
conda activate Open-Clusters-Analytics

# If you prefer to create manually:
# conda create -n Open-Clusters-Analytics python=3.10
# conda activate Open-Clusters-Analytics
# conda install --file requirements.txt
```

### 4. Start Jupyter
```bash
# Verify the environment is activated
conda activate Open-Clusters-Analytics
jupyter notebook
# or:
jupyter lab
```

## 📊 Use

The objective of this project is document the learning path of Open Clusters using data from the ESA mission Gaia. Execute the notebooks to replicate the analysis.

- Exploratory notebooks: `notebooks/exploratory/`
- Final notebooks `notebooks/final/`
- Utilities `src/utils/`
- Processed data `data/processed/`

## 📋 Requirements

- Python 3.10+ (managed by conda)
- Anaconda or Miniconda
- Dependencies listed in `environment.yml`

## 📚 Documentation

The process is being described in [Explore Gaia Data](https://exploregaiadata.com/)

## 🤝 Contributions

Contributions are welcome. Please:

1. Create a fork of the project
2. Create a branch for your feature (`git checkout -b feature/new-feature`)
3. Make commit of your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📄 Licensing

This project is under the MIT licensing. Read the [LICENSE](LICENSE) for more details.

## 📞 Contact

Sergio Pereira Lema - [sergio.pereiralema@proton.me](mailto:sergio.pereiralema@proton.me)

Explore Gaia Data: [https://ExploreGaiaData.com](https://exploregaiadata.com)