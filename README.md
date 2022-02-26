# assignment2-25-02-22
count of positive and negative numbers
count=0
pos=0
neg=0
while(count<5):
    num=int(input('enter a number:'))
    if(num==0):
        break;
    elif(num>0):
        pos=pos+1
    else:
            neg=neg+1
            count=count+1
print("count of positive number is",pos)
print("coutn of negitive number is",neg)
output:
enter a number:4
enter a number:5
enter a number:-6
enter a number:-8
enter a number:9
enter a number:10
enter a number:11
enter a number:-12
enter a number:-13
enter a number:14
enter a number:15
enter a number:16
enter a number:-17
count of positive number is 8
coutn of negitive number is 5
