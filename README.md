n=int(input('enter a number:'))
sum=0
while(n>0):
    rem=n%10
    n=n//10
    sum=sum+rem
print('sum of digits:',sum)

Output:
enter a number:1345
sum of digits: 13
>
