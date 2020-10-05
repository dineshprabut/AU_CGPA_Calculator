# Welcome to CGPA CALCULATOR !
A Simple CGPA calculator using PyQt5.

### Files 
First you have install PyQt5 in your Python Version 3 using Command prompt.

## What are the packages to be installed

**PyQt5** , 
**auto-py-to-exe** and 
**Qt Designer**

## What is Qt Designer 

**Qt Designer** is the **Qt** tool for **designing** and building graphical user interfaces (GUIs) with **Qt** Widgets.

## Create .Ui file and folders

We have to develop the graphical user interfaces (GUIs) for your application using **QT Designer** application. After develop the GUI, create folder for this file and save your .ui folder. 

## Switch to another file

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Convert .ui to .py

You want to convert .ui file to .py by clicking **Command Prompt**. You have to type **cd  >Location of the file<** and click enter.Now you have to type   **pyuic5 -x Filename.ui - o Filename.py** and click enter. Now python has been created.


# Source Code 
You have to type the following code under
 **def retranslateUi(self, MainWindow):**

```self.doubleSpinBox.setMaximum(10)  
self.doubleSpinBox.setMinimum(0)  
self.doubleSpinBox.setDecimals(3)  
self.doubleSpinBox_2.setMaximum(10)  
self.doubleSpinBox_2.setMinimum(0)  
self.doubleSpinBox_2.setDecimals(3)  
self.doubleSpinBox_3.setMaximum(10)  
self.doubleSpinBox_3.setMinimum(0)  
self.doubleSpinBox_3.setDecimals(3)  
self.doubleSpinBox_4.setMaximum(10)  
self.doubleSpinBox_4.setMinimum(0)  
self.doubleSpinBox_4.setDecimals(3)  
self.doubleSpinBox_5.setMaximum(10)  
self.doubleSpinBox_5.setMinimum(0)  
self.doubleSpinBox_5.setDecimals(3)  
self.doubleSpinBox_6.setMaximum(10)  
self.doubleSpinBox_6.setMinimum(0)  
self.doubleSpinBox_6.setDecimals(3)  
self.doubleSpinBox_7.setMaximum(10)  
self.doubleSpinBox_7.setMinimum(0)  
self.doubleSpinBox_7.setDecimals(3)  
self.doubleSpinBox_8.setMaximum(10)  
self.doubleSpinBox_8.setMinimum(0)  
self.doubleSpinBox_8.setDecimals(3)  
  
self.spinBox.setMaximum(35)  
self.spinBox.setMinimum(0)  
self.spinBox_2.setMaximum(35)  
self.spinBox_2.setMinimum(0)  
self.spinBox_3.setMaximum(35)  
self.spinBox_3.setMinimum(0)  
self.spinBox_4.setMaximum(35)  
self.spinBox_4.setMinimum(0)  
self.spinBox_5.setMaximum(35)  
self.spinBox_5.setMinimum(0)  
self.spinBox_6.setMaximum(35)  
self.spinBox_6.setMinimum(0)  
self.spinBox_7.setMaximum(35)  
self.spinBox_7.setMinimum(0)  
self.spinBox_8.setMaximum(35)  
self.spinBox_8.setMinimum(0)  
self.pushButton.clicked.connect(calculateCGPA)
```
## Define CalculateCGPA:

```def calculateCGPA():  
    ui.label_18.setText("9.8")  
    Totalcredits = ui.spinBox.value() + ui.spinBox_2.value() +  \       
                           ui.spinBox_3.value() + ui.spinBox_4.value() + \  
                          ui.spinBox_5.value() + ui.spinBox_6.value() +\ 
                          ui.spinBox_7.value() +ui.spinBox_8.value()  
    CGPA = (ui.doubleSpinBox.value() * ui.spinBox.value() +  
            ui.doubleSpinBox_2.value() * ui.spinBox_2.value() +  
            ui.doubleSpinBox_3.value() * ui.spinBox_3.value() +  
            ui.doubleSpinBox_4.value() * ui.spinBox_4.value() +  
            ui.doubleSpinBox_5.value() * ui.spinBox_5.value() +  
            ui.doubleSpinBox_6.value() * ui.spinBox_6.value() +  
            ui.doubleSpinBox_7.value() * ui.spinBox_7.value() +  
            ui.doubleSpinBox_8.value() * ui.spinBox_8.value()) / Totalcredits  
  
    ui.label_18.setText(str(CGPA))
   ```
## Run 
You can run the file in pycharm or Microsoft visual studio before convert to .exe. Using this you can check whether the application is working correctly or not.

## Convert .py file into .exe 
 You want to convert .py file to .exe by clicking **Command Prompt**. You have to type **auto-py-to-exe** and click enter.Now you can see the dialog box.In the dialog box, you have to upload the file which you to convert to .exe in the path to file option.
1. If you want only .exe file means do this **Onefile > One File option**
2. If you want to hide the console means do this **Console Window > Window Based (hide the console) 
3. You can add Icon for you application by clicking the icon option
Now click **CONVERT TO .PY TO .EXE **.

## Open a file

You can open a file from where you have save the .exe file by double clicking the file or clicking **Open from**.

## Conclusion 
After you have opened the exe file, you may find like below:



![Capture](https://user-images.githubusercontent.com/71083334/95092700-94789380-0745-11eb-97a8-4b584ce72e0c.JPG)
