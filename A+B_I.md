你的任务是计算a+b。

输入描述
输入包含一系列的a和b对，通过空格隔开。一对a和b占一行。

输出描述
对于输入的每对a和b，你需要依次输出a、b的和。

如对于输入中的第二对a和b，在输出中它们的和应该也在第二行。

输入示例
3 4
11 40
输出示例
7
51

while 循环是一种在满足特定条件时重复执行代码块的控制结构
while True:
    try:
    # 尝试执行这里的程序
    except:
    # 捕获异常，执行异常处理代码
        break


while True:
    try:
        num = input()
        num = num.split('')
        sum = int(num[0]) + int(num[1])
        print(sum)
    except:EOFError
        break


num = input()
input作为输入，接受的是字符串，例如输入的是123，那么num接收的是"123"

num = num.split('')
可以使用split方法将输入的字符串分割，得到数据列表

sum = int(num[0]) + int(num[1])
数据列表通过index索引来进行访问，然后强制转换即可


