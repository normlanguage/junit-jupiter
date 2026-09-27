# JUnit Jupiter

[English](README.md) | [简体中文](README.zh-CN.md)

JUnit Jupiter API 6.1.2 的测试生命周期、常用 Annotation 与断言适配，发布坐标见 [module.norm](junit/jupiter/module.norm)。

[示例](samples/README.zh-CN.md)提供独立模块消费者的生命周期与断言测试。

```powershell
norm test samples/GreetingTest.norm
```

测试类和方法均为普通 Norm 代码；JUnit Platform 负责发现、生命周期与结果汇总。
