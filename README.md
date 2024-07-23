# Calorie Tracker

Calorie Tracker is a basic Django-based web application that helps users keep track of their daily food intake, monitor macronutrient consumption, and maintain a calorie goal. 

## Features

- Add and remove food items consumed throughout the day
- Display total intake of carbohydrates, proteins, fats, and calories
- Visualize macronutrient breakdown using a doughnut chart
- Track progress towards a daily calorie goal with a progress bar

## Technologies Used

- Django
- HTML
- CSS (Bootstrap 4.6.2)
- JavaScript
- Chart.js

## Setup and Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/AtharvaDeokar21/calorie-tracker.git
    cd mysite
    ```

2. **Create and activate a virtual environment**
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**
    ```sh
    pip install -r requirements.txt
    ```

4. **Apply database migrations**
    ```sh
    python manage.py migrate
    ```

5. **Create a superuser**
    ```sh
    python manage.py createsuperuser
    ```

6. **Run the development server**
    ```sh
    python manage.py runserver
    ```

7. **Open your web browser and navigate to**
    ```
    http://127.0.0.1:8000
    ```

## Usage

1. **Login to the application**
    - Use the superuser credentials created during setup.

2. **Add Food Items**
    - Select a food item from the dropdown and click the "Add" button.
    - The added food items will appear in the "Today's Consumption" table.

3. **Track Macronutrients and Calories**
    - View the total intake of carbs, protein, fats, and calories in the table.
    - Check the progress towards the daily calorie goal with the progress bar.
    - Visualize the macronutrient breakdown using the doughnut chart.

4. **Remove Food Items**
    - Click the "X" button next to a food item to remove it from the list.


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Bootstrap](https://getbootstrap.com/)
- [Chart.js](https://www.chartjs.org/)
- [Django](https://www.djangoproject.com/)
