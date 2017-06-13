x1=[[1,2,3,4],[5,6,7,8],[9,10,11,12]]

rotated_p90 =[list(x) for x in zip(*x1[::-1])]#顺时针旋转90度
rotated_n90 =[list(x) for x in zip(*x1)][::-1]#逆时针旋转90度
trans=map(list,zip(*x1))#矩阵装置操作

print(rotated_p90)
print(rotated_n90)
print(list(trans))
