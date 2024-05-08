计算a+b，但输入方式有所改变。

输入描述
第一行是一个整数N，表示后面会有N行a和b，通过空格隔开。

输出描述
对于输入的每对a和b，你需要在相应的行输出a、b的和。
如第二对a和b，对应的和也输出在第二行。
输入示例
2
2 4
9 21
输出示例
6
30
提示信息
注意，测试数据不仅仅一组。也就是说，会持续输入N以及后面的a和b


while True:
    try:
        n = int(input())
        for i in range(n):
            num = input()
            sum = num.split(' ')
            result = int(sum[0]) + int(sum[1])
            print(result)
    except EOFError:
        break
        
for循环在列表list的使用：
persons = ["simon","john","ken"]
for i in persons;
    print(i)

结果如下：
循环遍历第一次print为：simon
循环遍历第二次print为：john
循环遍历第三次print为：ken

for循环在字符串array的使用：
array = 'simon'
for i in array
    print(i)

结果如下：
循环遍历第一次print为：s
循环遍历第二次print为：i
循环遍历第三次print为：m....


此外你还可以使用内置的range()函数，生成一组连续的整数，然后在 for 循环中结合range来遍历一组连续的整数。

range()函数有以下三种用法：

range(stop)
range(start, stop)
range(start, stop, step)

例如在本体中已经给定输入为n行，那么
n = int(input())
for i in range(n)
    print(i)
