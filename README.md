# Assignment-1
l=[1,2,3,4,5,1.1,1.2,1.3,1.4,1.5,"a","b","c","d","e"]
print(l)
#list (l) has been created 
l.append("abc")
print(l)
#"abc" has been added in last in (l)
n=[]
print(n)
#list (n) has been created (blank)
n.insert(0,"blue")
print(n)
#"blue" has been inserted in (n) on index 0
for loop in l:
 print(loop)
#loop l has been created
a=[1,2,3,4,5,6,7,8,9,10]
print(a)
#list (a) has been created
a.sort(reverse=False)
print(a)
#(a) has been arranged in ascending order
a.sort(reverse=True)
print(a)
#(a) has been arranged in descending order
b=["a","b","d","c","e","f","g","h","j","i"]
print(b)
#list (b) has been created
b.sort(reverse=False)
print(b)
#(b) has been arranged in assending order
b.sort(reverse=True)
print(b)
#(b) has been arranged in decsending order
c=[]
print(c)
#list c has been created 
c.insert(0,"add element")
print(c)
#insert elements above
minimum=min(b)
print(minimum)
#the minimum element in (b)
maximum=max(b)
print(maximum)
#the maximum element in (b)
k=[["hello",2],["n"]]
print(k)
#list within a list created 
print(k[0])
#prints 1st inner list of k 
print(k[1])
#prints 2nd inner list of k
print(k[0][1])
#prints 2nd element of 1st inner list
v=[10,"abc",]
print(v)
#list v has been created 
v.append(2)
print(v)
v.insert(2,"def")
print(v)
v.remove(2)
print(v)
v.pop(1)
print(v)
v.copy()
print(v)
#list operations done 
