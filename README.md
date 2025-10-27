# Keithley_programs
These programs were created to control the Keithley 237 SMU and record the current traces at a set voltage. They also allow the use of an AC biasing regime with a specific waveform and sweep time.

## Installation and usage
Install 64-bit python on Windows and run the following commands with it:

```powershell
python -m venv env
.\env\Scripts\Activate
Install necessary modules:

```powershell
pip install -r requirements.txt 
Run app:

```powershell
python Keithley_current_control.py
