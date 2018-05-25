# ctf2018

#1.  sCTF 2016 Q1 : banana-boy-20(必)
 
 ![image](https://github.com/610099/ctf2018/blob/master/pic/carter.jpg)
 1)
```
 file carter.jpg
  ```
 2)
 ```
 binwalk carter.jpg
  ```
3)
  ```
  dd if=carter.jpg of=carter-1.jpg skip=140147 bs=1
  ```
  ![image](https://github.com/610099/ctf2018/blob/master/pic/carter-1.jpg)
   
   done
    

#2.Secret@Scratch Dialga1234 - Johnny Boy

1)
```
google Dialga1234(https://scratch.mit.edu/projects/108998724/)
```
2)
```
see and fine
```
3)
```
ABCTF{DoYouThinkISpentTooMuchTimeOnThis}
```


#3.crypto 201
1)
```
150815 **1941 %435979
```
2)
```
133337
```


#4.crypto 202

p =  9648423029010515676590551740010426534945737639235739800643989352039852507298491399561035009163427050370107570733633350911691280297777160200625281665378483
q =  11874843837980297032092405848653656852760910154543380907650040190704283358909208578251063047732443992230647903887510065547947313543299303261986053486569407
e =  65537
c =  83208298995174604174773590298203639360540024871256126892889661345742403314929861939100492666605647316646576486526217457006376842280869728581726746401583705899941768214138742259689334840735633553053887641847651173776251820293087212885670180367406807406765923638973161375817392737747832762751690104423869019034
t = (p-1)*(q-1)
n = p*q
1)
```
d = gmpy2.invert(e,t)
```
2)
```
m = pow(c,d,n)
```
3)
```
print "Solved ! m = %d" % m
```


# DVWA

1) #Command Injection



