# volcanic_level_checker
Digital signage displaying the eruption alert level of Japan's constantly monitored volcanoes

## Program Description

This program is a GUI application that monitors the volcanic activity levels of active volcanoes in Japan in real-time. Currently, it displays the volcanic information for specific volcanoes such as Turumidake and Garan-dake. In the future, the program is planned to be expanded to monitor all of Japan's constantly monitored volcanoes. The background color and text color of the display change based on the volcanic alert level, allowing users to easily understand the volcano's status.
Usage

    Set up a Virtual Environment: The program runs within a virtual environment (venv). First, create the virtual environment.

python -m venv venv

Activate the Virtual Environment: Activate the virtual environment.

    Windows:

venv\Scripts\activate

macOS/Linux:

    source venv/bin/activate

Install Required Libraries: The required libraries are already included in the venv. If not already installed, you can install them with the following command:

pip install -r requirements.txt

Note: requirements.txt should be pre-configured with the necessary libraries like requests, beautifulsoup4, and tkinter.

Run the Program: Once the libraries are installed, you can run the program.

    python your_program_name.py

    Operation: The program will display the volcano information in full-screen mode, updating in real-time. The background color changes based on the volcanic alert level, providing a visual indication of the volcano's status. You can exit the program by pressing the Esc key.

## Future Expansion

Currently, the program only monitors specific volcanoes, such as Turumidake and Garan-dake. However, in the future, the program will be expanded to monitor all of Japan's constantly monitored volcanoes. This will allow users to check the status of multiple volcanoes across Japan in real-time, giving them a broader view of volcanic activity nationwide.
