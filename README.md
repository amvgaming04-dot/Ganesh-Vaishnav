# Ganesh-Vaishnav lab task
#lab task 1
sum=0
for i in range(1,1001):
		if i%2==0:
	    	sum+=i
		
sum=0
for i in range(1,1001):
	if i%5==0 and   i%7==0:
		sum+=i
	 
no=int(input("enter the number"))
for i in range(1,11):
		print(no*i)
		
#lab task 2	
age=int(input("enter your age"))
if age >=0 and age<=2:
		print("infant")
elif age>=3 and age<=17:
       print("minor")
elif age>=18 and age<=50:
       print("adult")
elif age>=51 and age<=70:
		print("seniur")  
elif age>=71:
		print("super seniur")
else:
	    print("im god")
