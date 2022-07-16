# Python-Proje
1)
l = [[0,1], [2,3]]

flatten_list = [item for subl in l for item in subl]

   print(flatten_list)
   
   [0,1,2,3]

2)

def Ters(lst): 
    lst.reverse() 
    return lst 
      
lst = [10, 11, 12, 13, 14, 15] 
print(Ters(lst))
 
 [15,14,13,12,11,10]
