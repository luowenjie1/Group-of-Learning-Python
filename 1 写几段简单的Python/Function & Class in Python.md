# Function & Class in Python

## Function (一个可以复用的代码块，一般包括输入、输出和中间的处理步骤)

- Simplest one [Session Ready](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/writing-your-own-functions?ex=4)

- With parameter [Session Ready](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/writing-your-own-functions?ex=10)

- Nested one [Session Ready](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/default-arguments-variable-length-arguments-and-scope?ex=6)

- With default argument [Session Ready](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/default-arguments-variable-length-arguments-and-scope?ex=11)
  
  - difference between parameter and argument?
    
    - The former is the variable,
    
    - The latter is the exact value,
    
    - However, in practice, people generally do not distinguish them

- 全局、局部对象

- With unlimited arguments [Session Ready](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/default-arguments-variable-length-arguments-and-scope?ex=12)

- Lambda [Session Ready](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/lambda-functions-and-error-handling?ex=3)

- Error raising [Session Ready](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/lambda-functions-and-error-handling?ex=10)

- The basic form of the python function:
  
  ```python
  def 函数名称(需要输入的参数):
      处理步骤
      [return 返回结果]
  ```

## Class (python 是面向对象编程，根据对象特征我们可以把它们抽象成类，每个类有共享的属性，和针对这些属性进行操作的方法； 我们可以根据类要求的属性创建一个对象，这个具体的对象叫做实例（instance）)

- Simplest one [Session Ready](https://campus.datacamp.com/courses/object-oriented-programming-in-python/oop-fundamentals?ex=6)

- Typical one (with methods and attributes) [Session Ready](https://campus.datacamp.com/courses/object-oriented-programming-in-python/oop-fundamentals?ex=10)
  
  - use initialize method to generate attributes for a class

- Inheritance
  
  - simplest inheritance [Session Ready](https://campus.datacamp.com/courses/object-oriented-programming-in-python/inheritance-and-polymorphism?ex=7)
  
  - build a new class based on the inherited class [Session Ready](https://campus.datacamp.com/courses/object-oriented-programming-in-python/inheritance-and-polymorphism?ex=9)

- The structure of a class (we do not discuss private and public here) [Session Ready](https://campus.datacamp.com/courses/object-oriented-programming-in-python/oop-fundamentals?ex=3)
  
  - type
  
  - dir
  
  - help
  
  - for naming convention [Session Ready](https://campus.datacamp.com/courses/object-oriented-programming-in-python/best-practices-of-class-design?ex=5)
  
  - more... 

- The basic form of the python class
  
  ```python
  class 类名称:
      def __init__(self, *arg): ##这个类的属性
          ...
      def 这个类的方法():
          ...
  实例 = 类名称（需要的属性）
  实例.方法()        
  ```

## Comparison

- function & class
  
  - 函数定义了一个处理方法；类定义了一个对象，包括一套属性和一套针对性的处理方法
  
  - 函数没有约定输入的参数类型，但如果输入的参数类型并不能处理，则会出错；类的方法是针对属性的，只要是一个实例化的对象都能处理
  
  - 函数适合线性的管道处理
  
  - 类适合数据管理和复杂处理，且具有更好的拓展性
  
  - 一个例子：https://zhuanlan.zhihu.com/p/108418193

- function & method
  
  - 定义：函数独立定义，方法在类内部定义，且必须带上实例（self）
  
  - 方法是属于特定类对象的函数

- package/module
  
  - 模块：一段代码块
  
  - 包：目录，多个模块

## More...

[PEP 8 – Style Guide for Python Code | peps.python.org](https://peps.python.org/pep-0008/)

[PEP 20 – The Zen of Python | peps.python.org](https://peps.python.org/pep-0020/)




