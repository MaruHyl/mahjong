# qiai

## 查表法

fork yuanyunfeng大神的库，这里在之前的版本上重构了golang版本


1 所有代码按照go的语言规范和命名规范重写和排版

2 方法重新规划，包重新规划

3 提供新的序列化参数选择，新的序列化方式写文件可以减少30%的内存

4 查胡算法没动，生成表的算法基本没动，改了gen1113的算法，用了新的dp算法，减少没必要的冗余，benchmark比较大约优化了40%

5 补充了单元测试和性能测试，保证结果一致
