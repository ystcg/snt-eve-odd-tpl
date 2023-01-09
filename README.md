def tup_fun(T):
    c1=c2=0
    for i in range(len(T)):
        if T[i]%2==0:
           c1+=1
        else:
            c2+1
    return c1,c2
tup=eval(input("Enter the tuple elements:"))
print("The tuple is:",tup)
ce,co=tup_fun(tup)
print("Number of odd numbers:",co)
print("Number of even numbers:",ce)
