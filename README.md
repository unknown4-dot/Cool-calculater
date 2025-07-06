import os 
import time 

os.system("clear")

print("""\033[33m
   ____      _            _       _             
  / ___|__ _| | ___ _   _| | __ _| |_ ___ _ __  
 | |   / _` | |/ __| | | | |/ _` | __/ _ \ '__| 
 | |__| (_| | | (__| |_| | | (_| | ||  __/ |    
  \____\__,_|_|\___|\__,_|_|\__,_|\__\___|_|    
                                                
""")

print("\nWelcome To The Calculater App\n")

op = ["+", "*", "-",]

num1 = int(input("enter the first number please\n"))
op = input("\nenter the opperation you want\n")
num2 = int(input("\nenter the second number please\n"))

print("\nwait...\n")
time.sleep(3)

if op == "+":
    print(num1 + num2)
elif op == "*":
    print(num1 * num2)
elif op == "-":
    print(+ num1 - num2)
else:
    print("you picked the wrong opperation sir")
