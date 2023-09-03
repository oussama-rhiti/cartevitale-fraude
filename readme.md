# Running the Application - Step-by-Step Guide

Follow these steps to set up and run the application:

1. **Clone the Project**: Create a copy of the project by cloning the repository to your local machine.

2. **Navigate to the Project Directory**: Open a command prompt and change your current path to the folder where you can find the 'app.py' file.

    ```shell
    cd path/to/your/project/directory
    ```

3. **Create a Conda Environment**: Create a new Conda environment for the project using the following command. Replace `<environment_name>` with your chosen name.

    ```shell
    conda create -n <environment_name> python=3.7
    ```

4. **Activate the Environment**: Activate the Conda environment you created in the previous step:

    ```shell
    conda activate <environment_name>
    ```

5. **Install Required Dependencies**: Install the necessary dependencies listed in the 'requirements.txt' file using this command:

    ```shell
    python -m pip install -r requirements.txt
    ```

6. **Run the Application**: Launch the application by running the following command:

    ```shell
    python app.py
    ```

That's it! You've successfully set up and are now running the application. Enjoy using it!
