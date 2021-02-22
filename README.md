# Price-Comparison
This is a GUI module basedPrice Comparison site. This enables the user to compare the prices of different products over different e-commerce sites.
from tkinter import *
root=Tk()
display=Label(root)
root.title('Price Dheko')
root.configure(bg='light blue')
root.geometry('900x500')


def home():
    root1=Tk()
    root1.title("Price Dheko")
    root1.geometry("1600x8000")
    root1.configure(bg='pink')

    h=Label(root1,font=('Times',35,'bold'),text='Available Products',bg='cyan',bd=15,anchor='w').pack()
    l1=Label(root1,font=('Times',20,'bold'),text='Mobiles',bg='goldenrod',bd=15,width=12).place(x=22,y=120)
    l2=Label(root1,font=('Times',20,'bold'),text='Cameras',bg='goldenrod',bd=15,width=12).place(x=273,y=120)
    l3=Label(root1,font=('Times',20,'bold'),text='Head Phones',bg='goldenrod',bd=15,width=12).place(x=524,y=120)
    l4=Label(root1,font=('Times',20,'bold'),text='Pendrives',bg='goldenrod',bd=15,width=12).place(x=775,y=120)
    l5=Label(root1,font=('Times',20,'bold'),text='Powerbanks',bg='goldenrod',bd=15,width=12).place(x=1026,y=120)
    l6=Label(root1,font=('Times',20,'bold'),text='Televisions',bg='goldenrod',bd=15,width=12).place(x=1277,y=120)

    Label(root1,font=('Times',16,'bold'),text='Oneplus_7tpro',bg='light green',bd=15,width=12).place(x=50,y=220)
    Label(root1,font=('Times',16,'bold'),text='Iphone_11pro',bg='light green',bd=15,width=12).place(x=50,y=260)
    Label(root1,font=('Times',16,'bold'),text='Samsung_note10',bg='light green',bd=15,width=12).place(x=50,y=300)
    Label(root1,font=('Times',16,'bold'),text='Realme_X',bg='light green',bd=15,width=12).place(x=50,y=340)
    Label(root1,font=('Times',16,'bold'),text='Redmi_k20',bg='light green',bd=15,width=12).place(x=50,y=380)
    Label(root1,font=('Times',16,'bold'),text='Asus_rog2',bg='light green',bd=15,width=12).place(x=50,y=420)
    Label(root1,font=('Times',16,'bold'),text='Oppo_reno2',bg='light green',bd=15,width=12).place(x=50,y=460)
    Label(root1,font=('Times',16,'bold'),text='Vivo_v15',bg='light green',bd=15,width=12).place(x=50,y=500)

    Label(root1,font=('Times',16,'bold'),text='Canon_EOS_15D',bg='light green',bd=15,width=12).place(x=300,y=220)
    Label(root1,font=('Times',16,'bold'),text='Nikon_D3500',bg='light green',bd=15,width=12).place(x=300,y=260)
    Label(root1,font=('Times',16,'bold'),text='Fujifilm_X100',bg='light green',bd=15,width=12).place(x=300,y=300)
    Label(root1,font=('Times',16,'bold'),text='Sony_A600Y',bg='light green',bd=15,width=12).place(x=300,y=340)
    Label(root1,font=('Times',16,'bold'),text='Nikon_D7200',bg='light green',bd=15,width=12).place(x=300,y=380)
    Label(root1,font=('Times',16,'bold'),text='Canon_EOS_90D',bg='light green',bd=15,width=12).place(x=300,y=420)
    Label(root1,font=('Times',16,'bold'),text='Sony_6400M',bg='light green',bd=15,width=12).place(x=300,y=460)
    Label(root1,font=('Times',16,'bold'),text='Pentax_k50',bg='light green',bd=15,width=12).place(x=300,y=500)

    Label(root1,font=('Times',16,'bold'),text='Boat_rockerz_400',bg='light green',bd=15,width=13).place(x=545,y=220)
    Label(root1,font=('Times',16,'bold'),text='JBL_T460',bg='light green',bd=15,width=13).place(x=545,y=260)
    Label(root1,font=('Times',16,'bold'),text='Sennheiser_4.5SE',bg='light green',bd=15,width=13).place(x=545,y=300)
    Label(root1,font=('Times',16,'bold'),text='Sennheiser_HD_4.4',bg='light green',bd=15,width=13).place(x=545,y=340)
    Label(root1,font=('Times',16,'bold'),text='Soundlogic_MSD',bg='light green',bd=15,width=13).place(x=545,y=380)
    Label(root1,font=('Times',16,'bold'),text='Boat_rockerz_510',bg='light green',bd=15,width=13).place(x=545,y=420)
    Label(root1,font=('Times',16,'bold'),text='Skullcandy_crusher',bg='light green',bd=15,width=13).place(x=545,y=460)
    Label(root1,font=('Times',16,'bold'),text='Bose_35',bg='light green',bd=15,width=13).place(x=545,y=500)

    Label(root1,font=('Times',16,'bold'),text='Sandisk_32GB',bg='light green',bd=15,width=12).place(x=798,y=220)
    Label(root1,font=('Times',16,'bold'),text='HP_16GB',bg='light green',bd=15,width=12).place(x=798,y=260)
    Label(root1,font=('Times',16,'bold'),text='Kingston_16GB',bg='light green',bd=15,width=12).place(x=798,y=300)
    Label(root1,font=('Times',16,'bold'),text='Sandisk_64GB',bg='light green',bd=15,width=12).place(x=798,y=340)
    Label(root1,font=('Times',16,'bold'),text='Transcend_64GB',bg='light green',bd=15,width=12).place(x=798,y=380)
    Label(root1,font=('Times',16,'bold'),text='HP_128GB',bg='light green',bd=15,width=12).place(x=798,y=420)
    Label(root1,font=('Times',16,'bold'),text='Sony_64GB',bg='light green',bd=15,width=12).place(x=798,y=460)
    Label(root1,font=('Times',16,'bold'),text='Kingston_128GB',bg='light green',bd=15,width=12).place(x=798,y=500)

    Label(root1,font=('Times',16,'bold'),text='MI_10000mAh',bg='light green',bd=15,width=12).place(x=1050,y=220)
    Label(root1,font=('Times',16,'bold'),text='MI_20000mAh',bg='light green',bd=15,width=12).place(x=1050,y=260)
    Label(root1,font=('Times',16,'bold'),text='Syska_10000mAh',bg='light green',bd=15,width=12).place(x=1050,y=300)
    Label(root1,font=('Times',16,'bold'),text='Sony_5000mAh',bg='light green',bd=15,width=12).place(x=1050,y=340)
    Label(root1,font=('Times',16,'bold'),text='Realme_5000mAh',bg='light green',bd=15,width=12).place(x=1050,y=380)
    Label(root1,font=('Times',16,'bold'),text='Intex_10000mAh',bg='light green',bd=15,width=12).place(x=1050,y=420)
    Label(root1,font=('Times',16,'bold'),text='Intex_20000mAh',bg='light green',bd=15,width=12).place(x=1050,y=460)
    Label(root1,font=('Times',16,'bold'),text='Sony_10000mAh',bg='light green',bd=15,width=12).place(x=1050,y=500)

    Label(root1,font=('Times',16,'bold'),text='Oneplus_55',bg='light green',bd=15,width=12).place(x=1300,y=220)
    Label(root1,font=('Times',16,'bold'),text='LG_32',bg='light green',bd=15,width=12).place(x=1300,y=260)
    Label(root1,font=('Times',16,'bold'),text='TCL_40',bg='light green',bd=15,width=12).place(x=1300,y=300)
    Label(root1,font=('Times',16,'bold'),text='Samsung_40',bg='light green',bd=15,width=12).place(x=1300,y=340)
    Label(root1,font=('Times',16,'bold'),text='Samsung_43',bg='light green',bd=15,width=12).place(x=1300,y=380)
    Label(root1,font=('Times',16,'bold'),text='TCL_55',bg='light green',bd=15,width=12).place(x=1300,y=420)
    Label(root1,font=('Times',16,'bold'),text='Micromax_32',bg='light green',bd=15,width=12).place(x=1300,y=460)
    Label(root1,font=('Times',16,'bold'),text='LG_43',bg='light green',bd=15,width=12).place(x=1300,y=500)
        
    Button(root1,font=('Times',16,'bold'),text='Compare Prices',bg='goldenrod',bd=16,width=14,command=comp).place(x=680,y=630)
    root1.mainloop()
    

