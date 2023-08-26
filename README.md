# NetSpeed Tool

## Overview

The NetSpeed tool is a Python script that allows you to perform real-time internet speed tests using the Speedtest.net service. It continuously measures your download and upload speeds and displays the results in Mbps (Megabits per second).

## Prerequisites

Before using this tool, ensure that you have the following prerequisites installed:

- Python 3.x
- Speedtest-cli library (You can install it using `pip install speedtest-cli`)
- figlet (for displaying the tool name)

## Usage

1. Clone the repository or download the `NetSpeed.py` script to your local machine.

2. Open a terminal and navigate to the directory where `NetSpeed.py` is located.

3. Run the script using the following command:

        python NetSpeed.py

4. The tool will continuously measure your internet speed and display the results in Mbps. Press `Ctrl+C` to stop the tool.

## Configuration

You can customize the tool by modifying the `NetSpeed.py` script. Here are some key configuration options:

- **Specific Server**: You can specify a specific server for the speed test by replacing the `"1234"` in the code with the ID of the desired server.

- **Measurement Interval**: By default, the tool measures speed every 5 seconds. You can change the measurement interval by modifying the `time.sleep(5)` line in the code.

## Troubleshooting

If you encounter any issues while using the NetSpeed tool, consider the following:

- Ensure that you have a stable internet connection.
- Check that you have installed the required dependencies as mentioned in the prerequisites section.
- If you face any errors, the tool will display error messages to help you diagnose the problem.

