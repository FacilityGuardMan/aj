import tkinter as tk

class MyCalculator:
    def __init__(self) -> None:

        self.root = tk.Tk()

        self.root.geometry("350x350")
        self.root.title("Mr.Pig's Calculator")

        self.label = tk.Label(self.root, text="Hello! Mr.Sigma", font=('Sans', 18))
        self.label.pack()

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=20, y=50)

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=85, y=50)

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=150, y=50)

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=20, y=120)

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=85, y=120)
        
        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=150, y=120)

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=20, y=190)

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=85, y=190)

        self.button = tk.Button(self.root, text="Click here!", height=4)
        self.button.place(x=150, y=190)

        self.root.mainloop()

MyCalculator()
