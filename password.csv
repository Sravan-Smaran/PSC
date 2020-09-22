import numpy as np
import matplotlib.pyplot as plt
import pandas as pd import tkinter as tk
def create_gui():
root = tk.Tk() root.geometry("350x400")
password = tk.StringVar(None)
root.title "Techack --- Password Strength Calculator )
define strength check(passed): dataset = pd.read csv( 'password.csv')
datas = np. array(dataset)
x = (s[o] for s in datas) y = (s[1] for sin datas]
def makeToken(f):
tokens = [] for i in f: tokens.append(i) return tokens
from sklearn. feature extraction.text import CountVectorizer from sklearn.feature extraction.text import TfidfVectorizer vectorizer = TfidfVectorizer(tokenizer =makeToken) X = vectorizer.fit transform(x)
from sklearn.model_selection import train test split x train, x test, y train, y test = train test split(x, y, test size = 0.4, random state =1
from sklearn.linear_model import LinearRegression Ir = LinearRegression() Ir.fit(x_train, y_train)
arri = 0)
arrl.append(passed)
arri = vectorizer, transform(arri)
y predict = lr.predict(arri)
pas = tk.Label(root, text = "Your password strength is " ,font=('caltbre', 11, 'bold ))
pas.grid(row=6,column=8)
pas = tk.Label(root, text = y predict ,font={"calibre', 18, 'bold')) pas.grid(row=7,column=) tk. Pack()
message = tk. Label(root, text =" A Basics Program by Techacks", font=('calibre', 'bold' ))

message.grid(row=) password input.grid row=2) message = tk. Label(root, text=" ", font=('calibre',3, 'bold'))
message = tk.Label(root, text = " ", font={'calibre', 15, 'bold'))
message.grid(row=1)
password input = tk. Label(root, text = Enter Your Password ',font=('calibre', 12, 'bold'))
message = tk.Label(root, text=" ", font=( 'calibre',3, 'bold'))
message.grid( row=3)
password_entry = tk.Entry(root, textvariable = password, font=('calibre', 10, 'normal')) password entry.grid(row=4)
message.grid(row=5) var = password entry.bind("<Return>", lambda x: strength check(password entry.get()))
tk mainloop()
create gui( )




