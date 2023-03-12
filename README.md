#llegal Logging Detection with Raspberry Pi
This GitHub repository contains code for detecting illegal logging using a Raspberry Pi and TensorFlow Lite. The TensorFlow model was trained using Edge Impulse, and then converted to TensorFlow Lite for deployment on the Raspberry Pi.

Setup
Before running the code, you'll need to set up the hardware and software.

Hardware Requirements
Raspberry Pi 4 Model B or later
Camera module
MicroSD card with Raspberry Pi OS installed
Software Requirements
Python 3
TensorFlow Lite
Edge Impulse CLI
Installation
Clone this repository to your Raspberry Pi using git clone https://github.com/<your-username>/illegal-logging-detection.git.
Install TensorFlow Lite by running pip3 install tflite-runtime.
Install the Edge Impulse CLI by running npm install -g edge-impulse-cli.
Usage
To run the code, navigate to the project directory and run the command python3 detect_logging.py. This will start the camera and begin detecting illegal logging activity.

Customization
If you want to use your own TensorFlow Lite model, you can replace the model.tflite file in the models directory with your own model file. Make sure the file is named model.tflite.

You can also adjust the detection threshold by changing the threshold variable in the detect_logging.py file.

