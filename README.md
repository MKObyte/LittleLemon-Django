# LittleLemon Django Project

Welcome to the LittleLemon Django project! This project is a web application built using the Django framework.

## Project Description

The LittleLemon Django project is designed as the final project for the Meta Django Web Framework course.

## Features

### Menu Page

- Display a list of menu items with their names and prices.
- Data for the menu items is dynamically loaded from a Django model.
- The page design includes a for loop to iterate over menu items and display their attributes.

### Menu Item Page

- Show detailed information about a specific menu item.
- Display name, description, and price of the menu item.
- Include a dynamic link to each menu item from the Menu page.
- Use URL parameters to query and display specific menu items.

### Admin Integration

- Use the Django admin panel to manage and add menu items.
- Create a superuser to access the admin panel.
- Add, edit, and update menu items through the admin interface.

### Database Management

- Create and manage Django models for storing menu data.
- Perform migrations to apply changes to the database schema.
- Use SQLite for backend database storage.

### Dynamic Template Rendering

- Utilize Django Template Language (DTL) for dynamic content rendering.
- Create and extend templates for a consistent site layout.
- Implement partial templates for reusable components like footers.

### Static Files Management

- Load and use static files such as images and CSS for styling.
- Ensure static assets are correctly referenced in the templates.


## Screenshot

![Project Screenshot](https://github.com/MKObyte/LittleLemon-Django/blob/main/Screenshot.png)


## Installation

To get a local copy up and running, follow these steps:

### Prerequisites

Make sure you have the following installed:

- Python (3.x recommended)
- Django (latest version recommended)
- Git

### Installation Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/MKObyte/LittleLemon-Django.git
    cd LittleLemon-Django
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv env
    source env/bin/activate   # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```sh
    python manage.py migrate
    ```

5. Run the development server:
    ```sh
    python manage.py runserver
    ```

6. Open your web browser and go to `http://127.0.0.1:8000/` to see the application in action.


## Contributing

Contributions are what make the open source community such an amazing place to be, learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact Information


Project Link: [https://github.com/MKObyte/LittleLemon-Django](https://github.com/MKObyte/LittleLemon-Django)
