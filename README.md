**QR Code Generator**
This is a simple Python application that generates QR codes from user input using the pyqrcode and tkinter libraries. The generated QR code is saved as a PNG image file on your local machine.

**Features**
Create QR codes from user input.
Save the generated QR code as a PNG file.
User-friendly graphical interface built with tkinter.
**Requirements**
Python 3.x
pyqrcode library
pypng library
Pillow library (for handling images in tkinter)
**Installation**
**Clone the repository:**
**bash**
**Copy code**
git clone https://github.com/jwrijuhou/qrcode.git
cd qrcode

**Install the required dependencies:**
**bash**
**Copy code**
pip install pyqrcode pypng Pillow

**Usage**
Run the Python script:
**bash**
**Copy code**
python qrcode.py
Enter the text or URL for which you want to generate the QR code in the input field.

Click the Create button.

The QR code will be generated and saved as myqr.png in the same directory as the script.

**Project Structure**
├── qrcode.py  # Main Python script
└── README.md             # This README file
**Example**
When the application runs, you'll see a window like this:
Enter the text or URL in the input field.
Click Create, and the QR code will be saved as myqr.png.
**Libraries Used**
pyqrcode: For generating the QR codes.
pypng: For saving the QR code as a PNG image.
Pillow (PIL): For handling images within the tkinter interface.
tkinter: For building the graphical user interface (GUI).
