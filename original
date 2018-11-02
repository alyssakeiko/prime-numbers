from time import*

while True:
    num=input("enter a number above 2: ")
    start=time()
    num=int(num)
    if num==2:
        print ("prime")
    elif num%2==0:
        print ("composite, factor of 2")
       
    else:
        prime=0
        for i in range(3, num, 2):
            if num%i==0:
                print ("composite, factor of ", i)
                prime=1
                break
        if prime==0:
            print ("prime")
           
    end=time()
    totalTime=(end-start)
    totalTime=round(totalTime,1)
    print ("It took ", totalTime, " seconds")
