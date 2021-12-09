引导可能会发生在任意功能模块内，且触发条件和完成条件各式各样，为了降低代码耦合和维护成本，需设计一套比较完善和低耦合的实现方式。

引导中的每个步骤称为任务，引导系统支持以下功能：

1. 可中断-恢复的任务
2. 任务组
3. 串行任务和并行任务
4. 任务数据的序列化和反序列化
5. 完全分离的代码配置

## 任务组

特性

1. 自动激活子任务

## 暂不支持

这些不支持的特性是因为当前不需要用到这些特性，实际上还是留有了扩展空间。

1. 细化的任务进度
2. 带蒙层的操作引导
