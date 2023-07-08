# This is a portfolio django project



To run the django project you need to run this command 

``` bash 
python manage.py runserver
```

To pull this Django project locally to your PC you need to follow this steps:

- Clone the repository :
``` bash
https://github.com/Itz-habeeb/Portfolio-project.git
```
- Once the cloning process is complete, navigate to the project directory using the cd command in the terminal :
``` bash
cd PORTFOLIO_WEBSITE
```

- Create a virtual environment with this command :
``` bash
python -m venv venv
```
- Activate the virtual environment :

    - On Windows (Command Prompt) :
        - ```bash
            venv\Scripts\activate
            ```
    - On Windows (PowerShell):


        - ``` bash
            myenv\Scripts\Activate.ps1
            ```
    - On macOS/Linux:
        ``` bash
        source myenv/bin/activate
        ```

- To install project dependencies,use the following command:
    ```bash
    pip install -r requirements.txt
    ```

- To Run database migrations, use the following command:
    ```bash
    python manage.py migrate
    ```

- Then you can now start the server but running:
    ```bash
    python manage.py runserver
    ```

You should see output indicating that the server is running. By default, the development server listens on http://127.0.0.1:8000/.

