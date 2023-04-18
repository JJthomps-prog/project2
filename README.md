Yuehan Qin yqin18@stevens.edu, Rudresh Mahesh Jetani rjetani@stevens.edu
# project2
# the URL of your public GitHub repo
https://github.com/JJthomps-prog/project2.git
# an estimate of how many hours you spent on the project
40 hours
# a description of how you tested your code
## Low-level parsing test
print 1+2+3  6.0   
print 1+2*3  7.0    
print (1+2)*3  9.0  
print 1+3/2  2.5  
print (1+3)/2  2.0  
print -5 ^ 2 * 3 + 4 % 2 - -1  ***76.0***  
print 3 + 4 * 5 - 6  17  
print 8 - 4 / 2 + 6 % 4  8  
print 2 * 3 ^ 2  18  
print 12 / 4 * 2 + 3 % 2  7  
print -5 ^ 2  25  
print 6 * 2 / 3  4  
print 10 % 3 + 2 * 5  11  
print 2 ^ 3 ^ 2  512  
print -6 / 2  -3  
print 5 * -2 + 3 * (4 + 1)  5  
x = 2
y = 3
z = x + y * 2 % 4
print x,y,z
2.0 3.0 2.0
print ++x 3.0
print --x 2.0  
## Evaluation
print x,y 0.0 0.0  
print 1,2 1.0 2.0 
## Errors
print 1 + 2 / parser error  
print 0 / 1, 1 / 0.0 divide by zero  
## Op-equals
x = 2  
y = 3   
x += 2   
y -= 1  
x *= y  
y /= x  
x ^= y  
x %= 1  
print x,y  
0.681792830507429 0.25
## Relational operations
print 1<=2  
print 2>=3  
print -3<6  
print 6>9  
print 1==1  
print 1!=1  
1 0 1 0 1 0  
x = -3 y = 1
print x < y  
print x > y  
print x == y  
print x <= y  
print  x >= y 
print  x != y  
1 0 0 1 0 1 
## Boolean operations
print 1 && 0  
print 1 && -2  
print 0 && 1 && -2  
print 0 && 1 || -2  
print !1 && 2  
0 1 0 1 0  
## Comments
print 1 #asdhjaoisjdoasjdojasodjasodij  
1.0  
```
print 1/*aosijdaosijdoasijdoasijdo  
aojsidaosijdoasijdoaisjd   
aishduaisdjaisojdaoisjdo*/print 1  
```
1.0 1.0  
# any bugs or issues you could not resolve
No
# an example of a difficult issue or bug and how you resolved
*,/,% is different with other features they must be written in the same function. Then it won't have error when run % before or after * and /.
# a list of the four extensions you’ve chosen to implement
Op-equals,Relational operations,Boolean operations,comments
