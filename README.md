# PytorchForcumcm
# 1. 从控制台获取输入的数字 a 和 n
a, n = map(int, input().split())

# 2. 初始化一个变量 s 用于存储总和，初始值为 0
s = 0

# 3. 使用循环计算每一项的值并累加到总和 s 中
for i in range(1, n + 1):
    # 计算当前项的值，通过字符串乘以数字的方式得到
    num = int(str(a) * i)
    # 将当前项的值累加到总和 s 中
    s += num

# 4. 按照要求的格式输出结果
print("s=%...
