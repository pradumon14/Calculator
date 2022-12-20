# Calculator
This is a simple Python program that uses the Tkinter library to create a graphical user interface (GUI) for a calculator. The program creates a window with a title, a text entry field where the user can enter an arithmetic expression, and a button that the user can click to calculate the result of the expression.

When the program starts, it creates an instance of the Root class, which is a subclass of the Tk class from Tkinter. The Root class has a constructor (__init__ method) that sets up the GUI elements and their layout.
# Install Tkinter
```
pip install tk
```

The Root class has three instance variables:

<b>title_label :</b> a Label widget that displays the title of the calculator </br>
<b>entry :</b> an Entry widget that allows the user to enter an arithmetic expression </br>
<b>label :</b> a Label widget that will display the result of the calculation</br>
<b>button :</b> a Button widget that the user can click to trigger the calculation</br>
The onclick method is called when the user clicks the "calculate" button. It uses the eval function to evaluate the arithmetic expression entered by the user and displays the result in the label widget.

Finally, the program calls the mainloop method on the Root instance to start the event loop that listens for user input and updates the GUI accordingly.
