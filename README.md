# comfy-echo-kit



给自己省点事的小工具

## 用法

```bash
cat data.txt | go run main.go
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

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 安装

```bash
git clone https://github.com/USER/comfy-echo-kit.git
cd comfy-echo-kit
go build ./...
```

## License

MIT
