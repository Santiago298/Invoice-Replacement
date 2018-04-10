# Invoice-Replacement
# This repository for a tool to upload a file on a remote server. The tool is to be built in Python.
# invoice_replacement

import sys
from PyQt4 import QtGui

def window():
    app = QtGui.QApplication(sys.argv)
    w = QtGui.QWidget()
    b = QtGui.QLabel(w)
    b.setText("Hello World!")
    w.setGeometry(100,100,200,50)
    b.move(50,20)
    w.setWindowTitle(“PyQt”)
    w.show()
    sys.exit(app.exec_())
	
if __name__ == '__main__':
   window()
