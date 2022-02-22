n=int(input('enter the values of n'))
osum=0
esum=0
for i in range(1,n+1):
   if i%2==1:
         osum=osum+i 
         else:
            esum=esum+i
print('sum of even',esum)
print('sum is odd',osum)
