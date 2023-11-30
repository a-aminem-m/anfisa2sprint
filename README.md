# Anfisa Ice Cream Catalog

Welcome to the **Anfisa Ice Cream Catalog** project! This Django-based web application is designed to create a comprehensive catalog of various ice cream varieties. Users can explore individual ice cream flavors, while administrators have the ability to curate the main selection displayed on the homepage.

## Project Structure

The project is organized into three main applications:

1. **Main Page App**: Responsible for displaying the homepage with a curated list of ice cream flavors set by the admin.

2. **Catalog App**: Manages the overall catalog, including a full list of all available ice cream flavors and individual pages for each flavor.

3. **About Page App**: Provides information about the project, its purpose, and any additional details.

## Getting Started

Follow these steps to set up and run the project locally:

1. Clone the repository and navigate to it in the command line:

    ```bash
    git clone https://github.com/yandex-praktikum/anfisa2sprint.git
    cd anfisa2sprint
    ```

2. Create and activate a virtual environment:

    **Windows:**

    ```bash
    python -m venv venv
    source venv/Scripts/activate
    ```

    **Linux/macOS:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Upgrade PIP:

    **Windows:**

    ```bash
    python -m pip install --upgrade pip
    ```

    **Linux/macOS:**

    ```bash
    python3 -m pip install --upgrade pip
    ```

4. Install dependencies from the requirements.txt file:

    ```bash
    pip install -r requirements.txt
    ```

5. Perform migrations:

    **Windows:**

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

    **Linux/macOS:**

    ```bash
    python3 manage.py makemigrations
    python3 manage.py migrate
    ```

6. Run the project:

    **Windows:**

    ```bash
    python manage.py runserver
    ```

    **Linux/macOS:**

    ```bash
    python3 manage.py runserver
    ```
