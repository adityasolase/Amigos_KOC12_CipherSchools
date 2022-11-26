# Amigos_KOC12_CipherSchools
#to enter a positive integer range [A,b] and system will find out the status (Primr or Composite) of each number is available in the given range.At the end print the count also.
def countPrimeComposite(x,y):
    p=0
    c=0
    cd=0
    for i in range(x,y+1):
        for j in range(1,i+1):
            if(i%j==0):
                cd+=1
        if(cd==2):
            print(i,' is prime')
            p+=1
        else:
            print(i,' is composite')
            c+=1
        cd=0
        
    print(p,' prime and ',c,' composite numbers are present within the range')
x=int(input("Enter the starting range"))
y=int(input("Enter the ending range"))
countPrimeComposite(x,y)
