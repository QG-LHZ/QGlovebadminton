# QGlovebadminton

for i in range(10):
    print(i)
num = 0
for i in range(10):
    for j in range(10):
        num += 1
        print("这是",num,"次循环",i,j,i*j)

target = 99
perdict = 0
while int(perdict)!= target:
    perdict = input("请进行一次猜测")
    if int(perdict) > target:
        print ("猜大了！")
    elif int(perdict) < target:
        print ("猜小78了！")
    else:
        print("恭喜猜对！")












