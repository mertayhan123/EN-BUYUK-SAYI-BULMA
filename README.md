# EN-BUYUK-SAYI-BULMA
print("3 adet sayıdan en büyüğünü yazdıran program")
a=float(input("1.sayı:"))    
b=float(input("2.sayı:"))    
c=float(input("3.sayı:"))    
if (b<=a and a<=c):
    print(c)
elif (b<=a and c<=a):
    print(a)
elif (a<=b and b<=c):
    print(c)
elif (a<=b and c<=b):
    print(b)
elif (c<=a and a<=b):
    print(b)
elif (c<=a and b<=a):
    print(a)
    
