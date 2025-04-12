# E-Commerce Delivery Time Analysis

<img src="https://raw.githubusercontent.com/MathRC/DeliveryTimes/main/images/Package_delivery.jpg" width="500"/>

This repository contains a data science portfolio project analyzing the delivery times of online shopping packages. The project uses data extracted from email notifications to uncover patterns and answer the question:

**When is it safest to leave home without missing a delivery?**

## Project Overview

This project focuses on:
- Validating and cleaning the raw email data.
- Analyzing weekly and hourly delivery patterns.
- Calculating key percentiles (2.5th and 97.5th) to define safe time windows for leaving home.

## Repository Contents

- **📁 images/**: Contains visualizations generated during the analysis, along with a few supporting illustrations.
- **Delivery Times - Online Shopping.ipynb**: The main Jupyter Notebook containing the complete analysis.
- **LICENSE.txt**: The project license.
- **README.md**: This file.
- **environment.yml**: A file to recreate the conda environment with all required packages.
- **mercadolivre_emails.txt**: Text file containing the filenames of MercadoLivre delivery notifications.
- **shopee_emails.txt**: Text file containing the filenames of Shopee delivery notifications.

## Setting Up the Environment

Follow these steps to set up the environment and run the notebook:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/MathRC/DeliveryTimes.git
   cd delivery-times-online-shopping
   ```

2. **Create the Conda Environment:**

   Ensure that [Conda](https://docs.conda.io/en/latest/) is installed on your system. Then run:

   ```bash
   conda env create -f environment.yml
   ```

3. **Activate the Environment:**

   ```bash
   conda activate DeliveryTimes
   ```

4. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Open and Run the Notebook:**

   In Jupyter, open `Delivery Times - Online Shopping.ipynb` and execute the cells to reproduce the analysis.

## Additional Information

- The data used in this project is based on delivery notifications extracted from emails.
- This project demonstrates practical data analysis techniques.
- For reproducibility, the environment file lists only the necessary packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `jupyter`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## Acknowledgments

- Special thanks to the Anaconda community and the creators of the tools used in this analysis.
