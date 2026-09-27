# JUnit Jupiter

[English](README.md) | [简体中文](README.zh-CN.md)

An adapter for test lifecycle, common annotations, and assertions from JUnit Jupiter API 6.1.2, whose package coordinates are defined in [module.norm](junit/jupiter/module.norm).

[Samples](samples/README.md) include a standalone consumer test with lifecycle and assertions.

```powershell
norm test samples/GreetingTest.norm
```

Test classes and methods are ordinary Norm code; the JUnit Platform handles discovery, lifecycle, and result aggregation.
