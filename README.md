# texteditor-py
#![Screenshot 2022-12-26 202429](https://user-images.githubusercontent.com/119044548/211377371-003541da-2d5a-4370-97c6-f2577c01894f.png)
Text Editor in Python
from tkinter import*
from tkinter.filedialog import *

root=Tk()
root.title("Text Editor")
root.geometry('200x200')
text=Text(root,width=200,height=200)
text.pack()

root.mainloop()
