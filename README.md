# Time Series Analysis Notebook

This repository contains a Python notebook designed for time series analysis and modeling using a suite of well-established scientific libraries.

---

## Installation

To ensure reproducibility and compatibility, it is highly recommended to install the required packages with the exact versions specified below. This helps avoid issues stemming from version mismatches or breaking changes in dependencies.

### Required Dependencies

Execute the following command in your terminal or notebook environment (e.g., Google Colab):

```bash
pip install -q altair==5.2.0 \
                 matplotlib==3.8.2 \
                 numpy>=1.26.4 \
                 pandas==2.2.2 \
                 pmdarima==2.0.4 \
                 Rbeast==0.1.23 \
                 scipy>=1.14.0 \
                 seaborn==0.13.2 \
                 statsmodels==0.14.1
```
## Libraries Utilized

- **numpy** — Fundamental package for numerical computations  
- **pandas** — Data manipulation and analysis  
- **scipy** — Scientific computing tools and statistical functions  
- **matplotlib**, **seaborn**, **altair** — Data visualization and plotting  
- **statsmodels** — Statistical modeling, hypothesis testing, and time series analysis  
- **pmdarima** — Automated ARIMA modeling  
- **Rbeast** — Bayesian change point detection in time series data  

---

## Important Notes

- Installation of **Rbeast** may present challenges in some environments, such as Google Colab, due to compilation requirements.  
- If installation of Rbeast fails, consider using a **local environment** with an appropriate **C++ compiler** (e.g., via the Anaconda distribution).

---

## Usage Instructions

1. Open the notebook.
2. Execute the cells sequentially.

For detailed guidance, please consult the official documentation of each package used.

---

## License

This project is distributed under the **MIT License**.  
You are free to **use**, **modify**, and **distribute** it.

---

Thank you for your interest in this project.  
Please feel free to **open an issue** for any questions or feedback.
