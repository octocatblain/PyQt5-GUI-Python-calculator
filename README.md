# PyQt5-GUI-Python-calculator
## GUI based Calculator using Python based on MVC Structure
A calculator GUI app using the Model-View-Controller (MVC) design pattern. Developed using PyQt. PyQt is a Python binding for Qt, which is a set of C++ libraries and development tools providing platform-independent abstractions for graphical user interfaces (GUIs). 

Here a simple calculator is created using python which follows the MVC architectural pattern which separates the application in three logical components: the model, the view and the controller

## Create test.py
This file is created to check if the PyQt5 GUI toolkit is installed and working properly in your machine or not.
### Code Sample

```import sys

from PyQt5.QtWidgets import QApplication
from PyQt5.QtWidgets import QLabel
from PyQt5.QtWidgets import QWidget
app = QApplication(sys.argv)

window = QWidget()
window.setWindowTitle('PyQt5 App')
window.setGeometry(100, 100, 280, 80)
window.move(600, 15)
helloMsg = QLabel('This is Test', parent=window)
helloMsg.move(60, 30)

window.show()

sys.exit(app.exec_())
```
Execute the test.py using:

```bash
python test.py
```
If while executing the file you get the error of ```ModuleNotFound``` suggests that PyQt5 is not installed. Install PyQt5 using the following command:

```bash
pip install PyQt5
```
Once installed execute the file and a small window will appear with message ```'This is Test'```.



