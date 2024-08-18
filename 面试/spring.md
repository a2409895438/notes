

# Spring

## 1. 什么是Spring的loC和Dl?

**IOC:** Spring 反向控制应用程序需要的资源。
**DI:** 应用程序依赖Spring为其提供资源。

IOC：是一种设计思想，意味着将设计好的对象交给容器控制，而不是传统的在对象内部直接控制。IOC容器可以理解为一个对象工厂，我们将对象交给工厂来管理其创建和依赖关系，开发者只需要关注业务逻辑。  好处在于将对象集中统一管理并且降低耦合度。

DI：是IOC的实现方式，由容器动态的将某个依赖关系注入到组件之中



## 2. Spring MVC 的核心组件有哪些？

### 2.1 [前端控制器](https://www.zhihu.com/search?q=前端控制器&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"answer"%2C"sourceId"%3A3464988294})：DispatcherServlet

DispatcherServlet 是Spring MVC的前端控制器，它负责将请求路由到不同的处理器。



# SpringBoot

https://www.yuque.com/snailclimb/mf2z3k/vqe4gz#hBEUb