# SpringBoot启动流程
SpringBoot启动核心是`SpringApplication`类的`run()` 方法，整个启动流程可拆解为:
1. `SpringApplication`初始化
2. `SpringApplication`的`run`方法执行，同时涵盖Spring核心的`IOC`容器刷新、事件驱动、自动配置等机制


# 一、核心入口