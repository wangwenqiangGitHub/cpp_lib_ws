# gtest
- class Environment环境对象能够设置和拆除环境，定义子类继承Environment类。环境对象在虚拟方法SetUp()和TearDown()中进行设置和分解，而不是在构造函数和析构函数中进行设置和分解。
	- 产生的异常不能从析构函数中抛出。
	- 构造函数和析构函数不能直接使用asert函数

