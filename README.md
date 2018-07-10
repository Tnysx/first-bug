# first-bug#
box=[i for i in range(10,21)]
grbage=[]
validbox=[]
iffound= [] 
for wt in box:
	if wt not in range(10,21):
	   grbage.append(wt)
	else:
	  validbox.append(wt)
print("blackboxes listing:",grbage)
print("valid box listing:",validbox)
print("found:",iffound)
#found the bug blackboxes box range was 100 on the dot changed that by matching with the valid box now theyre 0 blackboxes 10,21 valid run this to find out added on iffound

