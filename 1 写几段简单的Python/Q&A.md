# Q&A



## 1. 单引号，双引号，三引号？

> https://www.zhihu.com/question/59337505



## 2. 从`0`开始，从`-1`开始

> https://campus.datacamp.com/courses/intro-to-python-for-data-science/chapter-4-numpy?ex=11



## 3. “左闭右开”，不包括end

> https://campus.datacamp.com/courses/intro-to-python-for-data-science/chapter-2-python-lists?ex=9

```python
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Use slicing to create downstairs
downstairs = areas[:6]

# Use slicing to create upstairs
upstairs = areas[-4:]
```



>https://campus.datacamp.com/courses/intro-to-python-for-data-science/chapter-4-numpy?ex=7

```python
# Print out sub-array of np_height_in: index 100 up to and including index 110
print(np_height_in[100:111])
```



> https://campus.datacamp.com/courses/intermediate-python/case-study-hacker-statistics?ex=3



## 4. 需要（中文）帮助？

> https://www.runoob.com/python/python-tutorial.html



## 5. iterable是什么？

> https://www.jianshu.com/p/6b7806c4f54a



## 6. 运算符优先级

| 运算符                   | 描述                                                   |
| ------------------------ | ------------------------------------------------------ |
| **                       | 指数 (最高优先级)                                      |
| ~ + -                    | 按位翻转, 一元加号和减号 (最后两个的方法名为 +@ 和 -@) |
| * / % //                 | 乘，除，取模和取整除                                   |
| + -                      | 加法减法                                               |
| >> <<                    | 右移，左移运算符                                       |
| &                        | 位 'AND'                                               |
| ^ \|                     | 位运算符                                               |
| <= < > >=                | 比较运算符                                             |
| <> == !=                 | 等于运算符                                             |
| = %= /= //= -= += *= **= | 赋值运算符                                             |
| is is not                | 身份运算符                                             |
| in not in                | 成员运算符                                             |
| not and or               | 逻辑运算符                                             |

> https://www.runoob.com/python/python-operators.html

> https://campus.datacamp.com/courses/intermediate-python/logic-control-flow-and-filtering?ex=7



##  7. numpy array 和 Python list

> https://campus.datacamp.com/courses/intro-to-python-for-data-science/chapter-4-numpy?ex=6

>https://numpy.org/doc/stable/user/absolute_beginners.html
>
>## What’s the difference between a Python list and a NumPy array?
>
>NumPy gives you an enormous range of fast and efficient ways of creating arrays and manipulating numerical data inside them. While a Python list can contain different data types within a single list, all of the elements in a NumPy array should be **homogeneous**. The mathematical operations that are meant to be performed on arrays would be extremely inefficient if the arrays weren’t homogeneous.
>
>**Why use NumPy?**
>
>NumPy arrays are **faster** and more compact than Python lists. An array consumes less memory and is convenient to use. NumPy uses much less memory to store data and it provides a mechanism of specifying the data types. This allows the code to be optimized even further.



## 8. 方法和属性

### 属性

> https://campus.datacamp.com/courses/intro-to-python-for-data-science/chapter-4-numpy?ex=9
>
> https://campus.datacamp.com/courses/intro-to-python-for-data-science/chapter-4-numpy?ex=10

```python
# Print out the shape of np_baseball
print(np_baseball.shape)
```

`.`运算符后没有括号



### 方法

* 其实就是一个函数？



## 9. 换行

> https://www.php.cn/python-tutorials-419100.html

> https://campus.datacamp.com/courses/intermediate-python/matplotlib?ex=17

```python
# Specify c and alpha inside plt.scatter()
plt.scatter(x = gdp_cap, y = life_exp, 
            s = np.array(pop) * 2,
            c = col,
            alpha = 0.8 )
```



## 10. 函数会返回什么？

> https://docs.python.org/3/library/functions.html#enumerate
>
> https://docs.python.org/3/library/stdtypes.html#dict.items
