# 一. IoC控制反转
- 控制反转IoC: 控制权的转移，应用程序本身不负责依赖对象的创建和维护，而是有外部容器负责创建和维护。
- 依赖注入DI: 是一种实现方式，创建对象并且组装对象自检的关系。
# 二. Bean容器
- org.springframework.beans:bean容器的管理jar
- org.springframework.context:上下文jar
- BeanFactory提供配置结构和基本功能，加载并初始化Bean。
- ApplicationContext保存了Bean对象并在Spring中被广泛应用。
# Spring注入
- Spring注入是指在启动Spring容器加载bean配置的时候，完成对变量的赋值行为。
- 常用的两种注入方式：①设值注入(property)。②构造注入（consstructor-arg）。
- 