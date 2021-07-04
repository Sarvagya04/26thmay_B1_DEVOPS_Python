# 26thmay_B1_DEVOPS_Python



# Day1 Task Textfile
```
import ctypes
x=input("Enter Any Number: ")
ad=id(x)
print(ad)
print("Fetching Value Using Address....")
print("Value is: " , ctypes.cast(ad, ctypes.py_object).value)
```

