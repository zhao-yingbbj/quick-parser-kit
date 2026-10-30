# quick-parser-kit

Everything should be made as simple as possible, but no simpler.

处理日常小任务的工具

## 用法

```bash
cat data.txt | ./run.sh
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 备注

就是给自己省点事，没做太多抽象。

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## License

MIT
