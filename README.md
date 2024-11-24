# style_transfer_webcam_TF
A Python-based GUI application that uses TensorFlow Hub to apply real-time artistic style transfer to webcam video feeds, allowing users to load custom style images and view the transformed output instantly.

How to Run the Python Style Transfer App
Follow these steps to set up and run the real-time style transfer application:

1. Install Required Dependencies
Ensure you have Python installed (specifically /usr/local/bin/python3.10). Install the required Python libraries by running:

bash
Copy code
/usr/local/bin/python3.10 -m pip install tensorflow-macos tensorflow-metal tensorflow-hub opencv-python pillow
2. Prepare the Application Files
Save the application code as style_transfer_gui.py.
Place the generated style.jpg (or your custom style image) in the same directory as style_transfer_gui.py.
3. Run the Application
Execute the script using your preferred Python version:

bash
Copy code
/usr/local/bin/python3.10 style_transfer_gui.py
4. How to Use the App
Load a Style Image:
Click the "Load Style Image" button and select an image file (e.g., style.jpg).
Start the Webcam:
Click the "Start Webcam" button to see the real-time style transfer effect applied to your webcam feed.
Stop the Webcam:
Click the "Stop Webcam" button to stop the style transfer and release the webcam.
5. Troubleshooting
If the webcam doesn't work:
Grant camera permissions in System Preferences > Security & Privacy > Privacy > Camera.
Ensure no other application is using the webcam.
If style.jpg cannot be loaded:
Ensure the file path is correct or choose another valid image when prompted.
