# PalindromicPrime-Number-finding
To find nth PalindromicPrime of given input 
x=int(input("Enter n to find nth prime palindrome: "))
primePalindromes=[]
n=1
while True:
    n+=1
    reverse=int(str(n)[::-1])
    if n == reverse:
        if n>1:
            for i in range(2,n):
                if (n%i)==0:
                    break
            else:
                primePalindromes.append
    if len(primePalindromes)>=x:
        print(f"{x} th palindrome is {primePalindromes[x-1]}")
        break
