a = int(input("Enter a number:"))
series=[]
for i in range(a):
   series.append(2*i+1)
print(",".join(str(num) for num in series))
