Project: Mini Project
Description
This project is an Image Editor application that allows users to perform various image processing tasks such as:

Flipping
Rotating
Converting to Black & White
Resizing
Adjusting Brightness, Contrast, and Saturation
The application uses Streamlit for the user interface and various Python libraries for image processing.

Installation
Step 1: Create a Virtual Environment
Navigate to your project directory and create a virtual environment:

bash
Copy code
python -m venv env
Step 2: Activate the Virtual Environment
On Windows:
bash
Copy code
.\env\Scripts\activate
On macOS/Linux:
bash
Copy code
source env/bin/activate
Step 3: Install Dependencies
Install the required dependencies using pip:

bash
Copy code
pip install -r requirements.txt
If you do not have a requirements.txt file, install dependencies individually:

bash
Copy code
pip install streamlit pillow numpy
Running the Application
To run the application, execute the following command:

bash
Copy code
streamlit run app.py
Purpose of Each Component
app.py
This is the main script that defines the image processing functions and the Streamlit interface. It includes:

process_image: The main function that processes the image based on user inputs.
Streamlit Widgets for user interaction (file upload, sliders, checkboxes, buttons).
Dependencies
Streamlit: Used for creating the web-based user interface.
Pillow: Used for various image processing tasks such as flipping, rotating, resizing, and adjusting brightness/contrast.
NumPy: Used for numerical operations.
Notes
Ensure all dependencies are installed in a virtual environment if necessary.
The processed images will be saved in the same directory as processed_image.<format>.
If you face any issues, check the terminal for error messages.
