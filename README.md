# Olympic Data Analysis with Streamlit

![Olympics Logo](https://e7.pngegg.com/pngimages/1020/402/png-clipart-2024-summer-olympics-brand-circle-area-olympic-rings-olympics-logo-text-sport.png)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project provides an in-depth analysis of Olympic data using Streamlit, a popular framework for creating data web applications. The analysis covers various aspects such as medal tally, overall analysis, country-wise analysis, and athlete-wise analysis.

## Features
- **Medal Tally**: View the medal tally for different years and countries.
- **Overall Analysis**: Get top statistics like number of editions, cities, sports, events, athletes, and nations. Visualize participating nations, events, and athletes over the years.
- **Country-wise Analysis**: Analyze the performance of a specific country over the years, including medal tally and top athletes.
- **Athlete-wise Analysis**: Examine the age distribution of athletes, height vs. weight distribution, and participation of men and women over the years.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/MohammedLike/Olympic_FData_Analysis_Streamlit.git
    cd Olympic_FData_Analysis_Streamlit
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv .venv
    .venv\Scripts\activate  # On Windows
    source .venv/bin/activate  # On macOS/Linux
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501` to view the application.

## Screenshots
### Medal Tally
![Medal Tally Screenshot](screenshots/medal_tally.png)

### Overall Analysis
![Overall Analysis Screenshot](screenshots/overall_analysis.png)

### Country-wise Analysis
![Country-wise Analysis Screenshot](screenshots/country_wise_analysis.png)

### Athlete-wise Analysis
![Athlete-wise Analysis Screenshot](screenshots/athlete_wise_analysis.png)

## Technologies Used
- **Python**: The main programming language.
- **Streamlit**: Framework for creating the web application.
- **Pandas**: For data manipulation and analysis.
- **Plotly**: For interactive visualizations.
- **Seaborn & Matplotlib**: For static visualizations.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
