### Class
---

1. class是逻辑和数据的容器，python具有面向对象的特性，但是并不强制我们使用类。
2. 每个类对象或者实例对象被创建的时候，__init__函数是其第一个被调用的方法，但并不是其它语言中的构建函数，它的目的是为类对象被创建的时候，做一些初始化工作。
3. 自定义类中又自定义了__init__函数，系统会优先调用自定义的__init__方法。采用super(类名，self).__init__()与系统的__init__方法相关联起来。
4. self是类对象的自身引用。
5. 类名.__doc__可以输出类的docstring(文档字符串)。
