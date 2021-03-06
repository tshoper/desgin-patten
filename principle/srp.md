# 单一职责原则

> 仅有一个原因引起类的变更，设计好类的职责，且明确每个类的职责。在接口的设计中可以考虑下每个接口的职责是否单一。

单一职责原则（SRP）字义：
- 应该有且仅有一个原因引起类的变更。
> 业务逻辑，或者对象能够承担的责任，并以某种行为方式来执行。面向接口编程。

单一职责原则的好处：
- 类的复杂性降低。
- 可读性提高。
- 可维护性提高。
- 变更引起的风险降低，变更是必不可少的，如果接口的单一职责做得好，一个接口修改只对相应的实现类有影响，对其他的接口无影响，这对系统的扩展性、维护性都有非常大的帮助。

> 单一职责原则提出了一个编写程序的标准，用“职责”或“变化原因”来衡量接口或类设计得是否优良，但是“职责”和“变化原因”都是不可度量的，因项目而异，因环境而异。


> 单一职责为接口定义了一个规范
