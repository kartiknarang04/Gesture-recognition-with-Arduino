---

# LED Controller with Gesture Recognition

This project demonstrates controlling multiple LEDs connected to an Arduino board using Python and the `pyFirmata` library. The Python script communicates with the Arduino board via serial communication to turn the LEDs on or off based on hand gestures detected using the Mediapipe library.

## Prerequisites

Before running the project, make sure you have the following prerequisites installed:

- Python 3.x
- `pyFirmata` library (`pip install pyfirmata`)
- Arduino IDE

## Additional Libraries

In addition to the prerequisites mentioned above, you'll need to install the following Python libraries:

- `mediapipe` library for hand gesture recognition (`pip install mediapipe`)
- `opencv` library for capturing video (`pip install cv2`)

## Getting Started


1. **Upload Arduino Sketch:**
   - Open the Arduino IDE and save the standard firmdata file and save it to the connected arduino board.
   
2. **Connect Hardware:**
   - Connect the LEDs to the digital pins on your Arduino board as specified in the Arduino sketch.
   - Connect the Arduino board to your computer via USB.

3. **Run Python Script:**
   - Open a terminal and navigate to the directory containing the Python script (`main.py`).
   - Run the Python script:
     ```
     python main.py
     ```

## Usage

- Use hand gestures to control the LEDs connected to the Arduino board.
- The Python script uses the `mediapipe` library to detect the number of fingers raised and maps it to the corresponding number of LEDs to turn on.

---
