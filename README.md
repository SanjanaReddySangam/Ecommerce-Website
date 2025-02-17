# Ecommerce Website

This is a simple e-commerce website built using **Django** for the backend and **HTML/CSS** for the frontend. The project demonstrates key features like product management, shopping cart, and user authentication.

## Features

- User Registration and Login
- Product Listings and Categories
- Add to Cart and Checkout
- Admin Panel for managing products and categories
- Product Search functionality

## Technologies Used

- **Django** for the backend
- **SQLite** for the database
- **HTML**, **CSS**, and **JavaScript** for the frontend
- **Bootstrap** for responsive design
- **Pillow** for image handling

## Getting Started

### Prerequisites

You need to have Python installed on your machine. You can download it from the official [Python website](https://www.python.org/downloads/).

### Installing Dependencies

1. Clone the repository:

    ```bash
    git clone https://github.com/SanjanaReddySangam/Ecommerce-Website.git
    cd Ecommerce-Website
    ```

2. Create a virtual environment:

    ```bash
    python -m venv env
    ```

3. Activate the virtual environment:

    - On Windows:
      ```bash
      env\Scripts\activate
      ```

4. Install the dependencies:

    ```bash
    pip install django Pillow
    ```

5. Run the migrations to set up the database:

    ```bash
    python manage.py migrate
    ```

6. Create a superuser to access the admin panel:

    ```bash
    python manage.py createsuperuser
    ```

7. Run the development server:

    ```bash
    python manage.py runserver
    ```

### Access the website

- Open your browser and visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to see the project in action.
- You can access the admin panel at [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/), using the superuser credentials you created.

## Contributing

Feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
