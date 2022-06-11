# Dice-simulator
import tkinter as tk
from tkinter import *
from PIL import ImageTk, Image

import random
root=tk.Tk()
root.geometry('500x400+300+200')
root.title('Dice Simulator')
root.configure(bg='Green')

# label
l1=Label(root,bg='Green', font='arial 20 bold', fg='red')
l1.place(x=250,y=50)

# logic
def num_gen():
    l= [1,2,3,4,5,6]
    ran_num =random.choice(l)
    if ran_num==1:
        img=Image.open('1.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==2:
        img=Image.open('2.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==3:
        img=Image.open('3.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==4:
        img=Image.open('4.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root,image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==5:
        img=Image.open('5.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    else:
        img=Image.open('6.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
       
# image read
img=Image.open('download.jpg')
res=img.resize((150,100))
org_img=ImageTk.PhotoImage(res)

# Button
b1=Button(root,image=org_img,command=num_gen)
b1.place(x=200,y=200)


root.mainloop()import tkinter as tk
from tkinter import *
from PIL import ImageTk, Image

import random
root=tk.Tk()
root.geometry('500x400+300+200')
root.title('Dice Simulator')
root.configure(bg='Green')

# label
l1=Label(root,bg='Green', font='arial 20 bold', fg='red')
l1.place(x=250,y=50)

# logic
def num_gen():
    l= [1,2,3,4,5,6]
    ran_num =random.choice(l)
    if ran_num==1:
        img=Image.open('1.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==2:
        img=Image.open('2.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==3:
        img=Image.open('3.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==4:
        img=Image.open('4.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root,image=org)
        l2.image=org
        l2.place(x=250,y=50)
    elif ran_num==5:
        img=Image.open('5.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
    else:
        img=Image.open('6.png.png')
        res=img.resize((100,80))
        org=ImageTk.PhotoImage(res)
        l2=Label(root, image=org)
        l2.image=org
        l2.place(x=250,y=50)
       
# image read
img=Image.open('download.jpg')
res=img.resize((150,100))
org_img=ImageTk.PhotoImage(res)

# Button
b1=Button(root,image=org_img,command=num_gen)
b1.place(x=200,y=200)


root.mainloop()
