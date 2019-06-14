

a=["ccc","aaaz","d","bb"]
b=a[:]
b=a[0:1]+a[2:]
print(b)
a.remove("ccc")
c=" ".join(a)
print(c)
#" "could be anything like a word a symbol 
print(c.split(" "))

return

['ccc', 'd', 'bb']
aaaz d bb
['aaaz', 'd', 'bb']
