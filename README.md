# Feegow Data Analysis

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A project to extract data from the [Feegow API](https://docs.feegow.com/), perform marketing-focused analysis, and deliver insights to non-technical stakeholders.

## Overview

The main objective of this project is to leverage the data available through the Feegow API to generate valuable marketing insights for medical clinics. This involves:

1.  **Data Extraction:** Systematically pulling relevant data points from the Feegow platform.
2.  **Data Analysis:** Running scripts to process the data and identify trends, patterns, and key performance indicators (KPIs) relevant to marketing efforts.
3.  **Insight Delivery:** Presenting the findings in a simple and accessible format, such as automated email reports or a simple, self-hosted website.

## Current Status

🚧 **This project is in the early stages of development.** 🚧

The current focus is on building the foundational components for interacting with the Feegow API and establishing a solid structure for the data analysis scripts. The project is not yet ready for production use.

## Planned Features

- [ ] **Robust API Client:** A stable and reusable client to handle authentication and requests to the Feegow API.
- [ ] **Data Extraction Scripts:** Scripts to fetch specific datasets, such as patient demographics, appointments, and sources.
- [ ] **Marketing Analysis Modules:**
    - Patient acquisition source analysis.
    - Patient retention and churn rate.
    - Appointment scheduling patterns.
- [ ] **Automated Reporting:** A mechanism to generate and send reports (e.g., via email).
- [ ] **Simple Web Dashboard:** A basic web interface to visualize the key metrics.

## Getting Started

These instructions will guide you to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.8+
- A Feegow API Access Token. You can find more information in the [official documentation](https://docs.feegow.com/#autenticacao).

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/caazzi/feegow_data_analysis.git
    cd feegow_data_analysis
    ```

2.  **Create a virtual environment and install dependencies:**
    It's recommended to use a virtual environment.
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
    *(Note: A `requirements.txt` file will be added as dependencies are finalized.)*

3.  **Set up environment variables:**
    Create a `.env` file in the root directory of the project by copying the example file:
    ```sh
    cp .env.example .env
    ```
    Now, edit the `.env` file and add your Feegow API token:
    ```
    FEEGOW_API_TOKEN="your_api_token_here"
    ```

## Usage

Once the scripts are developed, you will be able to run them from the command line. For example:

```sh
python src/run_analysis.py --report patient_acquisition
```
*(Note: This is a placeholder for future usage instructions.)*

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