def comp():
    import tkinter as tk
    from tkinter import messagebox

    root2=Tk()
    root2.title('Price Dheko Comparison')
    root2.geometry('1600x8000')
    root2.configure(width=1500,height=600,bg='light yellow')
    
    def searchitem():
           entry1.delete(0, END)
           entry2.delete(0, END)
           entry3.delete(0, END)
           entry4.delete(0, END)
           entry5.delete(0, END)
           flag = 1
           e1 = entry6.get()
           with open("pro_details.txt") as f:
               for line in f:
                  if str(e1) in line:
                    flag = 0
                    break
               try:
                   if flag != 1:
                      v = list(line.split(" "))
                      entry1.delete(0, END)
                      entry2.delete(0, END)
                      entry3.delete(0, END)
                      entry4.delete(0, END)
                      entry5.delete(0, END)
                      entry1.insert(0, str(v[0]))
                      entry2.insert(0, str(v[1]))
                      entry3.insert(0, str(v[2]))
                      entry4.insert(0, str(v[3]))
                      entry5.insert(0, str(v[4]))
               except:
                   messagebox.showinfo("Title", "error end of file")
               if flag !=0:
                   messagebox.showinfo("Title", "NOT FOUND")
           f.close()

    def clearitem():
        entry1.delete(0, END)
        entry2.delete(0, END)
        entry3.delete(0, END)
        entry4.delete(0, END)
        entry5.delete(0, END)
        entry6.delete(0, END)

    label0= Label(root2,text=" PRICE COMPARISION ",bg="Black",fg="white",font=("Times", 40))
    label1=Label(root2,text="Product Name",bg="Black",fg="white",font=("Times", 15),width=25,bd=8,relief="ridge")
    entry1=Entry(root2,font=('Times',14),bd=8,width=25,bg='white')
    label2=Label(root2,text="Amazon",bg="Black",fg="white",font=("Times", 15),width=25,bd=8,relief="ridge")
    entry2=Entry(root2,font=('Times',14),bd=8,width=25,bg='white')
    label3=Label(root2,text="Flipkart",bg="Black",fg="white",font=("Times", 15),width=25,bd=8,relief="ridge")
    entry3=Entry(root2,font=('Times',14),bd=8,width=25,bg='white')
    label4=Label(root2,text="PayTm Mall",bg="Black",fg="white",font=("Times", 15),width=25,bd=8,relief="ridge")
    entry4=Entry(root2,font=('Times',14),bd=8,width=25,bg='white')
    label5=Label(root2,text="Ebay",bg="Black",fg="white",font=("Times", 15),width=25,bd=8,relief="ridge")
    entry5=Entry(root2,font=('Times',14),bd=8,width=25,bg='white')
    label6=Label(root2,text="Enter Product Name",bg="Black",fg="white",font=("Times", 20),width=26,bd=9,relief="ridge")
    entry6=Entry(root2,font=('Times',18),bd=10,width=30,bg='white')
    button1=Button(root2,text="Search Item",font=('Times',14),bg='green',bd=8,width=20,command=searchitem)
    button2=Button(root2,text="Clear",font=('Times',14),bg='green',bd=8,width=20,command=clearitem)
    
    label0.grid(columnspan=15, padx=500, pady=40)
    label1.grid(row=1,column=0, padx=10, pady=10)
    label2.grid(row=2,column=0, padx=10, pady=10)
    label3.grid(row=3,column=0, padx=10, pady=10)
    label4.grid(row=4,column=0, padx=10, pady=10)
    label5.grid(row=5,column=0, padx=10, pady=10)
    label6.grid(row=2,column=2, padx=(140,0), pady=10, columnspan=2)
    entry1.grid(row=1,column=1, padx=40, pady=10)
    entry2.grid(row=2,column=1, padx=10, pady=10)
    entry3.grid(row=3,column=1, padx=10, pady=10)
    entry4.grid(row=4,column=1, padx=10, pady=10)
    entry5.grid(row=5,column=1, padx=10, pady=10)
    entry6.grid(row=3,column=2, padx=(140,0), pady=10, columnspan=2)
    button1.grid(row=4,column=2, padx=(150,0))
    button2.grid(row=4,column=3)

    root2.mainloop()


Label(root,text="Welcome to our website \nPrice Dehko",bg="light blue",font=('Times new roman',40,'bold')).place(x=180,y=100)
Button(root,text="Click Here!",bd=10,font=('Times new roman',20,'bold'),command=home).place(x=370,y=300)
