def sortByLength(inputStr):
    return inputStr[0]
 
sp=['Keep calm and carry on']
n = int(input())
for i in range(n):
    sp.append(input())
while True:
    sp.sort(key=sortByLength)    
    sp.sort(key=len)
    for w in sp:
        print(w)
    break
