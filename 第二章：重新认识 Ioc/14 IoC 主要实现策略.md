- 维基百科的定义

  - Using a service locator pattern 服务定位模式，Java EE 里面定义的一种模式，主要通过 JNDI 的技术获取 JavaEE 的组件，例如 DataSource
  - Using dependency injection 依赖注入
    - Constructor injection 构造器注入
    - Parameter injection 参数注入
    - Setter injection setter 方法注入
    - Interface injection 接口注入

  - Using a contextualized look 上下文查找，例如 JavaBeans 技术，就有一个通用的 context，可以用来管理 Bean 的层次性
  - Using a template method design pattern 模板方法的设计模式，例如 Spring 里面 JDBC Template 的实现
  - Using strategy design 策略模式，不太好举例，用的不多

- Spring 的理念

  - Dependency Lookup 依赖查找
  - Dependency injection 依赖注入