# List
mevalar=['anor','olcha','banan','uzum','gilos']
narxlar=[10000,15000,12000,14000,16500]
sonlar=['bir','ikki','uch',4,5,6]
ismlar=[]

print("Birinchi meva>>>",mevalar[0])
print(mevalar[-1].title())
print(mevalar[-2].upper())
print(mevalar[:-1])
print(mevalar[:-2])
print(mevalar[-2:])
print(mevalar[-1:])
print(mevalar[2:])
print(mevalar[1:])
print(mevalar[:2])
print(mevalar[:3])
'''Javoblari
Birinchi meva>>> anor
Gilos
UZUM
['anor', 'olcha', 'banan', 'uzum']
['anor', 'olcha', 'banan']
['uzum', 'gilos']
['gilos']
['banan', 'uzum', 'gilos']
['olcha', 'banan', 'uzum', 'gilos']
['anor', 'olcha']
['anor', 'olcha', 'banan']'''

mevalar=['anor','olcha','banan','uzum','gilos']
narxlar=[10000,15000,12000,14000,16500]
sonlar=['bir','ikki','uch',4,'bir',5,6]
ismlar=[]

sonlar[1]=5
print(sonlar)


'''qoshish'''
mevalar.append('behi')
print(mevalar)
sonlar.append(7)
print(sonlar)
sonlar.insert(1, 2)
print(sonlar)

'''elementni ochirish'''
del sonlar[-1]
print(sonlar)

sonlar.remove(6)
sonlar.remove('bir') #Birinchi qiymatni ochiradi
print(sonlar)

'''Elementni sugurib olish'''
print(sonlar)
ikki_sonlar=[]
ikki_sonlar=sonlar.pop(0)
ikki_sonlar=sonlar.pop() #index berilmasa oxirgi qiymatni sugurib oladi.
print(ikki_sonlar)
print(sonlar)
'''Javoblari
['bir', 5, 'uch', 4, 'bir', 5, 6]
['anor', 'olcha', 'banan', 'uzum', 'gilos', 'behi']
['bir', 5, 'uch', 4, 'bir', 5, 6, 7]
['bir', 2, 5, 'uch', 4, 'bir', 5, 6, 7]
['bir', 2, 5, 'uch', 4, 'bir', 5, 6]
[2, 5, 'uch', 4, 'bir', 5]
[2, 5, 'uch', 4, 'bir', 5]
5
[5, 'uch', 4, 'bir']'''


