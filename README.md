principle=0
rate= 0
time = 0

while principle<=0:
    principle=float(input("Enter the principle amount = "))
    if principle<=0:
        print("Principle cant be less than or equal to zero ! ")
       

while rate <=0:
    rate=float(input("Enter the interest rate amount = "))
    if rate <=0:
        print("Interest rate cant be less than or equal to zero ! ")
      

while time <=0:
    time=float(input("Enter the time amount = "))
    if time <=0:
        print("Time cant be less than or equal to zero ! ")

print("Entries = ")
print(f"Principle ={principle}")    
print(f"Rate ={rate} %")    
print(f"Time ={time} years")

total=   principle*pow((1+rate/100),time)
print(f"Your balance after {time} year/s : ${total} ")
