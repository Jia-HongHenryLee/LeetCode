这道题究竟为什么通过率这么低？谁能告诉我。

这道题需要分析吗？不，一次迭代，排除其他字符，转为小写字母进行比对，对不上立刻 `false`，对上了继续。

最后没毛病就返回 `true`.

就这么简单。