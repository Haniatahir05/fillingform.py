## Automation Form Filler
A Python-based utility designed to streamline the process of collecting and organizing user data. This application serves as a foundation for automated form processing, data entry tasks, or simple user surveys, ensuring that information is captured accurately through a command-line interface.
## Key Features
* Interactive Data Collection: Prompts users for specific information (e.g., Name, Email, Contact, Address) in a structured sequence.
* Input Validation: Basic logic to ensure that required fields are not left empty and meet specific criteria.
* Formatted Output: Generates a clean summary of the entered data for review or further processing.
* Reusable Logic: Built with modular functions that can be easily adapted for different types of forms or surveys.
## Technical Implementation
The project is implemented in fillingform.py and showcases several fundamental Python concepts:
* String Manipulation: Using methods like .strip() and .title() to clean and format user input.
* Control Flow: Utilizing if-else statements to validate input and while loops to allow for re-entry of data if errors occur.
* Data Structures: Storing collected information in dictionaries or lists for easy access and manipulation.
* Standard I/O: Efficient use of the input() function for data gathering and print() for formatted reporting.
## Installation & Usage
### Prerequisites
* Python 3.x installed. You can verify this by running:
```Bash```
python --version
```Bash```
### Running the Script
1. Clone the repository:
```Bash```
git clone https://github.com/Haniatahir05/fillingform.py.git
```Bash```
2. Navigate to the project directory:
```Bash```
cd fillingform.py
```Bash```
3. Execute the application:
```Bash```
python fillingform.py
```Bash```
## User Workflow
1. Start: Launch the script via the terminal.
2. Entry: Follow the on-screen prompts to enter your personal or professional details.
3. Review: The system displays a summarized "Submission Form" for your verification.
4. Completion: Choose to submit the data or clear the entries to start over.
## Future Enhancements
* File Export: Adding functionality to save form responses to a .csv, .json, or .txt file.
* GUI Integration: Developing a visual form using libraries like Tkinter or PySide.
* Browser Automation: Integrating with Selenium to automatically push the collected data into web-based forms.
