# PixelWindowViewer

Worked with ChatGPT Code Editor to create an application that allows users to view the pixel size of a window by adjusting the window, selecting an aspect ratio from the options provided, or creating a valid custom aspect ratio.

This was another prompt engineering and long (nearly 2 working days) conversation session with ChatGPT to create a usable application that allowed users to resize a dummy window in real time to view the pixel size of the window. The relevant application is for newbies like myself who need a visual on a window size when writing code.

My initial prompt is below. There are still a few issues that I may try to resolve, but at this point, it will only be when I don't have anything else to do in the far future.

Prompt:

You are a Python dev of 27 years specializing in creating tools for other devs. Your current project holds a special place in your heart. You are tasked with creating a gui that helps other devs create the size dimensions of an empty window through manipulating a "dummy" window. Here are the specific requirements:

Must be written in Python.

GUI Requirements:

Main Window: 

Size: 400x800px
Background color: RGB: 224, 224, 224 / Hex# E0E0E0
Word colors: RGB: 0, 0, 0 / Hex # 000000
Button colors: RGB: 96, 96, 96 / Hex # 606060
Button Word color: RGB: 255, 255, 255 / Hex # FFFFFF

Font script of title: Open Sans, Bold case
Font size of title: 51.88px
Title: "Pixel Window Viewer"

Font script of body: Open Sans, Regular case
Font size of body and buttons: 19.531px
Button0 name: "Start"

Options Window:

Size: 400x800px
Background color: RGB: 224, 224, 224 / Hex# E0E0E0
Word colors: RGB: 0, 0, 0 / Hex # 000000
Buttons: Open Sans, Regular case
Font size of buttons: 19.531px
Button1 name: "Maintain Aspect Ratio"
Button2 name: "Free Form"


Dummy Window:

Starting Size: 800x800px
Background color: RGB: 64, 64, 64 / Hex# 404040
Word color: RGB: 255, 255, 255 / Hex # FFFFFF
Font script of output: Open Sans, Bold case
Font size of output: 19.531px

Logic Requirements:

Main Window:
1) Clicking the "Start" button begins the script.
2) Clicking the X button at the top right hand corner of the screen ends the script and closes the screen.
3) Window automatically changes to the Options window once the "Start" button is clicked.

Options window:
1) Clicking the "Maintain Aspect Ratio" button runs the script to ensure that any changes to the dummy window maintains the aspect ratio of the window no matter how it was manipulated.
2) Clicking on the "Free Form" button runs the script and does not maintain the aspect ratio
3) Does not close once either button is clicked.
4) Clicking the X button at the top right hand corner of the screen ends the script and closes the screen.

Dummy window:
1) Allows the user to adjust the size of the window while displaying the length and width of the window size in pixels. For example "255 X 300"
2) Clicking the X button at the top right hand corner of the screen closes the screen, but does NOT end the script.

Ask me any additional questions, one at a time, if you need any additional information.
