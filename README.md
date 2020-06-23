# uri1255
#uri1255.py
n=int(input())
while n:
	newline=''
	n-=1
	maximum=0
	line=input()
	line=line.lower()
	for c in "abcdefghijklmnopqrstuvwxyz":
		k=line.count(c)
		if k>=maximum:
			maximum=k
	for c in "abcdefghijklmnopqrstuvwxyz":
		k=line.count(c)
		if k==maximum:
			newline+=c
	print(newline)
