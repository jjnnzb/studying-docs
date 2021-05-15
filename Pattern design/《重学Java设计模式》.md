# Chap1. 设计模式介绍
## 是什么
- [Software Pattern design](https://en.wikipedia.org/wiki/Software_design_pattern);
  - Design patterns are formalized best practices that the programmer can use to solve common problems when designing an application or system.
    
- 软件设计最佳实践；
- 软件设计中，针对常见常见场景的一种解决方案，可以解决功能逻辑开发里遇到的共性问题。

## 发明者
- 1977, Christopher Alexander: "The Pattern of Streets", JOURNAL OF THE AIP, September 1977, Vol. 32, No. 3, pp. 273-278.
- 1994, "Gang of Four": Design Patterns: Elements of Reusable Object-Oriented Software.

## 类型
- 创建型模式：如何创建对象
- 结构型模式：如何组织对象
- 行为模式：对象之间如何高效沟通，职责传递委派

## 如何学习
- 看书
- 实践
- 练习

# Chap2. 六大设计原则
## 单一职责原则
- 定义： 一个Class，只负责一个职责（业务需求）

## 开闭原则
- 定义：对象、类、模块、函数对扩展应该是开放的，对于修改应该是封闭的。

## 里式替换原则
- 定义：继承需要确保超类所拥有的的性质在子类中依然成立。
    - 子类可以实现父类的抽象方法，但不能覆盖父类的非抽象方法；
    - 子类可以增加自己特有的方法；
    - 当子类方法重载父类方法时，方法的前置条件要比父类的方法更加宽松；
    - 当子类方法实现父类的方法时，方法的后置条件要比父类的方法更严格或与父类的方法相等。

## 迪米特法则
- 定义：客户端不应该被迫依赖其所不使用的方法；一个类对另外一个类的依赖应该是建立在最小的接口之上的。

## 接口隔离原则
- 定义：将臃肿庞大的接口拆分为更小、更具体的接口。

## 依赖倒置原则
- 定义：高层模块不应该依赖低层模块，二者都应该依赖于抽象。抽象不应该依赖于细节，细节应该依赖于抽象。
- 英文：Dependence 