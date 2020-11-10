# test
作业
## 字典，元组，集合的使用方法
### 字典增的使用方法
dictory = {'猪':'pig','狗':'dog','狼':'holf'}
print(dictory)
dictory['鸟'] = 'bird'
print(dictory)
dictory = {'猪':'pig','狗':'dog','狼':'holf'}
print(dictory)
dictory['鸟'] = 'bird'
print(dictory)
{'猪': 'pig', '狗': 'dog', '狼': 'holf'}
{'猪': 'pig', '狗': 'dog', '狼': 'holf', '鸟': 'bird'}
### 添加多个元素
dictory = {'鸟':'bird','狗':'dog','狼':'holf'}
print(dictory)
dictory['猪'] = 'pig'
print(dictory)
dictory.update({'蜜蜂':'bee','猫':'cat'})
dictory = {'鸟':'bird','狗':'dog','狼':'holf'}
print(dictory)
dictory['猪'] = 'pig'
print(dictory)
dictory.update({'蜜蜂':'bee','猫':'cat'})
{'鸟': 'bird', '狗': 'dog', '狼': 'holf'}
{'鸟': 'bird', '狗': 'dog', '狼': 'holf', '猪': 'pig'}
### 删

dictory = {'我':'i','爱':'love','你':'you'}
print(dictory)
del dictory['你'] 
print(dictory)
dictory = {'我':'i','爱':'love','你':'you'}
print(dictory)
del dictory['你'] 
print(dictory)
{'我': 'i', '爱': 'love', '你': 'you'}
{'我': 'i', '爱': 'love'}
### 改
dictory = {'鸟':'bird','狗':'dog','狼':'holf'}
dictory["鸟"] = "you"
print(dictory)
{'鸟': 'you', '狗': 'dog', '狼': 'holf'}
### 查
dictory = {'我':'i','爱':'love','你':'you'}
prin
dictory = {'我':'i','爱':'love','你':'you'}
print(dictory['我'])
print(dictory)
i
{'我': 'i', '爱': 'love', '你': 'you'}
## 元组的使用方法
### 定义一个元组
t1 = ([1,2,3],4) 
print(t1)
([1, 2, 3], 4)
### 增加元组
t1 = ([1,2,3],4)
t1[0].append(4)
print(t1)
([1, 2, 3, 4], 4)
### 删除（注：元组的删除是删除整组）
t10000=(1,2,3,4)
del t10000
### 查找按#查找
## 集合的使用方法

a={10,20,30,40,50}
print(a)
{40, 10, 50, 20, 30}
### 增
a.add(60)
print(a)
{40, 10, 50, 20, 60, 30}
a.update([70,90])
print(a)
### 删
a.pop()
print(a)
{10, 50, 20, 60, 30}
### 找
print(a)
{10, 50, 20, 60, 30}
