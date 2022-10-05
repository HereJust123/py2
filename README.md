# py2: program to check if a number is prime or not
def PrimeChecker(b):  
   
    if b > 1:  
         
        for j in range(2, int(b/2) + 1):  
           
            if (b % j) == 0:  
                print(b, "is not a prime number")  
                break  
         
        else:  
            print(b, "is a prime number")  
    
    else:  
        print(b, "is not a prime number")  
  
b = int(input("Enter an input number:"))  
  
PrimeChecker(b)  
