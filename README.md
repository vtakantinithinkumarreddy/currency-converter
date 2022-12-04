
# Currency Converter
res = 0
ind = 1
pnds = 92.19
eurs = 81.36
usd = 81.31
cnd = 60.17
chin = 11.23
rus = 1.32
pnkrpe=2.75
singapdollar=59.32
cur_lst1 = ["1: Pounds", "2: Euros", "3: US Dollars", "4: Canadian Dollars", "5: Chinese Yuan", "6: 
Russia Rubel","7: pakistanrupee","8: singaporedollar"]
inp = float(input("Enter in Indian Rupees: "))
for a in cur_lst1:
 print(a)
x = int(input("Select a currency to convert: "))
if x == 1:
print(f'{inp / pnds:.3f}')
elif x == 2:
print(f'{inp / eurs:.3f}')
elif x == 3:
print(f'{inp / usd:.3f}')
elif x == 4:
print(f'{inp / cnd:.3f}')
elif x == 5:
print(f'{inp / chin:.3f}')
elif x == 6:
print(f'{inp / rus:.3f}')
elif x== 7:
print(f'{inp / pnkrpe:.3f}')
elif x== 8:
print(f'{inp / singapdollar:.3f}')
else:
print("Wrong input")
