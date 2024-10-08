# Delivery-Route-Optimization

## Overview
This project aims to optimize delivery routes for restaurants in Bangalore, India, by analyzing the impact of weather and traffic conditions. By leveraging a dataset containing restaurant and delivery location data, we apply the Haversine formula to calculate distances and adjust them based on various environmental factors.

## Table of Contents
- [Installation](#installation)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Visualization](#visualization)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation
To run this project, you will need MATLAB installed on your computer. Follow these steps to get started:

1. Clone the repository:
    ```bash
    git clone https://github.com/HermelaDev/Delivery-Route-Optimization.git
    cd Delivery-Route-Optimization
    ```

2. Open the project in MATLAB.

## Data Collection
The primary dataset used in this project is `cleaned_bangalore_zomato_data.csv`, which contains the following columns:
- `Restaurant_latitude`
- `Restaurant_longitude`
- `Delivery_location_latitude`
- `Delivery_location_longitude`
- `Time_taken_min`
- Various weather condition indicators (e.g., Cloudy, Sunny)
- Traffic density indicators (e.g., Low, Medium, High, Jam)

## Data Cleaning
Data cleaning was performed to ensure the dataset's integrity:
- Handled missing values
- Verified data types
- Removed any duplicates

## Data Analysis
### Distance Calculation
Utilizing the Haversine formula, the project calculates the great-circle distance between restaurants and delivery locations. The distances are adjusted according to the following factors:
- **Weather Conditions**: Adjustments based on conditions like cloudy, stormy, or sunny.
- **Traffic Density**: Adjustments based on traffic states like low, medium, high, or jam.

## Visualization
The results are visually represented using geographic plots to illustrate the delivery paths. Restaurants are marked in **green**, while delivery locations are marked in **red**.

## Results
The adjusted distance and time matrices are saved as:
- `distance_matrix_adjusted.csv`
- `time_matrix_adjusted.csv`

These matrices serve as the foundation for further analysis and optimization algorithms.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries or feedback, please contact:
- **Name**: Hermela Seltanu
- **Email**: [hermellaseltanu@gmail.com](mailto:hermellaseltanu@gmail.com)
