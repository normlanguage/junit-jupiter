# JUnit Jupiter 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[GreetingTest.norm](GreetingTest.norm) 是独立的模块消费者，展示 Norm 测试类中的 JUnit 生命周期钩子与断言。

在仓库根目录运行测试：

```sh
norm test samples/GreetingTest.norm
```

预期结果：`1 found, 1 passed, 0 failed, 0 skipped`。[module.norm](../junit/jupiter/module.norm) 指定 JUnit Jupiter API 6.1.2 并定义公开 API。
