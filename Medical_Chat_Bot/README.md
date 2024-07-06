# Medical Chat Bot

The Medical Chat Bot is designed to simulate the predictions of a general physician and recommend suitable doctors based on user-entered symptoms. It utilizes decision tree algorithms for symptom analysis and doctor recommendation.

## Project Structure

The project consists of the following files:

- **Testing.csv**: Contains the testing dataset.
- **Training.csv**: Contains the training dataset.
- **Doctors_dataset.csv**: Contains the dataset of doctors.
- **Healthcare_chatbot_console.py**: Python script for the console-based healthcare chatbot.
- **Question_Diagnosis_Tkinter.py**: Python script for the Tkinter-based GUI for question diagnosis.
- **new_login.py**: Main script to start the chatbot application.

## How to Run

To execute the code, follow these steps:

1. Open a Terminal or Shell.
2. Navigate to the project directory.
3. Run the following command:

    ```bash
    python new_login.py
    ```

    This will start the chatbot application, and you can begin entering symptoms to receive doctor recommendations.

## Dependencies

Ensure you have the following Python packages installed:

- pandas
- numpy
- scikit-learn
- tkinter (for GUI)

You can install the required packages using pip:

    ```bash
    pip install pandas numpy scikit-learn
    ```

## Features

- **Symptom Analysis**: Analyzes user-entered symptoms using decision tree algorithms.
- **Doctor Recommendation**: Recommends suitable doctors based on the analysis.
- **User Interface**: Provides both console-based and GUI-based interfaces for user interaction.

## Usage

- Run the main script (`new_login.py`) to start the chatbot.
- Follow the prompts to enter symptoms.
- Receive doctor recommendations based on the analysis.

## Contributing

Feel free to fork this repository, create branches, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements

Thanks to all contributors and those who provided datasets for testing and training.

---

