# 03
#1) CREAT A TUPLE
 tpl1 = (1,2,3,4,5)
 print(tpl1)

#2) ACCESS TUPLE ELEMENTS
 tpl2 = (1,2,3,4,5)
 print(tpl2[0])
 print(tpl2[3])
 print(tpl2[2])

#3) TUPLE LENTGH
 tpl3 = (1,2,3,4,5)
 print(len(tpl3))

#4) CONCATENATE TUPLES
 tpl4 = (1,2,3)
 tpl5 = (4,5)
 combined = tpl4 + tpl5
 print(combined)

#5) REPEAT TUPLE ELEMENTS
 tpl6 = (1,2,3)
 repeated = tpl6 * 3
 print(repeated)

#6) FIND INDEX OF ELEMENTS
 tpl7 = (1,2,3,4,5)
 ind = tpl7.index(4)
 print(ind)

#7) COUNT OCCURRENCES OF ELEMENTS
 tpl8 = (1,2,3,3,4,3)
 count = tpl8.count(3)
 print(count)

#8) UNPACK TUPLE
 tpl9 = (1,2,3,4,5)
 a,b,c,d,e = tpl9
 print(a,b,c,d,e)

#9) CHECK IF ELEMENT EXISTS 
 tpl10 = (1,2,3,4,5)
 exists = 5 in tpl10
 exist = 6 in tpl10
 print(exists)
 print(exist)

#10) CONVERT LIST TO TUPLE
 tpl10 = (1,2,3,4,5)
 lst1 = list(tpl10)
 print(lst1)

#11) CREAT A LIST
 lst2 = [1,2,3,4,5]
 print(lst2)

#12) ACCESSLIST ELEMENTS
 lst3 = [1,2,3,4,5]
 print(lst3[0])
 print(lst3[2])
 print(lst3[1])

#13) LENGTH OF LIST
 lst4 = [1,2,3,4,5]
 print(len(lst4))

#14) ADD ELEMENTS TO LIST
 lst5 = [1,2,3,4,5]
 lst5.append(6)
 print(lst5)

#15) INSERT ELEMENT IN LIST
 lst6 = [1,2,3,4,5]
 lst6.insert(1,4)
 print(lst6)

#16) REMOVE ELEMENTS FROM list
 lst7 = [1,2,3,4,5]
 lst7.remove(1)
 print(lst7)

#17) POP ELEMENTS FROM LIST
 lst8 = [1,2,3,4,5,6]
 popped = lst8.pop()
 print(popped)
 print(lst8)

#18) SORT LIST
 lst9 = [5,2,4,3,1]
 lst9.sort()
 print(lst9)

#19) REVERSE LIST
 lst10 = [1,2,3,4,5]
 lst10.reverse()
 print(lst10)

#20) CLEAR LIST
 lst11 = [1,2,3,4,5]
 lst11.clear()
 print(lst11)

#21) COPY A LIST
 lst12 = [1,2,3]
 lst13 = lst12.copy()
 print(lst13)

#22) JOIN TWO LISTS
 lst14 = [1,2,3]
 lst15 = [4,5,6]
 joined = lst14 + lst15
 print(joined)

#23) CHECK IF ELEMENT EXISTS IN LIST
 lst16 = [1,2,3,4,5]
 exists = 5 in lst16
 exist = 7 in lst16
 print(exists)
 print(exist)

#24) COUNT OCCURRENCES OF ELEMENTS IN LIST
 lst17 = [1,2,2,3,2,4,2]
 count = lst17.count(2)
 print(count)

#25) CONVERT LIST TO TUPLE 
 lst18 = [1,2,3]
 convert = tuple(lst18)
 print(convert)

#26) CREAT A SET
 st1 = {1,2,3,4,5}
 print(st1)

#27) ADD ELEMENTS TO SET
 st2 = {1,2,3,4,5}
 st2.add(6)
 print(st2)

#28) REMOVE ELEMENTS FROM SET
 st3 = {1,2,3,4,5,6}
 st3.remove(6)
 print(st3)

#29) CHECK IF ELEMENTS EXISTS
 st4 = {1,2,3,4,5}
 exists = 2 in st4
 exist = 9 in st4
 print(exists)
 print(exist)

#30) UNION OF SET
 st5 = {1,2,3}
 st6 = {4,5}
 union = st5.union(st6)
 print(union)

#31) INTERSECTION OF SET
 st7 = {1,2,3,4,5}
 st8 = {1,3,4,2,5,6,7,8}
 intersection = st7.intersection(st8)
 print(intersection)

#32) DIFFERENCE OF SET
 st9 = {1,2,3,4,5,6,7,8,9}
 st10 = {1,2,3,4,5}
 difference = st9.difference(st10)
 print(difference)

#33) SYMMETRIC DIFFERENCE IN A SET
 st11 = {1,2,3,4,5,6}
 st12 = {1,2,3,7,8,9}
 sym_diff = st11.symmetric_difference(st12)
 print(sym_diff)

#34) CHECK SUBSET
 st13 = {1,2,3}
 st14 = {1,2,3,4,5}
 sub = st13.issubset(st14)
 subset = st14.issubset(st13)
 print(subset)
 print(sub)

#35) SUPER SET 
 st15 = {1,2,3,4,5}
 st16 = {1,2,3}
 is_superset = st15.issuperset(st16)
 print(is_superset)

