# JUnit Jupiter samples

[English](README.md) | [简体中文](README.zh-CN.md)

[GreetingTest.norm](GreetingTest.norm) is a standalone consumer that uses a JUnit lifecycle hook and assertions from a Norm test class.

From the repository root, run the test:

```sh
norm test samples/GreetingTest.norm
```

Expected result: `1 found, 1 passed, 0 failed, 0 skipped`. [module.norm](../junit/jupiter/module.norm), which pins JUnit Jupiter API 6.1.2 and defines the exposed API.
