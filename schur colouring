def check(colours):
  c=[]
  for i in colours:
    c.append(i)  
    
  for i in range (1,len(c)+1):
    for j in range (i,len(c)+1):
      x = i + j 
      if x < len(c)+1:
        if c[x-1] == c[i-1] and c[x-1] == c[j-1]:
    
          return False
  return True
          
arr=["R","G","B"]
sol=[]
for i in range(1,15):
  for j in range(len(arr)**i):
    ret=""
    new=j
    for _ in range(i):
      ret+=arr[new%len(arr)]
      new/=len(arr)
      new=int(new)
    if check(ret):
      print("n="+str(i))
      print(ret)
      break
