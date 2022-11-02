# 网格布局框架
f1 = Frame(tk)
f1.pack(padx=20,pady=15)

Label(f1,text='请输入要破解的文章链接：').grid(row= 0,column = 0)
# 字符串 str
in_tony = StringVar()
# 输入框
Entry(f1,width=50,textvariable=in_tony).grid(row= 0,column = 1)
# 按钮
Button(tk,text=' 开始破解 ',command = data).pack()
