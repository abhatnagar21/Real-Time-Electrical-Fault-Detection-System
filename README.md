# Real-Time-Electrical-Fault-Detection-System
Overview
This project implements a real-time electrical fault detection system using Python. It simulates electrical signals, processes the data to detect faults based on a threshold, and visualizes the results in real-time. This system can be extended to work with actual sensor data and more advanced fault detection algorithms.

Features
Simulated Electrical Signals: Generates sinusoidal signals with noise to mimic real-world data.
Fault Detection: Identifies faults when the signal exceeds a predefined threshold.
Real-Time Visualization: Displays the signal and detected faults using live plotting.
Getting Started
Prerequisites
Ensure you have Python installed along with the following packages:

numpy
matplotlib
You can install the required packages using pip:

bash
Copy code
pip install numpy matplotlib
Running the Project
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/real-time-fault-detection.git
cd real-time-fault-detection
Run the Script

Execute the script to start the real-time fault detection system:

bash
Copy code
python fault_detection.py
This will open a window displaying the simulated electrical signal and any detected faults.

How It Works
Data Simulation:

The simulate_data function generates a sinusoidal signal with added noise and identifies faults if the signal exceeds a specified threshold.
Fault Detection:

Faults are detected based on a simple threshold method. The system flags any data points where the signal exceeds this threshold.
Real-Time Visualization:

The matplotlib library is used to create real-time plots of the signal. Faults are marked with red markers on the plot.
Customization
Adjust Threshold: Modify the fault_threshold parameter in the simulate_data function to change the fault detection sensitivity.
Signal Frequency: Change the freq parameter in the simulate_data function to simulate different signal frequencies.
