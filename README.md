# CS61A 2025 FALL

课程网址 https://cs61a.org/  
教材网址 https://www.composingprograms.com/  
推荐搭配DeepL使用

## homework

### hw04

- Q2: Deep Map  
考虑如何进入内层列表，可以使用递归

- Q5: Finding Berries:
如何正确遍历每一条分支  

错误代码

```py
     if is_tree(t):
        if label(t) == 'berry':
            return True
        else:
            for i in range(len(branches(t))):
                return berry_finder(branches(t)[i]) or False
    elif is_leaf(t):
        if label(t) == 'berry':
            return True
        else:
            return False
```
错误原因：只执行了第一条分支就返回值，没有遍历其他分支

## lab

### lab04

- Q3: Buying Fruit  
注意`display`函数的用法


## project


