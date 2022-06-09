# prak-asd
#nomer 1
##username = '@adam01'
##username = '@adam01'
username = '@adam01_'
cocok = re.findall(r'@+[a-z]+[0-9]+\w', username)
if cocok:
    print(cocok ,'True') 
else:
    print('False')
