# How to Run the Project:

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
